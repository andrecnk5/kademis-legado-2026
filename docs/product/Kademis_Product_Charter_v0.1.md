# Kademis — Product Charter v0.1

**Versão:** v0.1  
**Status:** APROVADO — BASELINE ESTRATÉGICO DA FASE 1  
**Produto:** Kademis  
**Fase:** Fase 1 — Visão, Problema e Estratégia  
**Baseline metodológico:** Kademis Master Development Playbook v1.0  
**Baseline de governança:** Kademis — Governança do Projeto v1.0  
**Projeto legado de referência:** SGSA - Old  
**Instituição piloto:** Colégio Victorino  
**Data:** 20/09/2026

> Nota de versionamento: o Master Development Playbook v1.0 define explicitamente `Kademis_Product_Charter_v0.1.md` como artefato esperado da Fase 1. O status de aprovação deste documento é explícito e prevalece sobre qualquer interpretação baseada apenas no número de versão.

---

## 1. Objetivo deste documento

Este Product Charter estabelece o baseline estratégico inicial do Kademis.

Seu objetivo é registrar formalmente:

- por que o Kademis existe;
- qual problema pretende resolver;
- quais públicos são prioritários;
- qual valor pretende entregar;
- quais resultados estratégicos busca;
- quais princípios deverão orientar decisões futuras;
- o que explicitamente não pretende ser;
- como seu sucesso será observado e medido;
- quais hipóteses, riscos e pendências permanecem abertas.

Este documento não define funcionalidades detalhadas, requisitos funcionais ou não funcionais, regras de domínio detalhadas, UX/UI, arquitetura, stack, banco de dados, APIs, estratégia física de multi-tenancy, frontend, backend ou infraestrutura.

---

## 2. Visão do produto

O Kademis existe para tornar a gestão educacional digital mais acessível a instituições que ainda encontram barreiras econômicas e operacionais para abandonar processos baseados em papel.

O produto nasce como uma **plataforma multi-instituição**, concebida para apoiar a digitalização progressiva da gestão escolar sem obrigar diferentes instituições a funcionarem de maneira idêntica.

A ambição estratégica é permitir que instituições com menor capacidade de investimento tenham acesso a processos digitais organizados, confiáveis, rastreáveis e eficientes sem depender de soluções cujo custo inviabilize sua adoção.

---

## 3. Problema central

**Status:** VALIDADO

Instituições educacionais ainda mantêm parte relevante de suas rotinas acadêmicas e administrativas em diários de classe físicos e outros processos manuais.

No contexto inicialmente investigado pelo Kademis, especialmente em instituições observadas na região do Itaim Paulista, em São Paulo/SP, o custo das soluções digitais existentes representa uma das principais barreiras à adoção.

Essa limitação contribui para a permanência de processos com maior esforço operacional, repetição de trabalho, dificuldade de consulta, dependência de registros físicos e menor disponibilidade das informações escolares.

O problema estratégico do Kademis não é simplesmente a existência do papel.

> **O problema é a existência de barreiras econômicas e operacionais que impedem instituições de se beneficiarem adequadamente da digitalização de processos essenciais da gestão escolar.**

A constatação sobre custo é validada para o contexto inicial pesquisado pelo responsável pelo projeto e não deve ser generalizada automaticamente para todas as instituições brasileiras.

---

## 4. Públicos principais

### 4.1 Público institucional prioritário

**Status:** VALIDADO

O público institucional prioritário inicial é composto por instituições que oferecem:

- Ensino Fundamental — Anos Iniciais;
- Ensino Fundamental — Anos Finais;
- Ensino Médio.

A prioridade especial está em instituições que ainda utilizam total ou parcialmente diários de classe físicos e outros processos manuais e para as quais o custo constitui barreira relevante à digitalização.

### 4.2 Grupos humanos relacionados ao problema

**Status:** VALIDADO EM ALTO NÍVEL

Os principais grupos humanos relacionados ao problema incluem:

- responsáveis pela gestão institucional;
- equipes administrativas e secretariais;
- equipes pedagógicas;
- docentes;
- estudantes;
- responsáveis pelos estudantes.

Esta classificação não cria roles técnicas, permissões, perfis de acesso ou estruturas de autorização. Esses assuntos pertencem às fases posteriores.

### 4.3 Expansão futura

**Status:** ROADMAP

Poderão ser avaliados posteriormente:

- Educação Infantil;
- Educação de Jovens e Adultos;
- Ensino Técnico;
- Ensino Superior;
- cursos livres;
- outros contextos educacionais.

A inclusão futura dependerá de descoberta e validação próprias.

---

## 5. Estratégia inicial de validação

**Status:** VALIDADO

O **Colégio Victorino** será a instituição piloto e principal ambiente real de validação do Kademis durante seu primeiro ano de utilização.

Esse período deverá produzir evidências sobre:

- aderência dos processos;
- eficiência operacional;
- redução de dependência de papel;
- dificuldades de adoção;
- qualidade e consistência das informações;
- usabilidade;
- necessidade de suporte;
- problemas não previstos;
- custo real de operação e manutenção;
- sustentabilidade do modelo de produto.

A abertura comercial do Kademis ocorrerá somente após a avaliação desse primeiro ciclo real de utilização.

O Itaim Paulista e seu entorno constituem um contexto natural para a expansão comercial inicial após o piloto, devido ao conhecimento prévio do mercado e às evidências já coletadas na região. Isso não limita geograficamente o produto.

---

## 6. Proposta de valor

**Status:** VALIDADO

> **O Kademis pretende tornar a digitalização da gestão educacional economicamente mais acessível e operacionalmente viável, permitindo que instituições substituam progressivamente processos baseados em papel por processos digitais mais eficientes, organizados, confiáveis e rastreáveis.**

A proposta de valor se sustenta em quatro dimensões:

| Dimensão | Valor pretendido |
|---|---|
| Acessibilidade econômica | Reduzir a barreira financeira à adoção |
| Eficiência operacional | Reduzir esforço, repetição e retrabalho |
| Qualidade da informação | Melhorar organização, disponibilidade e rastreabilidade |
| Adequação institucional | Atender múltiplas instituições preservando particularidades sem fragmentar o núcleo do produto |

---

## 7. Objetivos estratégicos

**Status:** VALIDADO

| ID | Objetivo |
|---|---|
| OE-01 | Reduzir as barreiras econômicas para adoção da gestão escolar digital |
| OE-02 | Viabilizar a substituição progressiva de processos baseados em papel |
| OE-03 | Melhorar organização, disponibilidade, continuidade e rastreabilidade das informações escolares |
| OE-04 | Reduzir esforço operacional e retrabalho nas rotinas contempladas |
| OE-05 | Tornar as atividades cotidianas mais simples para os profissionais envolvidos |
| OE-06 | Melhorar a capacidade de acompanhamento institucional das informações escolares |
| OE-07 | Beneficiar estudantes e responsáveis com informações mais consistentes e acessíveis |
| OE-08 | Atender múltiplas instituições sem fragmentar o núcleo do produto |
| OE-09 | Manter um modelo economicamente sustentável para as instituições e para a continuidade do Kademis |
| OE-10 | Validar o produto em operação real antes da expansão comercial |

---

## 8. Princípios do produto

**Status:** VALIDADO

### PP-01 — Acessibilidade econômica

Custos adicionais deverão ser justificáveis pelo valor produzido.

A acessibilidade econômica deverá orientar decisões futuras sem antecipar soluções técnicas.

### PP-02 — Multi-instituição desde a origem

O Kademis não será concebido para uma instituição específica e adaptado posteriormente às demais.

A estratégia física ou arquitetural de multi-tenancy não é definida neste documento.

### PP-03 — Digitalização com propósito

Digitalizar deve melhorar o trabalho e a circulação da informação, não apenas substituir papel por uma tela equivalente.

### PP-04 — Simplicidade operacional

A complexidade técnica não deverá ser transferida aos usuários quando não for necessária para sua atividade.

### PP-05 — Integridade e rastreabilidade

Origem, contexto, autoria e histórico das informações deverão ser preservados quando o domínio exigir.

### PP-06 — Adoção progressiva

Uma instituição deverá poder obter valor do Kademis sem ser obrigada a digitalizar toda sua operação simultaneamente.

### PP-07 — Acessibilidade como requisito de produto

Acessibilidade deverá ser considerada desde a concepção, e não como melhoria posterior.

### PP-08 — Núcleo do produto separado da parametrização institucional

Particularidades institucionais não deverão fragmentar o núcleo do Kademis.

### PP-09 — Evidência antes de solução

Funcionalidades, processos e decisões futuras deverão ser justificadas por necessidade real, e não apenas pela existência em concorrentes ou no SGSA - Old.

### PP-10 — Sustentabilidade operacional

Baixo custo de adoção deverá coexistir com qualidade, suporte, manutenção e evolução sustentável do produto.

---

## 9. Não objetivos

**Status:** VALIDADO

O Kademis não pretende:

1. ser uma cópia ou modernização direta do SGSA - Old;
2. ser inicialmente um ERP educacional universal para todos os processos possíveis de qualquer instituição;
3. atender simultaneamente e com a mesma prioridade todos os níveis e modalidades educacionais;
4. digitalizar processos apenas porque existem em papel;
5. transformar particularidades de uma instituição em comportamento obrigatório para todas as demais;
6. substituir a autonomia pedagógica ou administrativa das instituições;
7. maximizar quantidade de funcionalidades como principal estratégia competitiva;
8. escolher tecnologia, arquitetura ou infraestrutura com base apenas em preferência técnica;
9. reproduzir automaticamente roles, módulos, menus, banco, fluxos, regras ou telas do SGSA - Old;
10. expor complexidade técnica aos usuários sem necessidade.

---

## 10. Critérios de sucesso

### 10.1 Meta estratégica de eficiência

**Status:** VALIDADO

> **Reduzir em pelo menos 50% o tempo necessário para execução dos processos de gestão escolar digitalizados pelo Kademis, comparados aos processos equivalentes anteriormente utilizados pela instituição piloto.**

A comparação deverá utilizar baseline coletado antes da substituição do processo.

A meta será aplicada aos processos e públicos efetivamente contemplados em cada etapa da implantação, evitando uma média genérica que esconda diferenças entre atividades.

A metodologia detalhada de medição, amostragem e validação será definida na fase apropriada.

### 10.2 Demais dimensões de sucesso

| Dimensão | Critério estratégico |
|---|---|
| Adoção | Usuários previstos efetivamente utilizando os processos digitais |
| Digitalização | Redução progressiva da dependência de registros físicos |
| Retrabalho | Redução de duplicações, transcrições e correções desnecessárias |
| Qualidade dos registros | Maior completude, consistência e disponibilidade |
| Continuidade | Uso sustentado ao longo do ciclo letivo |
| Usabilidade | Execução das tarefas sem complexidade desnecessária |
| Suporte | Identificação e redução de problemas recorrentes ao longo do piloto |
| Sustentabilidade | Operação, manutenção e suporte compatíveis com a proposta econômica |
| Validação institucional | Utilização real do Kademis durante o primeiro ciclo no Colégio Victorino |

---

## 11. Modelo econômico

### 11.1 Direção estratégica

**Status:** VALIDADO

O Kademis deverá buscar forte relação custo-benefício e reduzir a barreira econômica enfrentada pelas instituições.

### 11.2 Hipótese operacional/comercial

**Status:** PROPOSTO

Uma hipótese a ser avaliada é permitir que a instituição assuma diretamente determinados custos de hospedagem ou infraestrutura, remunerando o responsável pelo Kademis principalmente por manutenção, suporte e serviços associados.

Essa hipótese não constitui decisão de arquitetura, infraestrutura, contratação ou operação.

Sua consolidação dependerá das fases adequadas e de análise de custo, segurança, responsabilidade operacional, suporte e sustentabilidade.

---

## 12. Evidências e aprendizados

### 12.1 Evidência local

**Status:** VALIDADO PARA O CONTEXTO INICIAL

O responsável pelo projeto identificou, por experiência direta e pesquisa informal com professores de instituições da região do Itaim Paulista, que o custo de soluções digitais constitui barreira relevante à adoção.

Essa evidência fundamenta a estratégia inicial, mas não deve ser generalizada automaticamente para todo o mercado brasileiro.

### 12.2 SGSA - Old

**Status:** HISTÓRICO

O repositório `andrecnk5/sgsa` foi consultado como fonte de evidências e aprendizado.

Foram identificados historicamente processos relacionados a:

- estrutura acadêmica;
- matrícula e organização de turmas;
- registro de aula;
- frequência;
- tarefas e avaliações;
- ocorrências;
- horários e agenda;
- usuários e acesso;
- acompanhamento pedagógico;
- documentos;
- auditoria.

Esses elementos não constituem requisitos, módulos, regras ou estruturas técnicas do Kademis.

### 12.3 Evidências externas

A pesquisa inicial de sistemas e fontes institucionais confirmou a recorrência, no domínio educacional, de processos como:

- matrícula e enturmação;
- organização acadêmica;
- registro de aula e conteúdo;
- frequência;
- avaliações e notas;
- acompanhamento pedagógico;
- documentos e vida escolar;
- comunicação com estudantes e responsáveis;
- horários e agenda;
- registros institucionais.

Essas evidências orientam descoberta futura, mas não antecipam o escopo funcional do Kademis.

Fontes institucionais e de mercado consultadas na Fase 1 incluíram:

- INEP — Censo Escolar;
- Ministério da Educação — Gestão Presente na Escola;
- Secretaria da Educação do Estado de São Paulo — documentação de diário/frequência;
- documentação pública de plataformas de gestão educacional;
- SGSA - Old.

---

## 13. Hipóteses estratégicas

### HIP-01 — Modelo de custo operacional

**Status:** PROPOSTO

A transferência direta de determinados custos de infraestrutura para a instituição poderá contribuir para reduzir o preço de entrada e aumentar transparência de custos.

### HIP-02 — Adoção progressiva

**Status:** PROPOSTO

Permitir adoção gradual poderá facilitar a migração de instituições dependentes de processos físicos.

### HIP-03 — Simplicidade como fator de adoção

**Status:** PROPOSTO

Simplicidade operacional tende a ser um fator importante para adoção e permanência dos profissionais no uso do produto.

Essas hipóteses deverão ser testadas e não devem ser tratadas como fatos consolidados.

---

## 14. Riscos estratégicos

| ID | Risco | Impacto | Direção de mitigação |
|---|---|---|---|
| RSK-101 | Reduzir preço comprometendo sustentabilidade do produto | Alto | Medir custos reais antes da comercialização |
| RSK-102 | Reproduzir funcionalidades de concorrentes sem necessidade | Alto | Exigir rastreabilidade até problema e necessidade |
| RSK-103 | Importar decisões do SGSA - Old | Alto | Redescobrir e validar na fase adequada |
| RSK-104 | Personalização institucional fragmentar o produto | Alto | Separar núcleo de parametrização |
| RSK-105 | Usuários continuarem utilizando papel em paralelo | Alto | Medir adoção real durante o piloto |
| RSK-106 | Digitalização aumentar trabalho em vez de reduzi-lo | Alto | Comparar baseline e processo digital |
| RSK-107 | Piloto não representar mercados posteriores | Médio | Não generalizar evidências locais |
| RSK-108 | Crescimento prematuro de escopo | Alto | Aplicar não objetivos e Gates |
| RSK-109 | Meta de 50% ser medida de forma inadequada | Alto | Definir metodologia de medição antes da avaliação formal |

---

## 15. Pendências

### 15.1 BLOQUEANTES

Nenhuma pendência bloqueante registrada para o encerramento da Fase 1.

### 15.2 NÃO BLOQUEANTES

- definir posteriormente o modelo comercial definitivo;
- definir metodologia detalhada de mensuração da meta de 50%;
- levantar baseline operacional no Colégio Victorino antes da substituição dos processos selecionados;
- medir custos reais de operação, manutenção e suporte;
- caracterizar mercados posteriores ao piloto;
- validar hipóteses de adoção progressiva e simplicidade operacional.

### 15.3 ROADMAP

- Educação Infantil;
- EJA;
- Ensino Técnico;
- Ensino Superior;
- cursos livres;
- outros contextos educacionais;
- processos complementares não justificados pelo escopo futuro aprovado.

---

## 16. Relação com o SGSA - Old

O SGSA - Old permanece exclusivamente:

- referência histórica;
- fonte de evidências;
- fonte de aprendizados;
- fonte de problemas anteriormente investigados.

Não é baseline automático para:

- arquitetura;
- stack;
- banco;
- endpoints;
- roles;
- módulos;
- menus;
- navegação;
- Design System;
- regras de negócio;
- implementação.

Qualquer elemento reaproveitado deverá ser ratificado na fase correspondente do Kademis.

---

## 17. Limites desta baseline

Este Product Charter não autoriza ou define:

- MVP;
- funcionalidades detalhadas;
- requisitos funcionais;
- requisitos não funcionais;
- regras de domínio detalhadas;
- arquitetura de software;
- stack;
- framework;
- banco de dados;
- APIs;
- multi-tenancy físico;
- frontend;
- backend;
- infraestrutura;
- telas;
- fluxos de interface;
- Design System.

Essas decisões pertencem às fases posteriores do Master Development Playbook.

---

## 18. Checklist técnico da Fase 1

- [x] problema definido;
- [x] proposta de valor definida;
- [x] objetivos definidos;
- [x] não objetivos definidos;
- [x] critérios de sucesso definidos;
- [x] multi-instituição refletida na visão;
- [x] nenhuma solução técnica foi utilizada para definir o problema.

---

## 19. Checklist de validação humana

O responsável pelo projeto validou:

- [x] problema central;
- [x] custo como barreira relevante no contexto inicial;
- [x] público prioritário;
- [x] natureza multi-instituição;
- [x] proposta de valor;
- [x] objetivos estratégicos;
- [x] princípios do produto;
- [x] não objetivos;
- [x] meta de redução mínima de 50% do tempo nos processos medidos;
- [x] Colégio Victorino como instituição piloto;
- [x] primeiro ciclo dedicado à validação antes da abertura comercial;
- [x] SGSA - Old apenas como histórico e evidência;
- [x] expansão posterior de segmentos como ROADMAP.

---

## 20. Gate 1

O Kademis pode ser explicado em termos de problema, públicos, proposta de valor, objetivos, princípios e critérios de sucesso sem depender de telas ou tecnologia.

O responsável pelo projeto aprovou formalmente o Gate 1 em 20/09/2026.

> **Gate 1 — APROVADO**

A **Fase 1 — Visão, Problema e Estratégia está concluída**.

A Fase 2 — Negócio e Stakeholders não deve ser iniciada neste chat e dependerá de novo chat, reconstrução do estado oficial e autorização explícita do responsável pelo projeto.

---

## 21. Artefatos relacionados

- `docs/playbook/Kademis_Master_Development_Playbook_v1.0.md` — APROVADO — BASELINE METODOLÓGICO
- `docs/governance/Kademis_Governanca_v1.0.md` — APROVADO — BASELINE DE GOVERNANÇA
- `docs/brand/Kademis_Diretriz_Identidade_Visual_v0.1.md` — base visual inicial
- `andrecnk5/sgsa` — HISTÓRICO / evidência
