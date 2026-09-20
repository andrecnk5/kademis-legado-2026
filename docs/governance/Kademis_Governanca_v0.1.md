# Kademis — Governança do Projeto v0.1

**Versão:** v0.1  
**Status:** APROVADO — BASELINE DE GOVERNANÇA  
**Produto:** Kademis  
**Projeto no ChatGPT:** Kademis  
**Fase:** Fase 0 — Governança do Projeto  
**Baseline metodológico:** Kademis Master Development Playbook v1.0  
**Repositório oficial:** `andrecnk5/kademis`  
**Branch principal:** `main`  
**Data:** 19/09/2026

---

# 1. Objetivo

Este documento estabelece a governança operacional do Kademis.

Seu objetivo é definir como o projeto será:

- documentado;
- analisado;
- validado;
- aprovado;
- versionado;
- alterado;
- registrado;
- rastreado;
- conduzido no GitHub;
- conduzido com apoio de LLMs;
- transferido entre fases e chats do Projeto Kademis no ChatGPT.

Este documento operacionaliza as regras definidas pelo **Kademis Master Development Playbook v1.0**, sem substituí-lo.

Em caso de conflito com o Playbook vigente e aprovado, o conflito deverá ser explicitado e submetido à decisão do responsável pelo projeto.

---

# 2. Escopo da Governança

Esta governança aplica-se a:

- documentação;
- decisões de produto;
- decisões de domínio;
- requisitos;
- UX/UI;
- arquitetura;
- tecnologia;
- engenharia;
- código;
- banco de dados;
- infraestrutura;
- Git/GitHub;
- Figma;
- uso de LLMs;
- Gates;
- mudanças de baseline;
- handoffs entre fases.

Ela não define antecipadamente:

- arquitetura de software;
- stack;
- framework;
- banco de dados;
- estratégia física de multi-tenancy;
- autenticação;
- modelo de dados;
- endpoints;
- estrutura técnica do frontend ou backend.

Esses assuntos deverão ser tratados somente nas fases correspondentes do Playbook.

---

# 3. Princípios permanentes

Aplicam-se à governança os princípios do Master Development Playbook v1.0.

A prioridade geral é:

> **correção → segurança → integridade dos dados → consistência arquitetural → usabilidade → manutenibilidade → desempenho → sofisticação técnica**

Adicionalmente:

1. nenhuma decisão relevante será consolidada silenciosamente;
2. existência não implica aprovação;
3. memória de conversa não substitui fonte oficial;
4. evidência histórica não é baseline;
5. decisão de nível inferior deve ser justificável por decisão ou necessidade de nível superior;
6. nenhuma fase avança sem Gate correspondente;
7. autorização possui escopo e não deve ser extrapolada;
8. alterações relevantes devem preservar rastreabilidade;
9. mudanças irreversíveis exigem autorização explícita;
10. a governança deve ser suficientemente rigorosa para evitar inconsistências, mas simples o bastante para uso cotidiano.

---

# 4. Projeto Kademis no ChatGPT × Produto Kademis

O nome **Kademis** é utilizado tanto para o Projeto no ChatGPT quanto para o produto desenvolvido.

Para evitar ambiguidade:

**Projeto Kademis no ChatGPT** designa o ambiente de trabalho utilizado para:

- chats;
- instruções;
- contexto;
- análises;
- propostas;
- handoffs;
- interação com ferramentas.

**Produto Kademis** designa a plataforma multi-instituição de gestão educacional desenvolvida no projeto.

Quando houver risco de ambiguidade, os termos completos deverão ser utilizados.

Uma conversa no Projeto Kademis no ChatGPT não se torna baseline do produto apenas por existir.

---

# 5. Relação com o SGSA - Old

O SGSA - Old é classificado como **HISTÓRICO**.

Ele pode ser utilizado como:

- fonte de evidências;
- registro de decisões antigas;
- referência de problemas conhecidos;
- fonte de aprendizados;
- referência de fluxos anteriormente estudados;
- fonte de riscos;
- fonte de artefatos potencialmente reutilizáveis.

Ele não constitui baseline automático para:

- arquitetura;
- stack;
- banco;
- endpoints;
- modelo de dados;
- roles;
- módulos;
- menus;
- navegação;
- Design System;
- regras de negócio;
- implementação.

Qualquer elemento reutilizado deverá ser analisado e ratificado na fase adequada.

---

# 6. Fontes de verdade

Não existe uma única fonte absoluta para todas as categorias do projeto.

A autoridade é definida por categoria.

| Categoria | Fonte principal |
|---|---|
| Metodologia e Gates | Master Development Playbook vigente + decisões formais aprovadas |
| Estado atual do projeto | README + documentação vigente no GitHub |
| Governança | `docs/governance/` |
| Produto e negócio | artefatos de produto aprovados |
| Domínio | glossário, processos e regras de domínio validados/aprovados |
| Requisitos | artefatos de requisitos aprovados |
| UX/UI | Figma vigente + documentação de UX aprovada |
| Identidade visual | documentação de marca aprovada + artefatos visuais correspondentes |
| Arquitetura | ADRs + documentação arquitetural aprovada |
| Código | repositório oficial |
| Banco/migrations | repositório oficial |
| Infraestrutura | repositório + documentação operacional aprovada |
| Histórico | SGSA - Old e documentos classificados como históricos |

Quando duas fontes da mesma categoria entrarem em conflito:

1. identificar explicitamente o conflito;
2. verificar status e versão;
3. verificar aprovação;
4. prevalecerá a versão mais recente formalmente aprovada;
5. quando isso não puder ser determinado, registrar como **PENDENTE** ou **BLOQUEANTE**.

---

# 7. Estados oficiais das informações

São utilizados os estados previstos pelo Playbook:

- **EXISTENTE** — existe no projeto, sem implicar aprovação;
- **HISTÓRICO** — pertence ao legado ou a decisão substituída;
- **VALIDADO** — confirmado e aceito;
- **APROVADO** — autorizado formalmente como baseline;
- **INFERIDO** — conclusão lógica não validada;
- **PROPOSTO** — sugestão em análise;
- **EM DESCOBERTA** — depende de investigação;
- **PENDENTE** — necessita decisão;
- **BLOQUEANTE** — impede avanço;
- **ROADMAP** — intenção futura fora do escopo atual;
- **DEPRECATED** — não deve orientar novo trabalho.

## 7.1 VALIDADO ≠ APROVADO

Uma informação pode estar validada e ainda não estar autorizada como baseline.

Fluxo comum:

```text
PROPOSTO
→ análise
→ VALIDADO
→ aprovação formal
→ APROVADO
```

---

# 8. Governança documental

## 8.1 Localização

A estrutura documental conceitual do projeto é:

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

Pastas deverão ser criadas somente quando houver artefatos reais que justifiquem sua existência.

Não devem ser criadas estruturas vazias apenas para antecipar fases futuras.

## 8.2 Nomenclatura

Padrão preferencial:

```text
Kademis_<Nome_Do_Artefato>_vX.Y.md
```

Exemplos:

```text
Kademis_Governanca_v0.1.md
Kademis_Product_Charter_v0.1.md
Kademis_Arquitetura_v1.0.md
```

Datas não devem fazer parte do nome normal do arquivo.

## 8.3 Cabeçalho mínimo

Artefatos relevantes deverão registrar, quando aplicável:

- título;
- versão;
- status;
- produto;
- fase;
- data;
- baseline substituído;
- artefatos relacionados.

## 8.4 Versionamento

- `v0.x` — descoberta, proposta ou validação incompleta;
- `v1.0` — primeiro baseline aprovado;
- `v1.x` — evolução compatível;
- `v2.0` — mudança estrutural significativa.

A presença de um documento no GitHub não significa aprovação.

O status deve estar explícito dentro do documento.

---

# 9. Ciclo de vida documental

O fluxo normal é:

```text
criação
→ PROPOSTO
→ revisão
→ validação
→ VALIDADO
→ aprovação explícita
→ APROVADO
→ baseline vigente
```

Quando um baseline precisar mudar:

```text
necessidade de mudança
→ evidências
→ análise de impacto
→ nova proposta
→ validação
→ aprovação
→ nova versão
→ atualização das dependências
→ preservação do histórico anterior
```

A versão anterior poderá ser classificada como:

- **HISTÓRICO**; ou
- **DEPRECATED**.

A substituição nunca deverá apagar silenciosamente a existência da decisão anterior.

---

# 10. Autoridade de decisão

Existem quatro operações diferentes:

> **PROPOR → VALIDAR → APROVAR → EXECUTAR**

Elas não devem ser confundidas.

## 10.1 Responsável pelo Projeto

Enquanto não existir delegação formal específica, o Responsável pelo Projeto Kademis possui autoridade final para:

- aprovar Gates;
- aprovar baseline;
- rejeitar baseline;
- autorizar substituição de baseline;
- autorizar ações irreversíveis;
- autorizar mudanças estruturais;
- aprovar decisões de produto;
- aprovar arquitetura;
- aprovar tecnologia;
- autorizar implementação;
- autorizar releases.

## 10.2 Autoridades especializadas

Determinadas decisões deverão ser validadas por pessoas com autoridade ou conhecimento específico quando as fases correspondentes identificarem essa necessidade.

Não devem ser inventadas antecipadamente autoridades pedagógicas, administrativas, institucionais ou técnicas.

Quando a autoridade necessária ainda não tiver sido identificada:

> **PENDENTE — autoridade de validação ainda não definida**

## 10.3 Matriz inicial

| Categoria | Proposta/análise | Validação | Aprovação |
|---|---|---|---|
| Metodologia | responsável / LLM | responsável | responsável |
| Governança | responsável / LLM | responsável | responsável |
| Produto | responsável / equipe / LLM | autoridade pertinente | responsável |
| Domínio | especialistas / analistas / LLM | autoridade de domínio | responsável |
| UX/UI | design / LLM | validação adequada | responsável |
| Arquitetura | arquitetura / LLM | revisão técnica | responsável |
| Tecnologia | engenharia / LLM | revisão técnica | responsável |
| Implementação | engenharia / LLM | testes e revisão | conforme autorização do incremento |
| Operação irreversível | agente autorizado | responsável | responsável |

Essa matriz poderá evoluir conforme stakeholders e autoridades forem formalmente identificados.

---

# 11. Fluxo de decisão

Uma decisão relevante deverá seguir, quando aplicável:

```text
problema ou necessidade
→ evidências
→ classificação
→ proposta
→ análise de dependências
→ análise de impacto
→ validação
→ decisão humana
→ autorização operacional
→ registro
→ verificação
→ baseline
```

## 11.1 Decisão de conteúdo ≠ autorização operacional

Aprovar uma proposta não significa automaticamente autorizar:

- criação de arquivo;
- commit;
- push;
- merge;
- exclusão;
- alteração de Figma;
- deploy;
- migration.

O escopo da autorização deve ser explícito.

## 11.2 Escopo de autorização

Uma autorização vale somente para as ações que descreve.

Exemplo:

> “Autorizo criar a branch, adicionar o documento aprovado e abrir o PR.”

Isso não autoriza automaticamente:

- merge;
- outras alterações;
- alteração do Playbook;
- alteração do Figma;
- exclusões.

---

# 12. Mudança de decisões aprovadas

Decisões aprovadas não deverão ser substituídas silenciosamente.

Toda mudança relevante deverá registrar:

- decisão anterior;
- motivo da alteração;
- novas evidências;
- dependências;
- impactos;
- decisão proposta;
- artefatos afetados;
- versão nova;
- aprovação.

Quando apropriado:

```text
motivo
→ impacto
→ proposta
→ validação
→ aprovação
→ nova versão
→ atualização de rastreabilidade
```

Mudança estrutural significativa deverá resultar em nova versão principal quando aplicável.

---

# 13. Política Git/GitHub

## 13.1 Repositório

Repositório oficial:

```text
andrecnk5/kademis
```

Branch permanente principal:

```text
main
```

## 13.2 Significado da `main`

A `main` representa o estado integrado oficialmente reconhecido do repositório.

Alterações rotineiras relevantes não deverão ser desenvolvidas diretamente na `main` após a formalização desta Governança.

## 13.3 Branches de trabalho

Formato:

```text
<tipo>/<escopo-curto>
```

Tipos iniciais:

- `docs/`
- `feat/`
- `fix/`
- `refactor/`
- `test/`
- `chore/`

Exemplos:

```text
docs/governance
docs/product-charter
feat/attendance-registration
fix/absence-validation
```

Não serão introduzidas branches permanentes adicionais como `develop` sem necessidade comprovada.

## 13.4 Relação entre fases e branches

Não existe obrigação de uma branch por fase.

Uma fase pode produzir uma ou mais mudanças delimitadas e, consequentemente, uma ou mais branches.

A organização do Git não deve reproduzir artificialmente a estrutura do Playbook.

---

# 14. Commits

## 14.1 Formato

Formato preferencial:

```text
tipo(escopo): descrição
```

Baseado em Conventional Commits.

Exemplos:

```text
docs(governance): add project governance
docs(product): add product charter proposal
fix(attendance): reject invalid absence state
```

O escopo pode ser omitido quando não agregar valor.

## 14.2 Idioma

Preferencialmente:

- commits técnicos: inglês;
- documentação funcional do Kademis: português, enquanto esse for o idioma vigente do projeto.

## 14.3 Regras

Um commit deverá representar uma alteração coerente.

Evitar mensagens genéricas como:

```text
update
changes
fix
final
```

A mensagem do commit não substitui o status formal do artefato.

---

# 15. Pull Requests e merges

## 15.1 Pull Requests

Mudanças relevantes devem preferencialmente passar por PR.

PR é obrigatório por política para:

- novo baseline;
- alteração de baseline;
- arquitetura;
- código funcional;
- migrations;
- segurança;
- infraestrutura.

Correções documentais triviais podem utilizar processo simplificado quando explicitamente autorizadas.

## 15.2 Merge

Estratégia padrão:

> **Squash merge**

Objetivo:

- manter histórico da `main` legível;
- representar mudanças integradas;
- evitar excesso de commits intermediários na branch principal.

Outras estratégias poderão ser utilizadas quando houver justificativa técnica.

## 15.3 Autorização

Merge requer autorização explícita quando a mudança envolver decisões ou artefatos sujeitos a aprovação.

A abertura de um PR não autoriza automaticamente o merge.

---

# 16. Proteção da `main`

A `main` deverá ser protegida processualmente contra alterações acidentais.

No estado atual do repositório privado, determinados mecanismos de rulesets do GitHub podem depender do plano contratado.

Portanto:

> ausência de proteção técnica não equivale a ausência de política.

Enquanto mecanismos automáticos não estiverem disponíveis, serão utilizados:

- branches de trabalho;
- revisão;
- PR;
- autorização explícita;
- verificação pós-merge.

A proteção técnica poderá ser reforçada futuramente quando disponível.

---

# 17. Política de uso de LLM

LLMs podem atuar como:

- pesquisadores;
- analistas;
- revisores;
- arquitetos assistivos;
- desenvolvedores assistivos;
- documentadores;
- executores de ações autorizadas;
- validadores técnicos dentro de suas capacidades.

LLMs não possuem autoridade própria para:

- aprovar Gates;
- aprovar baseline;
- autorizar sua própria execução;
- transformar inferência em decisão;
- extrapolar autorização;
- substituir validação humana necessária.

## 17.1 Obrigações

Antes de trabalhar em uma fase, a LLM deverá:

1. consultar as Instruções do Projeto Kademis no ChatGPT;
2. consultar o repositório oficial;
3. verificar branch e HEAD reais;
4. consultar o README;
5. consultar o Playbook vigente;
6. consultar os artefatos necessários;
7. identificar baseline aprovado;
8. identificar pendências;
9. distinguir fatos, inferências e propostas;
10. executar somente a fase autorizada.

---

# 18. Um chat por fase

Regra operacional:

> **Cada fase do Kademis Master Development Playbook deverá possuir seu próprio chat dentro do Projeto Kademis no ChatGPT.**

Objetivos:

- reduzir contaminação de contexto;
- tornar o escopo de cada conversa explícito;
- obrigar reconstrução do estado oficial;
- preservar disciplina dos Gates;
- facilitar handoffs;
- impedir avanço silencioso de fase.

Essa regra não modifica o Playbook v1.0.

Ela operacionaliza sua execução.

---

# 19. Protocolo de inicialização de uma fase

Todo novo chat de fase deverá:

1. ler as Instruções do Projeto Kademis no ChatGPT;
2. acessar `andrecnk5/kademis`;
3. confirmar branch padrão;
4. confirmar HEAD real;
5. ler README;
6. ler Playbook vigente;
7. ler artefatos aprovados necessários;
8. confirmar Gate da fase anterior;
9. analisar o handoff recebido;
10. comparar handoff e fontes oficiais;
11. declarar divergências;
12. confirmar autorização;
13. somente então iniciar trabalho.

O handoff nunca substitui essa verificação.

---

# 20. Autoridade do handoff

A hierarquia é:

```text
artefato oficial aprovado
    >
handoff do chat anterior
    >
memória de conversas
```

Se o handoff divergir das fontes oficiais, a divergência deverá ser explicitada.

Não se deve corrigir silenciosamente uma fonte usando apenas memória do chat anterior.

---

# 21. Handoff entre fases

Após aprovação do Gate e registro autorizado dos artefatos, o chat deverá preparar o handoff para a próxima fase.

Conteúdo mínimo:

- Projeto no ChatGPT;
- produto;
- fase concluída;
- decisão do Gate;
- HEAD final verificado;
- branch;
- artefatos aprovados;
- artefatos históricos relevantes;
- decisões aprovadas;
- pendências bloqueantes;
- pendências não bloqueantes;
- roadmap;
- riscos;
- limites da próxima fase;
- ações proibidas;
- fontes obrigatórias;
- prompt completo de inicialização da próxima fase.

Nenhuma fase será iniciada dentro do chat da fase anterior.

---

# 22. Rastreabilidade

Aplicam-se os identificadores definidos pelo Playbook:

- `RF-xxx`
- `RNF-xxx`
- `RD-xxx`
- `RES-xxx`
- `PRE-xxx`
- `PEN-xxx`
- `RSK-xxx`
- `ADR-xxx`
- `UX-xxx`
- `SEC-xxx`

Não serão criadas novas categorias de identificadores sem necessidade concreta.

Decisões de governança podem ser rastreadas por:

```text
documento
+ versão
+ seção
+ Gate
+ commit
```

---

# 23. Riscos iniciais de governança

## RSK-001 — Chat tornar-se fonte informal de verdade

**Impacto:** Alto.

**Mitigação:** GitHub como registro persistente oficial; reconstrução de contexto em cada nova fase.

## RSK-002 — `main` sem proteção técnica

**Impacto:** Alto.

**Mitigação:** branches, PR, revisão, autorização e futura proteção técnica quando disponível.

## RSK-003 — Governança excessivamente burocrática

**Impacto:** Médio.

**Mitigação:** manter regras simples e concentradas; dividir documentos somente quando necessário.

## RSK-004 — Confusão entre aprovação e execução

**Impacto:** Alto.

**Mitigação:** separar explicitamente PROPOR, VALIDAR, APROVAR e EXECUTAR.

## RSK-005 — Figma divergir da documentação aprovada

**Impacto:** Médio/alto.

**Mitigação:** status explícito, rastreabilidade e verificação cruzada nas fases de UX/UI.

## RSK-006 — Memória entre chats divergir das fontes oficiais

**Impacto:** Alto.

**Mitigação:** protocolo obrigatório de inicialização.

## RSK-007 — Autoridade de domínio presumida

**Impacto:** Alto.

**Mitigação:** autoridades específicas somente após identificação e validação formal.

## RSK-008 — Baseline sobrescrito sem histórico

**Impacto:** Alto.

**Mitigação:** versionamento, análise de impacto e preservação da decisão anterior.

---

# 24. Pendências da Governança v0.1

## BLOQUEANTES

- integração do documento aprovado na `main`;
- validação do registro após integração antes do Gate 0 definitivo.

## NÃO BLOQUEANTES

- proteção técnica futura da `main`;
- criação futura de templates de PR;
- definição de CODEOWNERS se houver necessidade;
- autoridades especializadas ainda não conhecidas.

## ROADMAP

- automações adicionais de governança;
- políticas mais avançadas caso o número de colaboradores cresça;
- enforcement técnico adicional no GitHub quando necessário e disponível.

---

# 25. Checklist técnico da Fase 0

- [x] fontes de verdade definidas;
- [x] autoridade de decisão definida;
- [x] fluxo de aprovação definido;
- [x] convenções documentais definidas;
- [x] política de Git definida;
- [x] política de LLM definida;
- [x] processo de mudança definido;
- [x] nenhuma decisão técnica prematura foi introduzida.

---

# 26. Checklist de validação humana

A Governança v0.1 foi analisada e aprovada pelo responsável pelo projeto em 19/09/2026, contemplando:

- [x] autoridade final;
- [x] distinção entre propor, validar, aprovar e executar;
- [x] fontes de verdade;
- [x] distinção entre existência no GitHub e aprovação;
- [x] ciclo documental;
- [x] versionamento;
- [x] política de branches;
- [x] uso de Pull Requests;
- [x] squash merge como padrão;
- [x] adoção de Conventional Commits;
- [x] política processual para a `main`;
- [x] regra de um chat por fase;
- [x] protocolo de início dos chats;
- [x] modelo de handoff;
- [x] simplicidade operacional da governança.

---

# 27. Gate 0

A Governança v0.1 foi aprovada pelo responsável pelo projeto.

Para encerramento operacional da Fase 0, ainda deverão ocorrer:

1. registro deste documento no repositório;
2. commit autorizado;
3. revisão da alteração;
4. integração autorizada na `main`;
5. verificação do estado final no GitHub.

Até a integração e verificação final:

> **Gate 0 — APROVAÇÃO DE CONTEÚDO CONCLUÍDA; INTEGRAÇÃO PENDENTE**

A Fase 1 não poderá ser iniciada antes da conclusão e confirmação do Gate 0.
