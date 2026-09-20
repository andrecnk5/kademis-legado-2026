# Kademis — Master Development Playbook v1.0

**Status:** APROVADO — BASELINE METODOLÓGICO  
**Produto:** Kademis  
**Projeto legado de referência:** SGSA - Old  
**Data de consolidação:** 19/09/2026  
**Gate do Playbook:** APROVADO em 19/09/2026

---

# 1. Propósito deste Playbook

Este documento define a metodologia oficial para condução do **Kademis** desde sua fundação até operação e evolução contínua.

Ele tem duas funções simultâneas:

1. **governar o desenvolvimento do produto e do software**;
2. **governar como uma LLM, como o ChatGPT, deve atuar em cada fase do projeto**.

O objetivo é garantir que, em qualquer novo chat, sessão, ferramenta ou momento futuro, seja possível determinar com clareza:

- onde o projeto está;
- quais decisões já foram consolidadas;
- quais fontes possuem autoridade;
- quais artefatos precisam ser produzidos;
- quais atividades são permitidas;
- quais atividades são proibidas;
- quais critérios precisam ser validados;
- o que o responsável pelo projeto precisa conferir;
- quando é permitido avançar para a próxima fase.

---

# 2. Princípio metodológico central

O Kademis deverá evoluir segundo a seguinte hierarquia:

> **Governança → Estratégia → Negócio → Domínio → Produto → Requisitos → Experiência → Arquitetura → Tecnologia → Engenharia → Construção → Qualidade → Entrega → Operação → Evolução**

A lógica fundamental é:

> **Cada decisão de nível inferior deve ser justificável por uma necessidade, regra ou decisão de nível superior.**

Exemplo:

```text
Botão "Salvar"
    ↑
Fluxo de interação
    ↑
Jornada do usuário
    ↑
Requisito funcional
    ↑
Regra de domínio
    ↑
Necessidade do usuário
    ↑
Objetivo do produto
```

Outro exemplo:

```text
Índice no banco de dados
    ↑
Consulta
    ↑
Serviço/caso de uso
    ↑
Requisito de desempenho
    ↑
Requisito não funcional
```

---

# 3. Princípios permanentes do projeto

A prioridade do projeto será sempre:

> **correção → segurança → integridade dos dados → consistência arquitetural → usabilidade → manutenibilidade → desempenho → sofisticação técnica**

Também são permanentes os seguintes princípios:

- não programar antes de entender o problema;
- não escolher stack antes dos requisitos arquiteturais;
- não transformar telas diretamente em banco ou endpoints;
- não transformar perfis automaticamente em roles técnicas;
- não transformar zonas conceituais automaticamente em módulos ou serviços;
- não transformar páginas automaticamente em rotas;
- não adotar microsserviços, filas, caches ou infraestrutura distribuída sem necessidade comprovada;
- não criar abstrações "para o futuro" sem evidência real;
- não congelar regras de domínio que ainda estejam em descoberta;
- preservar autoria, origem, contexto e histórico quando o domínio exigir;
- garantir autorização no servidor;
- tratar UX como fonte de requisitos comportamentais, e não apenas aparência;
- tratar acessibilidade como requisito de produto;
- tratar multi-instituição como capacidade estrutural do Kademis;
- separar núcleo do produto de parametrização institucional;
- documentar decisões relevantes;
- validar tecnicamente toda implementação;
- nenhuma fase avança apenas porque "parece pronta".

---

# 4. Relação com o legado SGSA

O projeto anterior passa a ser identificado como:

> **SGSA - Old**

O SGSA - Old é:

- referência histórica;
- fonte de evidências;
- fonte de aprendizado;
- fonte de artefatos potencialmente reutilizáveis.

O SGSA - Old **não é baseline automático** para:

- arquitetura;
- stack;
- banco;
- endpoints;
- navegação;
- Design System;
- regras de negócio;
- implementação.

Qualquer decisão antiga que venha a ser reutilizada deverá ser explicitamente ratificada na fase correspondente do Kademis.

---

# 5. Fonte de verdade por categoria

Não existe uma única fonte absoluta para todo o projeto.

A autoridade será definida por categoria:

| Categoria | Fonte principal |
|---|---|
| Metodologia e gates | Este Playbook + decisões formais aprovadas |
| Estado atual do projeto | README + documentação vigente no GitHub |
| Produto e negócio | Product Charter, requisitos e decisões aprovadas |
| Domínio | Glossário, regras de domínio e processos validados |
| UX/UI | Figma vigente + documentação de UX aprovada |
| Arquitetura | ADRs, documentação arquitetural e requisitos arquiteturais |
| Código | Repositório GitHub oficial |
| Banco/migrations | Repositório GitHub oficial |
| Infraestrutura | Repositório + documentação operacional |
| Histórico | SGSA - Old e documentos explicitamente marcados como históricos |

Quando duas fontes da mesma categoria entrarem em conflito, prevalece a versão mais recente que tenha sido formalmente aprovada.

---

# 6. Classificação obrigatória das informações

Toda informação relevante deverá ser classificada quando houver risco de ambiguidade.

Estados oficiais:

- **VALIDADO** — confirmado e aceito;
- **APROVADO** — autorizado formalmente para uso como baseline;
- **EXISTENTE** — existe no projeto, mas não implica aprovação;
- **HISTÓRICO** — pertence ao legado ou a uma decisão substituída;
- **INFERIDO** — conclusão lógica ainda não validada;
- **PROPOSTO** — sugestão em análise;
- **EM DESCOBERTA** — depende de investigação;
- **PENDENTE** — precisa de decisão;
- **BLOQUEANTE** — impede avanço da fase;
- **ROADMAP** — intenção futura não pertencente ao escopo atual;
- **DEPRECATED** — não deve ser utilizado em novo trabalho.

---

# 7. Rastreabilidade

Os principais artefatos deverão utilizar identificadores.

Padrão inicial:

- `RF-xxx` — requisito funcional;
- `RNF-xxx` — requisito não funcional;
- `RD-xxx` — regra de domínio;
- `RES-xxx` — restrição;
- `PRE-xxx` — premissa;
- `PEN-xxx` — pendência;
- `RSK-xxx` — risco;
- `ADR-xxx` — Architectural Decision Record;
- `UX-xxx` — requisito/decisão de experiência quando necessário;
- `SEC-xxx` — requisito/decisão de segurança quando necessário.

Cada item deverá registrar, quando aplicável:

- ID;
- descrição;
- origem;
- evidência;
- status;
- prioridade;
- dependências;
- impacto;
- critério de aceite;
- artefatos relacionados.

---

# 8. Versionamento documental

Versões recomendadas:

- `v0.x` — descoberta, proposta ou validação incompleta;
- `v1.0` — primeiro baseline aprovado;
- `v1.x` — evolução compatível;
- `v2.0` — mudança estrutural significativa.

Um documento estar no GitHub **não significa automaticamente estar aprovado**.

O status deve aparecer dentro do próprio documento.

---

# 9. Política de commits e mudanças

Nenhuma alteração relevante deve ocorrer sem autorização explícita quando envolver:

- commit;
- push;
- merge;
- rebase;
- deploy;
- exclusão;
- migração;
- alteração de dados;
- modificação estrutural de Figma;
- mudança de arquitetura já aprovada.

Mudanças documentais previamente autorizadas devem ser:

1. produzidas;
2. revisadas;
3. validadas;
4. commitadas;
5. verificadas no GitHub.

---

# 10. Método de análise obrigatório

Em tarefas de análise, a LLM deverá seguir, quando aplicável:

> **estado atual → evidências → problema/requisito → dependências → proposta → impactos → decisão → implementação → validação**

Em fases anteriores à implementação, os passos "implementação" e "validação técnica" deverão ser substituídos pelos artefatos e critérios adequados à fase.

---

# 11. Protocolo global para LLM

Antes de executar qualquer etapa, a LLM deverá:

1. consultar o estado atual do projeto;
2. consultar as fontes da fase;
3. distinguir fatos de inferências;
4. identificar decisões já aprovadas;
5. identificar pendências;
6. não recriar soluções validadas sem motivo técnico;
7. não inventar arquivos, código, tabelas, APIs, telas ou resultados;
8. executar somente a etapa autorizada;
9. validar o próprio resultado;
10. apresentar checklist e gate;
11. aguardar autorização antes da próxima fase.

---

# 12. Estrutura padrão de um Gate

Todo gate deverá apresentar:

## Resultado da fase
- artefatos produzidos;
- decisões validadas;
- decisões ainda abertas.

## Pendências
Separar:

- bloqueantes;
- não bloqueantes;
- roadmap.

## Riscos
Listar riscos conhecidos e mitigação.

## Checklist técnico
Itens objetivos que comprovam qualidade da entrega.

## Checklist para o responsável pelo projeto
Perguntas em linguagem clara para permitir aprovação consciente.

## Decisão solicitada
Uma das opções:

- **APROVADO**
- **APROVADO COM RESSALVAS**
- **AJUSTES NECESSÁRIOS**
- **BLOQUEADO**

Somente **APROVADO** ou **APROVADO COM RESSALVAS não bloqueantes** permitem avançar.

---

# 13. Visão geral das fases

| Fase | Nome | Gate |
|---|---|---|
| 0 | Governança do Projeto | Gate 0 |
| 1 | Visão, Problema e Estratégia | Gate 1 |
| 2 | Negócio e Stakeholders | Gate 2 |
| 3 | Descoberta do Domínio | Gate 3 |
| 4 | Estratégia Multi-instituição | Gate 4 |
| 5 | Produto, Escopo e Roadmap | Gate 5 |
| 6 | Engenharia de Requisitos | Gate 6 |
| 7 | UX/UI | Gate 7 |
| 8 | Validação de Produto e UX | Gate 8 |
| 9 | Arquitetura de Software | Gate 9 |
| 10 | Seleção Tecnológica | Gate 10 |
| 11 | Fundação de Engenharia | Gate 11 |
| 12 | Implementação Incremental | Gate 12 por incremento |
| 13 | Verificação e Validação | Gate 13 |
| 14 | Release e Implantação | Gate 14 |
| 15 | Operação | Gate 15 |
| 16 | Evolução Contínua | Gates iterativos |

---

# FASE 0 — GOVERNANÇA DO PROJETO

## Objetivo

Definir como o Kademis será conduzido, documentado, validado e alterado.

## Pré-requisitos

- nome Kademis definido;
- repositório oficial existente;
- este Playbook aprovado como baseline metodológico.

## Subetapas

### 0.1 Definir governança documental
- fontes de verdade;
- versionamento;
- nomenclatura;
- status de documentos;
- localização dos artefatos.

### 0.2 Definir autoridade de decisão
- quem aprova produto;
- quem aprova domínio;
- quem aprova arquitetura;
- quem aprova implementação;
- quem pode autorizar mudanças irreversíveis.

### 0.3 Definir fluxo de decisão
- proposta;
- análise;
- decisão;
- registro;
- aprovação;
- atualização de baseline.

### 0.4 Definir política de Git/GitHub
- branch principal;
- branches de trabalho;
- commits;
- PRs;
- merges;
- proteção futura da `main`.

### 0.5 Definir política de uso de LLM
- consulta de fontes;
- limites;
- rastreabilidade;
- validação humana;
- proibição de inferências silenciosas.

## Artefatos esperados

- `docs/governance/Kademis_Governanca_v0.1.md`
- matriz de autoridades;
- convenções de versionamento;
- política de decisão;
- política de commits;
- política de LLM.

## Não fazer nesta fase

- escolher stack;
- criar backend;
- criar frontend;
- modelar banco;
- criar endpoints;
- criar autenticação;
- desenhar arquitetura técnica.

## Prompt operacional — Fase 0

```text
Atue como Arquiteto de Software Sênior e responsável por Governança de Engenharia.

Contexto:
Estamos estruturando o Kademis, uma plataforma multi-instituição de gestão educacional. O SGSA - Old é apenas referência histórica. Consulte o Master Development Playbook, o README oficial e os artefatos já aprovados antes de responder.

Objetivo:
Executar somente a Fase 0 — Governança do Projeto.

Método:
estado atual → evidências → lacunas → proposta → impactos → validação.

Tarefas:
1. identificar todas as decisões de governança necessárias;
2. definir autoridade por categoria de decisão;
3. definir fontes de verdade;
4. definir nomenclatura e versionamento de artefatos;
5. definir política de Git/GitHub;
6. definir política de uso de LLM;
7. definir processo de mudança de decisões aprovadas;
8. registrar riscos e pendências.

Regras:
- não escolher stack;
- não criar arquitetura;
- não criar banco, APIs ou código;
- não inventar papéis institucionais;
- não tratar histórico como baseline;
- classificar claramente VALIDADO, PROPOSTO, EM DESCOBERTA e PENDENTE.

Saída:
- análise estruturada;
- artefatos propostos;
- checklist técnico;
- checklist para aprovação humana;
- Gate 0.

Pare ao final do Gate 0 e aguarde autorização.
```

## Checklist técnico

- [ ] fontes de verdade definidas;
- [ ] autoridade de decisão definida;
- [ ] fluxo de aprovação definido;
- [ ] convenções documentais definidas;
- [ ] política de Git definida;
- [ ] política de LLM definida;
- [ ] processo de mudança definido;
- [ ] nenhuma decisão técnica prematura foi introduzida.

## O que o responsável precisa conferir

- [ ] Está claro quem decide cada tipo de assunto?
- [ ] Está claro onde cada informação oficial deve ficar?
- [ ] Está claro quando um documento é apenas proposta?
- [ ] Está claro quando um commit pode ser realizado?
- [ ] Está claro como uma decisão antiga pode ser substituída?
- [ ] A governança é simples o suficiente para ser usada no dia a dia?

## Gate 0

Aprovado quando a forma de trabalho do projeto estiver suficientemente clara para impedir decisões contraditórias ou não rastreáveis.

---

# FASE 1 — VISÃO, PROBLEMA E ESTRATÉGIA

## Objetivo

Definir formalmente por que o Kademis existe e qual problema resolve.

## Subetapas

### 1.1 Problema central
Descrever o problema sem mencionar tecnologia.

### 1.2 Públicos principais
Identificar quem sofre os problemas e quem se beneficia.

### 1.3 Proposta de valor
Definir como o Kademis melhora a situação atual.

### 1.4 Objetivos estratégicos
Definir resultados desejados.

### 1.5 Princípios do produto
Definir princípios que orientarão decisões.

### 1.6 Não objetivos
Explicitar o que o Kademis não pretende ser.

### 1.7 Critérios de sucesso
Definir como medir sucesso do produto.

## Artefato esperado

`docs/product/Kademis_Product_Charter_v0.1.md`

## Prompt operacional — Fase 1

```text
Atue como Product Strategist e Arquiteto de Software Sênior.

Objetivo:
Executar somente a Fase 1 — Visão, Problema e Estratégia do Kademis.

Use:
- Governança aprovada;
- conhecimento histórico do SGSA apenas como evidência;
- decisões explicitamente validadas.

Tarefas:
1. formular o problema central;
2. identificar públicos afetados;
3. definir proposta de valor;
4. definir objetivos;
5. definir princípios do produto;
6. definir não objetivos;
7. propor critérios de sucesso mensuráveis;
8. registrar hipóteses e pendências.

Não:
- definir funcionalidades detalhadas;
- desenhar telas;
- escolher stack;
- criar arquitetura;
- inventar requisitos sem evidência.

Diferencie fatos, inferências e propostas.

Finalize com checklist e Gate 1.
```

## Checklist técnico

- [ ] problema definido;
- [ ] proposta de valor definida;
- [ ] objetivos definidos;
- [ ] não objetivos definidos;
- [ ] critérios de sucesso definidos;
- [ ] multi-instituição refletida na visão;
- [ ] nenhuma solução técnica foi usada para definir o problema.

## Checklist para aprovação

- [ ] O problema descrito é realmente o problema que queremos resolver?
- [ ] O Kademis está sendo descrito de forma ampla demais?
- [ ] A proposta de valor é clara?
- [ ] Os objetivos são relevantes?
- [ ] Há algo que explicitamente deve ficar fora do produto?

## Gate 1

Aprovado quando for possível explicar o Kademis sem depender de telas ou tecnologia.

---

# FASE 2 — NEGÓCIO E STAKEHOLDERS

## Objetivo

Mapear atores, stakeholders, autoridades e relações de decisão.

## Subetapas

### 2.1 Stakeholders internos
### 2.2 Stakeholders externos
### 2.3 Usuários do produto
### 2.4 Autoridades de domínio
### 2.5 Responsabilidades
### 2.6 Conflitos e dependências
### 2.7 Matriz RACI quando útil

## Artefatos esperados

- `docs/product/Kademis_Stakeholders_v0.1.md`
- matriz de autoridades de domínio.

## Prompt operacional — Fase 2

```text
Atue como Analista de Negócios Sênior.

Objetivo:
Mapear stakeholders e autoridades do Kademis sem confundir stakeholder, perfil de usuário e role técnica.

Tarefas:
1. identificar stakeholders;
2. separar usuários operacionais de decisores;
3. identificar quem define regras pedagógicas, acadêmicas, administrativas e institucionais;
4. identificar dependências;
5. registrar conflitos de autoridade;
6. propor matriz de responsabilidade quando fizer sentido.

Não:
- transformar stakeholder em role técnica;
- criar RBAC;
- criar tabelas de usuários;
- assumir responsabilidades não confirmadas.

Finalize com checklist e Gate 2.
```

## Checklist técnico

- [ ] stakeholder ≠ usuário;
- [ ] usuário ≠ role técnica;
- [ ] autoridades de domínio identificadas;
- [ ] conflitos registrados;
- [ ] pendências explicitadas.

## Checklist para aprovação

- [ ] As pessoas/grupos que influenciam o produto estão representados?
- [ ] Quem decide regras pedagógicas está correto?
- [ ] Quem decide regras administrativas está correto?
- [ ] Há alguma autoridade importante ausente?

## Gate 2

Aprovado quando decisões de negócio puderem ser encaminhadas à autoridade correta.

---

# FASE 3 — DESCOBERTA DO DOMÍNIO

## Objetivo

Entender o domínio educacional antes de modelar software.

## Subetapas

### 3.1 Glossário
### 3.2 Processos
### 3.3 Objetos de domínio
### 3.4 Regras
### 3.5 Invariantes
### 3.6 Eventos de negócio
### 3.7 Estados
### 3.8 Exceções
### 3.9 Histórico e temporalidade
### 3.10 Pontos ainda em descoberta

## Exemplos de termos que precisarão ser validados

- instituição;
- unidade;
- ano letivo;
- período;
- turma;
- disciplina;
- aula;
- matrícula;
- frequência;
- ausência;
- justificativa;
- atestado;
- abono;
- reabertura;
- planejamento;
- conteúdo ministrado;
- avaliação;
- ocorrência;
- solicitação;
- responsável legal.

## Artefatos esperados

- `docs/domain/Kademis_Glossario_Dominio_v0.1.md`
- `docs/domain/Kademis_Processos_Dominio_v0.1.md`
- `docs/domain/Kademis_Regras_Dominio_v0.1.md`

## Prompt operacional — Fase 3

```text
Atue como Domain Analyst e Arquiteto de Software com experiência em modelagem de domínio.

Objetivo:
Executar a descoberta do domínio do Kademis sem transformar conceitos em banco ou código.

Tarefas:
1. construir linguagem ubíqua;
2. definir termos;
3. mapear processos;
4. identificar objetos de domínio;
5. identificar invariantes;
6. identificar eventos;
7. mapear estados e exceções;
8. identificar necessidades de histórico;
9. registrar regras ainda abertas;
10. indicar quais regras dependem de autoridade institucional.

Regras:
- planejamento não deve ser confundido com conteúdo ministrado;
- justificativa não deve ser tratada automaticamente como abono;
- preservar origem e histórico quando a regra indicar;
- não criar tabelas;
- não criar classes;
- não criar endpoints;
- não forçar DDD tático nesta fase.

Finalize com checklist e Gate 3.
```

## Checklist técnico

- [ ] glossário consistente;
- [ ] ambiguidades identificadas;
- [ ] regras de domínio rastreáveis;
- [ ] invariantes explicitadas;
- [ ] eventos relevantes identificados;
- [ ] histórico analisado;
- [ ] decisões abertas não foram congeladas.

## Checklist para aprovação

- [ ] Os termos usados refletem a linguagem real das instituições?
- [ ] Algum termo possui mais de um significado?
- [ ] Alguma regra foi presumida?
- [ ] Algum processo real ficou de fora?
- [ ] Alguma exceção importante não foi modelada?

## Gate 3

Aprovado quando o domínio puder ser explicado sem depender do desenho do banco.

---

# FASE 4 — ESTRATÉGIA MULTI-INSTITUIÇÃO

## Objetivo

Definir conceitualmente o que pertence ao Kademis e o que varia por instituição.

## Subetapas

### 4.1 Núcleo invariável
### 4.2 Parametrizações
### 4.3 Políticas institucionais
### 4.4 Branding
### 4.5 Calendário e períodos
### 4.6 Estrutura curricular
### 4.7 Limites de customização
### 4.8 Isolamento conceitual de dados
### 4.9 Estratégia de evolução entre instituições

## Artefato esperado

`docs/product/Kademis_Estrategia_MultiInstituicao_v0.1.md`

## Prompt operacional — Fase 4

```text
Atue como Arquiteto de Produto e Software especializado em SaaS multi-tenant.

Objetivo:
Definir a estratégia conceitual multi-instituição do Kademis.

Tarefas:
1. separar core, configuração, política e branding;
2. mapear variabilidades institucionais;
3. identificar invariantes;
4. identificar riscos de customização;
5. definir princípios de isolamento;
6. registrar pontos que futuramente influenciarão tenancy técnica.

Não:
- escolher shared schema, database-per-tenant ou outras estratégias físicas;
- escolher banco;
- criar tabelas;
- criar ifs específicos por escola;
- assumir que tudo é configurável.

Finalize com checklist e Gate 4.
```

## Checklist técnico

- [ ] core identificado;
- [ ] variabilidades classificadas;
- [ ] branding separado de regra de negócio;
- [ ] políticas institucionais reconhecidas;
- [ ] riscos de customização identificados;
- [ ] nenhuma estratégia física de tenancy congelada.

## Checklist para aprovação

- [ ] Está claro o que todas as instituições compartilham?
- [ ] Está claro o que cada instituição pode configurar?
- [ ] Existem diferenças reais que ainda não foram consideradas?
- [ ] O modelo evita customizações específicas em código?

## Gate 4

Aprovado quando for possível adicionar uma nova instituição conceitualmente sem redesenhar o produto.

---

# FASE 5 — PRODUTO, ESCOPO E ROADMAP

## Objetivo

Definir o que será construído primeiro e o que ficará para depois.

## Subetapas

### 5.1 Capacidades do produto
### 5.2 Escopo inicial
### 5.3 MVP
### 5.4 Não escopo
### 5.5 Roadmap próximo
### 5.6 Roadmap futuro
### 5.7 Dependências
### 5.8 Critérios de priorização

## Artefato esperado

`docs/product/Kademis_Escopo_Roadmap_v0.1.md`

## Prompt operacional — Fase 5

```text
Atue como Product Manager Sênior.

Objetivo:
Definir escopo, MVP e roadmap do Kademis a partir do domínio validado.

Tarefas:
1. listar capacidades;
2. identificar valor e dependências;
3. separar MVP, próxima etapa e roadmap;
4. definir não escopo;
5. justificar priorização;
6. registrar riscos de expansão prematura.

Não:
- incluir funcionalidade por simetria;
- assumir LMS completo;
- criar dashboards sem necessidade;
- usar complexidade técnica como justificativa de produto.

Finalize com checklist e Gate 5.
```

## Checklist técnico

- [ ] MVP claramente delimitado;
- [ ] não escopo explícito;
- [ ] roadmap separado de pendências;
- [ ] dependências mapeadas;
- [ ] critérios de priorização documentados.

## Checklist para aprovação

- [ ] O MVP entrega valor real?
- [ ] Existe algo essencial fora do MVP?
- [ ] Existe algo no MVP que pode esperar?
- [ ] Algum item de roadmap está sendo tratado como requisito atual?

## Gate 5

Aprovado quando o primeiro recorte de produto puder ser construído sem ambiguidade de escopo.

---

# FASE 6 — ENGENHARIA DE REQUISITOS

## Objetivo

Converter necessidades e regras em requisitos rastreáveis.

## Subetapas

### 6.1 RF
### 6.2 RNF
### 6.3 RD
### 6.4 Restrições
### 6.5 Premissas
### 6.6 Riscos
### 6.7 Critérios de aceite
### 6.8 Matriz de rastreabilidade

## Artefatos esperados

- `docs/requirements/Kademis_Requisitos_Funcionais_v0.1.md`
- `docs/requirements/Kademis_Requisitos_Nao_Funcionais_v0.1.md`
- `docs/requirements/Kademis_Matriz_Rastreabilidade_v0.1.md`
- `docs/requirements/Kademis_Riscos_Pendencias_v0.1.md`

## Prompt operacional — Fase 6

```text
Atue como Requirements Engineer Sênior.

Objetivo:
Transformar o escopo e o domínio aprovados em requisitos rastreáveis.

Tarefas:
1. criar RF;
2. criar RNF;
3. vincular regras de domínio;
4. registrar restrições;
5. registrar premissas;
6. registrar riscos;
7. definir critérios de aceite;
8. construir matriz de rastreabilidade.

Regras:
- requisito deve ser verificável;
- não inventar valores de desempenho;
- não escolher tecnologia;
- não converter UI em requisito sem justificar a necessidade;
- estados de UX relevantes devem virar drivers arquiteturais.

Finalize com checklist e Gate 6.
```

## Checklist técnico

- [ ] requisitos identificados;
- [ ] IDs únicos;
- [ ] critérios de aceite;
- [ ] origem rastreável;
- [ ] RNFs explícitos;
- [ ] riscos registrados;
- [ ] pendências não mascaradas.

## Checklist para aprovação

- [ ] Os requisitos descrevem realmente o que precisamos?
- [ ] Há algum requisito desnecessário?
- [ ] Há algum requisito importante ausente?
- [ ] Algum requisito está impossível de validar?

## Gate 6

Aprovado quando o escopo estiver representado por requisitos verificáveis e rastreáveis.

---

# FASE 7 — UX/UI

## Objetivo

Projetar a experiência a partir dos requisitos.

## Subetapas

### 7.1 Necessidades e tarefas
### 7.2 Jornadas
### 7.3 Arquitetura da informação
### 7.4 Sitemap
### 7.5 Navegação
### 7.6 Fluxos
### 7.7 Wireframes
### 7.8 Estados
### 7.9 Design System
### 7.10 Alta fidelidade
### 7.11 Responsividade
### 7.12 Acessibilidade

## Artefatos esperados

- Figma oficial;
- documentação de UX;
- matriz requisito → fluxo/tela.

## Prompt operacional — Fase 7

```text
Atue como Product Designer Sênior com forte experiência em sistemas operacionais complexos e acessibilidade.

Objetivo:
Projetar a UX/UI do Kademis com base nos requisitos aprovados.

Tarefas:
1. mapear tarefas;
2. criar jornadas;
3. definir IA;
4. criar sitemap;
5. definir navegação;
6. desenhar fluxos;
7. criar wireframes;
8. modelar estados e exceções;
9. construir Design System progressivamente;
10. validar responsividade e acessibilidade;
11. manter rastreabilidade com requisitos.

Regras:
- não criar telas por simetria;
- não criar sidebar ou dashboard sem jornada;
- não depender apenas de cor;
- tratar erro, conflito, somente leitura e perda de conexão como estados reais;
- preservar a identidade Kademis;
- respeitar multi-instituição;
- não alterar páginas fora do escopo.

Finalize com checklist e Gate 7.
```

## Checklist técnico

- [ ] requisitos cobertos;
- [ ] estados críticos modelados;
- [ ] acessibilidade considerada;
- [ ] responsividade considerada;
- [ ] Design System coerente;
- [ ] nenhuma tela sem necessidade comprovada.

## Checklist para aprovação

- [ ] Os usuários sabem onde estão?
- [ ] O contexto aparece antes da ação?
- [ ] Erros são compreensíveis?
- [ ] Existe risco de perda de trabalho?
- [ ] A navegação reflete tarefas reais?
- [ ] O visual representa o Kademis?

## Gate 7

Aprovado quando o produto puder ser compreendido e utilizado conceitualmente sem depender da implementação.

---

# FASE 8 — VALIDAÇÃO DE PRODUTO E UX

## Objetivo

Verificar se a solução proposta resolve o problema de forma compreensível e eficiente.

## Subetapas

### 8.1 Revisão analítica
### 8.2 Testes com usuários
### 8.3 Cenários críticos
### 8.4 Acessibilidade
### 8.5 Ajustes
### 8.6 Registro de evidências

## Artefato esperado

`docs/ux/Kademis_Validacao_Produto_UX_v0.1.md`

## Prompt operacional — Fase 8

```text
Atue como UX Researcher e Product Designer Sênior.

Objetivo:
Validar o produto e a UX antes da arquitetura técnica.

Tarefas:
1. revisar cobertura de requisitos;
2. executar avaliação heurística;
3. definir cenários de teste;
4. analisar testes de usabilidade quando disponíveis;
5. registrar problemas por severidade;
6. diferenciar evidência de hipótese;
7. propor ajustes;
8. declarar limitações da validação.

Não:
- declarar usabilidade comprovada sem teste real;
- esconder pendências;
- avançar para arquitetura se existirem problemas bloqueantes.

Finalize com checklist e Gate 8.
```

## Gate 8

Aprovado quando os principais fluxos estiverem suficientemente validados para orientar arquitetura, com limitações explicitadas.

---

# FASE 9 — ARQUITETURA DE SOFTWARE

## Objetivo

Transformar requisitos aprovados em decisões arquiteturais.

## Subetapas

### 9.1 Drivers arquiteturais
### 9.2 Limites de domínio
### 9.3 Modularização
### 9.4 Autorização
### 9.5 Segurança
### 9.6 Persistência conceitual
### 9.7 Concorrência
### 9.8 Auditoria
### 9.9 Integrações
### 9.10 Multi-tenancy técnica
### 9.11 ADRs

## Artefatos esperados

- `docs/architecture/Kademis_Arquitetura_v0.1.md`
- `docs/architecture/adr/ADR-xxx-*.md`

## Prompt operacional — Fase 9

```text
Atue como Software Architect Sênior.

Objetivo:
Derivar a arquitetura do Kademis a partir dos requisitos aprovados.

Tarefas:
1. identificar drivers arquiteturais;
2. propor limites e módulos;
3. analisar segurança e autorização contextual;
4. definir necessidades de persistência;
5. definir estratégia de concorrência;
6. definir auditoria;
7. analisar tenancy;
8. analisar integrações;
9. comparar opções;
10. registrar ADRs.

Princípios:
- começar simples;
- preferir arquitetura modular;
- evitar distribuição sem necessidade;
- preservar integridade;
- autorização server-side;
- histórico quando necessário;
- decisões devem citar requisitos.

Não:
- escolher stack por preferência;
- criar banco físico antes da modelagem;
- assumir RBAC simples;
- criar microsserviços por zona da IA.

Finalize com checklist e Gate 9.
```

## Gate 9

Aprovado quando a arquitetura explicar claramente como atender aos requisitos sem depender de tecnologia escolhida por hábito.

---

# FASE 10 — SELEÇÃO TECNOLÓGICA

## Objetivo

Escolher tecnologias com critérios objetivos.

## Subetapas

### 10.1 Critérios
### 10.2 Alternativas
### 10.3 PoCs quando necessárias
### 10.4 Segurança
### 10.5 Custo
### 10.6 Operação
### 10.7 Manutenção
### 10.8 Capacidade da equipe
### 10.9 ADRs finais

## Prompt operacional — Fase 10

```text
Atue como Software Architect e Tech Lead Sênior.

Objetivo:
Selecionar a stack do Kademis com base na arquitetura e nos requisitos.

Compare alternativas usando:
- correção;
- segurança;
- integridade;
- maturidade;
- manutenção;
- experiência da equipe;
- custo;
- implantação;
- ecossistema;
- desempenho;
- risco operacional.

Tecnologias históricas do SGSA podem ser avaliadas, mas não possuem prioridade automática.

Não:
- escolher tecnologia por popularidade;
- adotar complexidade sem requisito;
- criar PoC sem objetivo mensurável.

Registre decisões relevantes como ADR.

Finalize com checklist e Gate 10.
```

## Gate 10

Aprovado quando cada tecnologia importante possuir justificativa rastreável.

---

# FASE 11 — FUNDAÇÃO DE ENGENHARIA

## Objetivo

Preparar repositório, padrões e ambientes para desenvolvimento seguro.

## Subetapas

### 11.1 Estrutura real do repositório
### 11.2 Estratégia de branches
### 11.3 Convenções
### 11.4 Lint/format
### 11.5 Testes
### 11.6 Configuração
### 11.7 Segredos
### 11.8 CI
### 11.9 Ambientes
### 11.10 Documentação de onboarding

## Prompt operacional — Fase 11

```text
Atue como Tech Lead e DevOps Engineer Sênior.

Antes de editar qualquer arquivo:
1. leia a estrutura real do repositório;
2. confirme branch;
3. confirme permissões;
4. confirme stack aprovada;
5. analise impactos.

Objetivo:
Criar apenas a fundação necessária para desenvolvimento.

Não:
- criar infraestrutura não aprovada;
- adicionar dependências sem justificativa;
- realizar deploy;
- armazenar segredos;
- assumir caminhos inexistentes.

Após cada alteração:
- executar validações;
- informar arquivos alterados;
- informar comandos executados;
- registrar resultados reais.

Finalize com checklist e Gate 11.
```

## Gate 11

Aprovado quando um desenvolvedor puder clonar o projeto e iniciar trabalho de forma reproduzível.

---

# FASE 12 — IMPLEMENTAÇÃO INCREMENTAL

## Objetivo

Construir o produto por fatias verticais completas.

## Estratégia

Evitar:

```text
todo banco → todo backend → todo frontend
```

Preferir:

```text
caso de uso
+ domínio
+ persistência
+ segurança
+ API
+ UI
+ testes
```

## Subetapas por incremento

1. selecionar requisito;
2. confirmar dependências;
3. detalhar caso de uso;
4. implementar domínio;
5. implementar persistência;
6. implementar autorização;
7. implementar interface;
8. testar;
9. revisar;
10. validar com critérios de aceite.

## Prompt operacional — Fase 12

```text
Atue como Desenvolvedor Full Stack Sênior.

Antes de modificar código:
1. leia arquivos reais;
2. identifique dependências;
3. localize padrões existentes;
4. confirme requisitos e ADRs;
5. proponha alteração mínima.

Implemente somente o incremento autorizado.

Regras:
- código funcional;
- sem pseudocódigo quando implementação real for solicitada;
- não alterar arquitetura sem ADR;
- não quebrar compatibilidade sem necessidade;
- preservar integridade;
- aplicar autorização no servidor;
- validar tecnicamente;
- não fazer commit sem autorização.

Ao final:
- liste arquivos alterados;
- explique decisões relevantes;
- execute testes;
- registre limitações;
- apresente checklist do incremento.
```

## Gate 12

Cada incremento possui seu próprio gate e só é considerado concluído quando seus critérios de aceite passam.

---

# FASE 13 — VERIFICAÇÃO E VALIDAÇÃO

## Objetivo

Demonstrar que a implementação atende aos requisitos.

## Escopos

- testes unitários;
- integração;
- API;
- banco;
- concorrência;
- autorização;
- isolamento de tenants;
- segurança;
- acessibilidade;
- responsividade;
- desempenho;
- aceitação.

## Prompt operacional — Fase 13

```text
Atue como QA Engineer, Security Reviewer e Software Architect Sênior.

Objetivo:
Verificar o incremento/release do Kademis contra requisitos e critérios de aceite.

Tarefas:
1. mapear requisito → teste;
2. identificar lacunas;
3. executar testes disponíveis;
4. revisar segurança;
5. revisar isolamento multi-instituição;
6. revisar acessibilidade;
7. revisar falhas e recuperação;
8. classificar defeitos por severidade.

Não:
- declarar sucesso sem evidência;
- ignorar teste falho;
- mascarar limitações de ambiente.

Finalize com relatório e Gate 13.
```

## Gate 13

Aprovado quando não houver defeitos bloqueantes e a cobertura necessária estiver demonstrada.

---

# FASE 14 — RELEASE E IMPLANTAÇÃO

## Objetivo

Colocar uma versão em ambiente real de forma controlada.

## Sequência mínima

```text
build
→ testes
→ homologação
→ backup
→ migração
→ plano de rollback
→ deploy
→ smoke tests
→ validação
```

## Prompt operacional — Fase 14

```text
Atue como Release Engineer e DevOps Engineer Sênior.

Objetivo:
Planejar e executar somente a release autorizada.

Antes de qualquer ação:
- confirmar ambiente;
- confirmar versão;
- confirmar backup;
- confirmar migrations;
- confirmar rollback;
- confirmar janela;
- confirmar responsáveis.

Não:
- deploy sem autorização;
- migration destrutiva sem plano;
- alterar produção fora do escopo;
- ignorar rollback.

Após deploy:
- executar smoke tests;
- validar logs;
- validar métricas;
- registrar resultado.

Finalize com Gate 14.
```

## Gate 14

Aprovado quando a release estiver estável, validada e reversível.

---

# FASE 15 — OPERAÇÃO

## Objetivo

Manter o Kademis confiável após produção.

## Subetapas

### 15.1 Observabilidade
### 15.2 Logs
### 15.3 Métricas
### 15.4 Alertas
### 15.5 Backup
### 15.6 Restore
### 15.7 Incidentes
### 15.8 Segurança operacional
### 15.9 Suporte
### 15.10 Capacidade

## Prompt operacional — Fase 15

```text
Atue como Site Reliability Engineer e Software Architect Sênior.

Objetivo:
Operar o Kademis com foco em disponibilidade, segurança e recuperação.

Tarefas:
1. revisar saúde do sistema;
2. analisar logs e métricas;
3. validar backups;
4. validar restore;
5. tratar incidentes;
6. revisar capacidade;
7. registrar causas raiz;
8. propor melhorias rastreáveis.

Não:
- mascarar incidentes;
- alterar produção sem autorização;
- tratar backup não testado como confiável.

Finalize com checklist operacional e Gate 15.
```

---

# FASE 16 — EVOLUÇÃO CONTÍNUA

## Objetivo

Melhorar o produto com base em evidência real.

## Ciclo

```text
uso real
→ dados
→ feedback
→ problema
→ descoberta
→ priorização
→ incremento
→ validação
```

## Prompt operacional — Fase 16

```text
Atue como Product Manager, Product Designer e Software Architect Sênior.

Objetivo:
Avaliar oportunidades de evolução do Kademis com base em dados, feedback e estratégia.

Tarefas:
1. revisar métricas;
2. revisar feedback;
3. identificar problemas;
4. diferenciar sintoma de causa;
5. priorizar oportunidades;
6. avaliar impacto arquitetural;
7. atualizar roadmap;
8. encaminhar cada melhoria à fase adequada.

Não:
- implementar diretamente toda sugestão;
- tratar pedido isolado como requisito universal;
- criar complexidade sem evidência.

Cada evolução deve retornar à fase adequada do Playbook.
```

---

# 14. Regras específicas para identidade visual

A identidade atualmente consolidada do Kademis possui:

## VALIDADO
- direção: **Sabedoria tecnológica**;
- vermelho como assinatura de marca;
- vermelho não dominante na UI;
- base neutra/grafite;
- apoio cromático frio;
- independência do SGSA, Victorino e CNK5;
- marca mais expressiva que a interface;
- linguagem forte sem agressividade.

## AINDA EM VALIDAÇÃO
- hex definitivos;
- Sora + Inter;
- símbolo K geométrico;
- azul petróleo/teal funcional;
- logo final;
- tokens;
- iconografia.

O documento oficial vigente é:

`docs/brand/Kademis_Diretriz_Identidade_Visual_v0.1.md`

Esse artefato é anterior ao Gate 0 e deverá ser formalmente enquadrado pela Governança quando a Fase 0 for executada.

---

# 15. Estrutura documental inicial recomendada

Estrutura conceitual:

```text
docs/
├── governance/
├── product/
├── domain/
├── requirements/
├── ux/
├── brand/
├── architecture/
│   └── adr/
├── engineering/
├── operations/
└── legacy/
```

Esta estrutura é apenas organizacional e poderá ser refinada pela Fase 0.

Não implica criação imediata de todas as pastas.

---

# 16. Estado atual do Kademis

No momento da aprovação deste Playbook:

## EXISTENTE
- repositório oficial: `andrecnk5/kademis`;
- branch principal: `main`;
- repositório privado;
- README inicial;
- diretriz de identidade visual v0.1;
- conector GitHub limitado ao repositório Kademis.

## VALIDADO
- nome: **Kademis**;
- produto multi-instituição;
- SGSA como legado histórico;
- direção visual geral;
- necessidade de fases, checklists e gates;
- necessidade de prompts operacionais por fase;
- uso de GitHub como repositório documental e técnico;
- Master Development Playbook v1.0 como baseline metodológico aprovado.

## AINDA NÃO APROVADO COMO BASELINE
- governança formal;
- Product Charter;
- modelo de domínio;
- escopo/MVP;
- requisitos;
- nova UX;
- arquitetura;
- stack;
- estrutura técnica do repositório.

---

# 17. Checklist de aprovação deste Playbook

## Metodologia
- [x] A ordem das fases está adequada.
- [x] As fases cobrem todo o ciclo de vida.
- [x] Não existem fases importantes ausentes.
- [x] A sequência evita code-first.
- [x] A sequência evita excesso de planejamento antes de validar.

## Governança
- [x] As fontes de verdade estão claras.
- [x] Os status das informações estão claros.
- [x] A política de gates está clara.
- [x] A política de mudanças está clara.
- [x] A política de commits está clara.

## LLM
- [x] Os prompts são suficientemente claros.
- [x] Os prompts limitam avanço indevido.
- [x] Os prompts exigem consulta de fontes.
- [x] Os prompts exigem distinção entre fato e inferência.
- [x] Os prompts exigem validação antes de avançar.

## Produto e domínio
- [x] Multi-instituição aparece cedo o suficiente.
- [x] Descoberta de domínio ocorre antes da arquitetura.
- [x] Escopo/MVP ocorre antes dos requisitos detalhados.
- [x] UX deriva de requisitos e domínio.
- [x] Validação ocorre antes da arquitetura.

## Engenharia
- [x] Arquitetura vem antes da stack.
- [x] Stack vem antes da fundação de engenharia.
- [x] Implementação é incremental.
- [x] Qualidade não é deixada apenas para o final.
- [x] Release exige rollback e validação.
- [x] Operação e evolução estão contempladas.

---

# 18. Gate do Playbook

**Resultado:** APROVADO

O checklist do Master Development Playbook foi integralmente aprovado pelo responsável pelo projeto em **19/09/2026**.

Com esta decisão:

1. esta versão passa a ser **v1.0 — APROVADO — BASELINE METODOLÓGICO**;
2. a versão v0.1 permanece preservada como registro histórico da proposta;
3. o README deve apontar a v1.0 como referência metodológica vigente;
4. toda fase futura deverá respeitar os gates, limites e critérios definidos neste Playbook.

**Limite desta aprovação:** a **Fase 0 — Governança do Projeto não está autorizada a iniciar**. Ela permanece **PENDENTE DE AUTORIZAÇÃO EXPLÍCITA**.

---

# 19. Regra final

> **O Playbook orienta o projeto; ele não substitui julgamento técnico.**

Quando a realidade do produto justificar mudança de método, o Playbook poderá evoluir.

Mas nenhuma mudança estrutural deverá ocorrer silenciosamente.

Toda alteração deverá registrar:

- motivo;
- impacto;
- versão;
- decisão;
- aprovação.
