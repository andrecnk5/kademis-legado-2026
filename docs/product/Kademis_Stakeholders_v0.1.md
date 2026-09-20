# Kademis — Stakeholders v0.1

**Versão:** v0.1  
**Status:** APROVADO — BASELINE DE NEGÓCIO E STAKEHOLDERS DA FASE 2  
**Produto:** Kademis  
**Projeto no ChatGPT:** Kademis  
**Fase:** Fase 2 — Negócio e Stakeholders  
**Baseline metodológico:** Kademis Master Development Playbook v1.0  
**Baseline de governança:** Kademis — Governança do Projeto v1.0  
**Baseline estratégico:** Kademis Product Charter v0.1  
**Repositório oficial:** `andrecnk5/kademis`  
**Branch principal:** `main`  
**Instituição piloto:** Colégio Victorino  
**Data de aprovação do Gate 2:** 20/09/2026

---

## 1. Objetivo

Este documento consolida o resultado aprovado da **Fase 2 — Negócio e Stakeholders** do Kademis.

Seu objetivo é mapear, em nível de negócio:

- stakeholders internos;
- stakeholders externos;
- usuários diretos do produto;
- autoridades de domínio;
- responsabilidades;
- relações de decisão;
- conflitos e dependências;
- riscos relacionados a pessoas, autoridade e operação;
- descobertas que deverão ser aprofundadas nas fases posteriores.

Este documento **não cria roles técnicas, RBAC, permissões, tabelas, entidades de banco, módulos, menus, endpoints, APIs, arquitetura, telas ou fluxos de interface**.

---

## 2. Regra conceitual da Fase 2

Durante toda a interpretação deste artefato deve ser preservada a seguinte distinção:

> **stakeholder ≠ usuário ≠ perfil institucional ≠ cargo ≠ autoridade de domínio ≠ responsabilidade ≠ role técnica**

Uma pessoa poderá exercer múltiplas funções institucionais.

A existência de uma função institucional ou responsabilidade de negócio não cria automaticamente uma role técnica equivalente no software.

Exemplo:

> uma pessoa pode atuar como docente e também exercer função socioemocional; isso não implica a existência de `ROLE_PROFESSOR`, `ROLE_SOCIOEMOCIONAL` ou qualquer mecanismo técnico equivalente nesta fase.

---

## 3. Fontes e classificação das evidências

### 3.1 Baselines oficiais

Foram utilizados como fontes prioritárias:

- `docs/playbook/Kademis_Master_Development_Playbook_v1.0.md` — **APROVADO — BASELINE METODOLÓGICO**;
- `docs/governance/Kademis_Governanca_v1.0.md` — **APROVADO — BASELINE DE GOVERNANÇA**;
- `docs/product/Kademis_Product_Charter_v0.1.md` — **APROVADO — BASELINE ESTRATÉGICO DA FASE 1**.

### 3.2 Instituição piloto

O Colégio Victorino é fonte de **EVIDÊNCIA LOCAL VALIDADA** para compreensão de processos e relações reais.

Sua organização não constitui modelo universal do Kademis.

> **VALIDADO:** particularidades organizacionais do Colégio Victorino não deverão ser transformadas automaticamente em estruturas obrigatórias para outras instituições.

### 3.3 SGSA - Old

O repositório `andrecnk5/sgsa` foi consultado apenas como **HISTÓRICO**.

O SGSA - Old apresentava historicamente atores e perfis como professor, coordenação, secretaria, administrador, aluno e outros participantes.

Esses elementos serviram somente como evidência para redescoberta.

Nenhuma role, hierarquia, permissão, banco, módulo, menu ou regra técnica do SGSA foi adotada como baseline do Kademis.

### 3.4 Ambiente regulatório

São reconhecidas como referências externas relevantes:

- Lei Geral de Proteção de Dados Pessoais — LGPD;
- legislação aplicável à proteção de crianças e adolescentes;
- Estatuto Digital da Criança e do Adolescente — ECA Digital;
- regulamentações e orientações da ANPD;
- normas educacionais aplicáveis à instituição e ao contexto de utilização.

A aplicabilidade detalhada de cada dispositivo e as bases legais específicas de cada tratamento de dados deverão ser avaliadas nas fases apropriadas e, quando necessário, com validação jurídica especializada.

---

## 4. Princípio multi-instituição aplicado aos stakeholders

**Status:** VALIDADO

O Kademis é multi-instituição desde sua origem.

Consequentemente:

- o organograma do Colégio Victorino não será convertido em organograma obrigatório do produto;
- funções institucionais poderão possuir nomes e distribuições diferentes em outras instituições;
- uma responsabilidade poderá ser exercida por pessoas ou setores diferentes conforme a instituição;
- particularidades não estruturais deverão poder variar sem fragmentar o núcleo do produto;
- a estratégia técnica que possibilitará essa capacidade não pertence à Fase 2.

A Fase 2 registra **responsabilidades e relações de negócio**, não mecanismos técnicos de parametrização.

---

# 5. Stakeholders internos

## 5.1 Gestão Institucional / Mantença

**Status:** VALIDADO

Interesses e responsabilidades de alto nível:

- sustentabilidade institucional;
- eficiência operacional;
- adoção do Kademis no piloto;
- continuidade dos processos;
- decisões institucionais;
- equilíbrio entre custo, qualidade, segurança e benefício.

**Influência:** alta.  
**Impacto do Kademis:** alto.

---

## 5.2 Direção Pedagógica

**Status:** VALIDADO

Interesses e responsabilidades de alto nível:

- direção das políticas e práticas pedagógicas;
- coerência pedagógica institucional;
- acompanhamento dos processos educacionais;
- articulação com coordenação, docentes e equipes especializadas.

**Influência:** alta.  
**Impacto do Kademis:** alto.

---

## 5.3 Coordenação Pedagógica

**Status:** VALIDADO

Interesses e responsabilidades de alto nível:

- acompanhar docentes e estudantes;
- acompanhar processos pedagógicos cotidianos;
- orientar e apoiar o trabalho docente;
- colaborar na análise de situações que exijam acompanhamento especializado;
- participar da validação de processos pedagógicos.

**Usuário direto do Kademis:** VALIDADO.

**Influência:** alta.  
**Impacto do Kademis:** muito alto.

---

## 5.4 Docentes

**Status:** VALIDADO

Os docentes são stakeholders internos e usuários diretos centrais do Kademis.

Responsabilidades e interesses em alto nível:

- produzir registros originados na prática docente;
- registrar informações relacionadas às atividades pedagógicas;
- participar dos processos de frequência, conteúdo, atividades e outras rotinas que forem futuramente validadas;
- produzir observações contextuais quando apropriado;
- reduzir esforço operacional, repetição e retrabalho;
- preservar autoria e contexto dos registros;
- comunicar informações a estudantes e responsáveis quando o processo aprovado assim determinar.

Os docentes são especialistas na realidade da rotina docente, mas isso não os transforma automaticamente em autoridade final sobre todas as regras pedagógicas ou institucionais.

**Influência:** média/alta.  
**Impacto do Kademis:** muito alto.

---

## 5.5 Secretaria Escolar

**Status:** VALIDADO — SETOR DISTINTO

A Secretaria Escolar constitui setor próprio e não deve ser confundida com a função de Secretária da Coordenação.

Responsabilidades em alto nível:

- atividades relacionadas à vida escolar;
- registros e documentação institucional pertinentes;
- processos administrativos escolares sob sua responsabilidade;
- continuidade e consistência das informações escolares.

A autoridade final sobre regras de vida escolar e documentação ainda deverá ser formalizada quando os processos específicos forem descobertos.

**Usuário direto do Kademis:** VALIDADO em nível de grupo operacional.

**Influência:** alta.  
**Impacto do Kademis:** muito alto.

---

## 5.6 Secretária da Coordenação

**Status:** VALIDADO — FUNÇÃO DISTINTA

A Secretária da Coordenação é uma função de apoio à Coordenação e não constitui o mesmo setor que a Secretaria Escolar.

### Estado operacional atual no Colégio Victorino

**EVIDÊNCIA LOCAL VALIDADA**

Parte de seu trabalho atual decorre da necessidade de receber informações em papel e retransmiti-las digitalmente.

Entre as informações atualmente consolidadas ou comunicadas estão:

- registros de conteúdo;
- ocorrências;
- atividades futuras;
- lembretes;
- comunicações cotidianas destinadas aos responsáveis.

A comunicação diária com responsáveis utiliza atualmente o ClassApp.

### Impacto esperado da digitalização

**VALIDADO EM ALTO NÍVEL**

Parte dessa intermediação operacional tende a deixar de ser necessária quando a informação originada pelo professor puder ser registrada diretamente no Kademis e disponibilizada ao público adequado.

Isso não significa que a função Secretária da Coordenação deixará de existir.

Significa somente que:

> uma responsabilidade existente por causa da transferência manual entre papel e sistema não deve ser preservada artificialmente se a causa dessa intermediação desaparecer.

---

## 5.7 Coordenação de Tecnologia Educacional

**Status:** VALIDADO — STAKEHOLDER-CHAVE E USUÁRIO OPERACIONAL

No Colégio Victorino, a Coordenação de Tecnologia Educacional participará diretamente do projeto e da operação do Kademis.

Responsabilidades de negócio validadas em alto nível:

- administração operacional do Kademis na instituição piloto;
- cadastramento/gestão operacional dos ciclos letivos;
- cadastramento/gestão operacional de usuários;
- organização operacional de turmas;
- parametrizações institucionais necessárias à utilização cotidiana, quando futuramente definidas;
- apoio à adoção;
- validação especializada da viabilidade operacional;
- participação na validação futura de UX/UI.

A expressão **administrador do sistema** neste documento representa uma responsabilidade institucional de negócio.

Ela **não cria role técnica, RBAC ou permissão de software**.

**Influência:** alta no piloto.  
**Impacto do Kademis:** alto.

---

## 5.8 Psicopedagogia

**Status:** VALIDADO — USUÁRIO DIRETO E AUTORIDADE ESPECIALIZADA

Responsabilidades e interesses de alto nível:

- acompanhamento psicopedagógico;
- análise contextual de informações pertinentes ao desenvolvimento do estudante;
- colaboração com coordenação, docentes, família e demais participantes quando apropriado;
- participação na identificação e condução de ações de acompanhamento;
- validação especializada das necessidades psicopedagógicas do domínio.

O fato de uma informação poder ser útil à psicopedagogia não autoriza, nesta fase, acesso irrestrito a todos os dados do estudante.

---

## 5.9 Atuação socioemocional

**Status:** VALIDADO — USUÁRIO DIRETO E AUTORIDADE ESPECIALIZADA

No contexto atual do Colégio Victorino, essa função pode ser exercida por professores que acumulam atribuições.

Esse fato consolida a seguinte regra de negócio de alto nível:

> **uma pessoa física pode exercer múltiplas funções institucionais, e suas responsabilidades dependem do contexto em que atua.**

A atuação socioemocional participa do acompanhamento de estudantes e da validação especializada dos processos desse contexto.

Não é automaticamente equivalente à psicopedagogia, à docência, à coordenação ou a uma futura role técnica.

---

## 5.10 Estudantes

**Status:** VALIDADO — STAKEHOLDER INTERNO E USUÁRIO DIRETO

Os estudantes são:

- principais afetados pelos processos educacionais;
- beneficiários diretos da melhoria da informação escolar;
- titulares de grande parte dos dados tratados no contexto escolar;
- usuários diretos do Kademis.

### Autoridade

**VALIDADO:** estudantes não possuem autoridade formal de decisão, aprovação de Gate ou governança do produto Kademis.

Eventual participação futura em pesquisa, testes de usabilidade ou validação de experiência, se aprovada na fase adequada, não transfere autoridade de decisão sobre o produto.

---

# 6. Stakeholders externos

## 6.1 Pais e responsáveis

**Status:** VALIDADO — STAKEHOLDER EXTERNO E USUÁRIO DIRETO

Pais e responsáveis são participantes relevantes da relação escola–família.

Interesses e responsabilidades em alto nível:

- receber informações escolares pertinentes;
- acompanhar o estudante;
- participar de comunicações institucionais;
- participar de ações pedagógicas, psicopedagógicas ou socioemocionais quando apropriado;
- obter informações consistentes e contextualizadas.

Ser usuário direto não significa possuir autoridade sobre todas as decisões pedagógicas ou institucionais.

---

## 6.2 ANPD

**Status:** VALIDADO — REGULADOR EXTERNO

A ANPD é reconhecida como regulador externo relevante para:

- proteção de dados pessoais;
- tratamento de dados de crianças e adolescentes;
- matérias regulatórias relacionadas à LGPD;
- matérias de sua competência relacionadas ao ECA Digital.

A ANPD não constitui autoridade operacional interna da instituição nem consultoria jurídica do projeto.

---

## 6.3 Autoridades educacionais competentes

**Status:** PROPOSTO / DEPENDENTE DO PROCESSO

Órgãos educacionais e autoridades de supervisão poderão ser stakeholders externos quando processos do Kademis estiverem sujeitos às suas normas, declarações, documentação ou fiscalização.

No contexto do piloto paulista, isso poderá incluir órgãos do sistema de ensino competente e Supervisão de Ensino, conforme o processo.

A Fase 2 não cria requisito de integração com esses órgãos.

---

## 6.4 INEP

**Status:** PROPOSTO / DEPENDENTE DO ESCOPO FUTURO

O INEP é parte relevante do ambiente institucional da educação básica, especialmente quanto ao Censo Escolar.

Sua presença neste mapa não implica que o Kademis realizará integração, transmissão, importação ou qualquer processo técnico com o INEP.

A necessidade deverá ser demonstrada em fases posteriores.

---

## 6.5 Fornecedores e plataformas atuais

### ClassApp

**Status:** EXISTENTE — EVIDÊNCIA LOCAL DO PILOTO

O Colégio Victorino utiliza atualmente o ClassApp como parte da comunicação cotidiana com responsáveis.

**VALIDADO:** uma integração Kademis ↔ ClassApp **não faz parte do escopo pretendido**.

**PROPOSTO — encaminhar à Fase 5:** avaliar o Kademis como substituto do ClassApp no conjunto de capacidades de comunicação escola–estudante–família.

Essa direção não é ainda requisito funcional nem decisão de escopo do produto inicial.

---

# 7. Usuários diretos do produto

Os seguintes grupos estão **VALIDADOS** como usuários diretos do Kademis:

| Grupo | Estado |
|---|---|
| Gestão/Direção Institucional | VALIDADO |
| Coordenação Pedagógica | VALIDADO |
| Docentes | VALIDADO |
| Secretaria Escolar / operação correspondente | VALIDADO |
| Coordenação de Tecnologia Educacional | VALIDADO |
| Psicopedagogia | VALIDADO |
| Atuação socioemocional | VALIDADO |
| Estudantes | VALIDADO |
| Pais e responsáveis | VALIDADO |

A Secretária da Coordenação é stakeholder interno validado; sua necessidade de uso direto e as atividades que permanecerão após a digitalização deverão ser confirmadas durante a descoberta dos processos.

Nenhum item desta tabela cria role técnica.

---

# 8. Autoridades de domínio e validação

A autoridade final de aprovação dos baselines e Gates do Kademis permanece definida pela Governança v1.0.

As autoridades especializadas identificadas nesta fase são:

| Área | Autoridade / especialistas | Estado |
|---|---|---|
| Gestão institucional e adoção no piloto | Gestão Institucional / Mantença | VALIDADO |
| Diretrizes pedagógicas | Direção Pedagógica | VALIDADO |
| Operação pedagógica | Coordenação Pedagógica + Docentes | VALIDADO |
| Rotina docente | Docentes, com participação da Coordenação Pedagógica | VALIDADO |
| Acompanhamento psicopedagógico | Psicopedagogia | VALIDADO — autoridade especializada de validação |
| Acompanhamento socioemocional | Profissionais responsáveis pela atuação socioemocional | VALIDADO — autoridade especializada de validação |
| Administração operacional do Kademis no piloto | Coordenação de Tecnologia Educacional | VALIDADO |
| Adoção tecnológica e validação operacional/UX no piloto | Coordenação de Tecnologia Educacional | VALIDADO |
| Baselines e Gates do Kademis | Responsável pelo Projeto Kademis | APROVADO pela Governança v1.0 |
| Proteção de dados / ECA Digital | ANPD como regulador externo | VALIDADO |
| Vida escolar e documentação oficial | Autoridade institucional especializada ainda não formalizada | PENDENTE — não bloqueante |

## 8.1 Observação sobre privacidade

**PENDENTE — não bloqueante**

A ANPD é regulador externo.

Ainda não foi identificada, no contexto desta Fase 2, eventual autoridade interna, encarregado, assessoria jurídica ou especialista que validará decisões específicas de privacidade e proteção de dados para o piloto.

Essa lacuna deverá ser tratada antes de decisões que dependam de validação jurídica/privacidade.

---

# 9. Responsabilidades de negócio

| Responsabilidade | Participantes principais |
|---|---|
| Definir direção institucional | Gestão Institucional / Mantença |
| Definir e validar diretrizes pedagógicas | Direção Pedagógica |
| Acompanhar operação pedagógica | Coordenação Pedagógica |
| Produzir registros originados na atividade docente | Docentes |
| Acompanhar vida escolar e documentação sob sua competência | Secretaria Escolar |
| Apoiar Coordenação e executar atividades de apoio correspondentes | Secretária da Coordenação |
| Administrar operacionalmente o Kademis no piloto | Coordenação de Tecnologia Educacional |
| Apoiar adoção e validar viabilidade operacional | Coordenação de Tecnologia Educacional |
| Realizar acompanhamento psicopedagógico | Psicopedagogia |
| Realizar acompanhamento socioemocional | Profissionais responsáveis pela função socioemocional |
| Produzir observações contextuais de sala quando o processo for validado | Docentes |
| Analisar sinais e contexto para acompanhamento especializado | Psicopedagogia / socioemocional, com participação pedagógica pertinente |
| Participar de ações de acompanhamento quando apropriado | Família/responsáveis + instituição |
| Receber e utilizar informações escolares pertinentes | Estudantes e responsáveis |
| Aprovar baselines e Gates do Kademis | Responsável pelo Projeto |

Essas responsabilidades não são permissões de acesso.

---

# 10. Processo operacional atual de registro e comunicação no piloto

## 10.1 Estado atual

**Status:** EVIDÊNCIA LOCAL VALIDADA

Parte do fluxo atual ocorre aproximadamente da seguinte forma:

```text
Professor
   ↓
registro físico / diário
   ↓
Secretária da Coordenação
   ↓
consolidação / retransmissão
   ↓
ClassApp
   ↓
pais / responsáveis
```

As informações podem incluir:

- conteúdo ministrado;
- ocorrências;
- atividades futuras;
- lembretes;
- outras comunicações cotidianas.

Outros processos, como presença/ausência e vida escolar, poderão possuir fluxos próprios e deverão ser descobertos individualmente.

## 10.2 Direção de mudança validada em alto nível

O Kademis deverá reduzir intermediações cuja razão de existência seja somente a transferência manual de informação entre papel e plataforma digital.

Direção pretendida em alto nível:

```text
Professor
   ↓
Kademis
   ↓
informação disponível ao público adequado
```

Isso não define telas, notificações, permissões, workflows ou requisitos técnicos.

## 10.3 Princípio de autoria

**Status:** VALIDADO

> A pessoa ou setor que consolida, encaminha ou retransmite uma informação não deve substituir silenciosamente a autoria de quem a originou.

Autoria, origem, contexto e histórico deverão ser preservados quando o domínio exigir.

---

# 11. Descoberta validada — acompanhamento contextual, psicopedagógico e socioemocional

## 11.1 Direção

**Status:** VALIDADO PARA PROSSEGUIR EM DESCOBERTA

O Kademis deverá investigar e suportar uma capacidade de acompanhamento contextual do estudante que permita que observações realizadas no ambiente escolar contribuam para:

- acompanhamento pedagógico;
- acompanhamento psicopedagógico;
- acompanhamento socioemocional;
- identificação humana de padrões;
- possíveis ações de intervenção;
- colaboração com pais/responsáveis quando apropriado.

Essa direção é especialmente relevante no contexto do Colégio Victorino, onde o trabalho de inclusão e acompanhamento é parte importante da realidade institucional.

A solução deverá ser concebida para apoiar os estudantes sem transformar neurodivergência, deficiência, comportamento, personalidade ou diferenças individuais em rótulos negativos.

## 11.2 Limites conceituais

**Status:** VALIDADO

O Kademis não deverá utilizar essa capacidade para:

- diagnosticar condições psicológicas;
- diagnosticar condições psiquiátricas;
- diagnosticar condições neurológicas;
- diagnosticar condições médicas;
- produzir automaticamente conclusões clínicas;
- transformar observação isolada em atributo permanente do estudante;
- produzir ranking comportamental;
- usar uma percepção subjetiva como verdade clínica;
- substituir avaliação humana especializada.

## 11.3 Observação não é diagnóstico

Uma observação contextual deve descrever o que foi percebido no contexto escolar, preservando:

- autor da observação;
- momento;
- contexto;
- dimensão observada;
- eventual complemento necessário.

A semântica detalhada pertence à Fase 3.

## 11.4 Possíveis dimensões

**Status:** EM DESCOBERTA — Fase 3

Hipóteses que deverão ser investigadas:

- atenção percebida;
- participação;
- disposição percebida;
- engajamento;
- mudança relevante em relação ao comportamento habitual;
- estado emocional percebido, com cautela semântica reforçada.

Nenhuma escala está definida nesta fase.

## 11.5 Emojis

**Status:** PROPOSTO — Fase 7, condicionado às fases anteriores

Emojis ou outros controles visuais poderão ser avaliados como mecanismo de interação rápido para o docente.

> **Emoji é possibilidade de representação de interface, não conceito de domínio.**

A escolha visual não será realizada antes da descoberta do domínio, definição do escopo, requisitos e UX/UI.

## 11.6 Princípios de proteção

O desenvolvimento futuro dessa capacidade deverá observar:

- melhor interesse da criança e do adolescente;
- finalidade;
- necessidade;
- proporcionalidade;
- minimização;
- integridade;
- confidencialidade;
- rastreabilidade;
- preservação de contexto;
- proteção contra rotulação;
- acesso somente quando justificado pelas responsabilidades posteriormente definidas;
- legislação e regulamentação aplicáveis.

A base legal específica e o tratamento detalhado dos dados ainda não são definidos por este documento.

---

# 12. Relação humana de acompanhamento socioemocional

A relação de negócio identificada em alto nível é:

```text
docente observa
   ↓
registro contextual
   ↓
análise humana especializada
   ↓
coordenação/direção pedagógica quando pertinente
   ↓
família/responsáveis quando pertinente
   ↓
acompanhamento ou intervenção humana
```

O Kademis poderá apoiar essa relação, mas não deverá substituir a decisão humana especializada por conclusões automáticas.

---

# 13. RACI focal — acompanhamento contextual

Esta matriz é deliberadamente limitada ao processo que apresenta maior risco de confusão de responsabilidades.

**Status:** PROPOSTO — base para refinamento na Fase 3

Legenda:

- **R** — Responsible
- **A** — Accountable
- **C** — Consulted
- **I** — Informed

| Atividade | Docente | Psicopedagogia / socioemocional | Coordenação Pedagógica | Direção Pedagógica | Família |
|---|---:|---:|---:|---:|---:|
| Produzir observação contextual | R | C | C | I | — |
| Analisar recorrência e contexto especializado | C | R | C | I/C | — |
| Avaliar necessidade de acompanhamento | C | R | C | C/A conforme processo futuro | C quando pertinente |
| Planejar ação institucional | C | R/C | R/C | A conforme processo futuro | C |
| Acompanhar resultado | C | R | C | I | C |

A distribuição final de accountability deverá ser descoberta processo a processo na Fase 3.

---

# 14. Conflitos e dependências

## 14.1 Pessoa física × múltiplas funções

**VALIDADO**

Uma mesma pessoa pode exercer diferentes funções institucionais.

A responsabilidade deve ser entendida no contexto da função exercida, evitando confundir identidade pessoal com função ou autoridade.

## 14.2 Autoria docente × consolidação administrativa

**VALIDADO**

A consolidação de uma informação por outro participante não deve apagar a autoria e o contexto de sua origem.

## 14.3 Observação docente × interpretação especializada

**VALIDADO**

> observação contextual ≠ interpretação psicopedagógica ≠ diagnóstico clínico.

## 14.4 Acompanhamento × privacidade

**VALIDADO COMO DEPENDÊNCIA CRÍTICA**

Combinar frequência, desempenho, ocorrências e observações poderá gerar informação útil para acompanhamento, mas também aumenta a sensibilidade e o impacto potencial do tratamento.

As fases posteriores deverão aplicar proteção proporcional à finalidade e ao risco.

## 14.5 Instituição piloto × produto multi-instituição

**VALIDADO**

A estrutura do Victorino é fonte de evidência, não estrutura universal.

## 14.6 Papel × consolidação × plataforma externa

**VALIDADO COMO EVIDÊNCIA LOCAL**

O fluxo atual contém intermediações e retranscrições causadas pelo uso combinado de papel e plataforma digital.

Isso é candidato prioritário para descoberta e medição de eficiência.

## 14.7 ClassApp × Kademis

**VALIDADO / PROPOSTO**

- integração com ClassApp: **fora da direção de escopo pretendida**;
- substituição do ClassApp pelo Kademis: **PROPOSTO para avaliação na Fase 5**;
- comunicação direta escola–estudante–família: relação de negócio **VALIDADA**.

---

# 15. Riscos específicos da Fase 2

| ID | Risco | Impacto | Evidência | Tratamento inicial |
|---|---|---:|---|---|
| RSK-201 | Transformar estrutura do Victorino em modelo universal | Alto | Instituição piloto possui organização própria | Separar evidência local de estrutura comum do produto |
| RSK-202 | Observação socioemocional tornar-se rótulo ou diagnóstico | Alto | Natureza subjetiva do registro | Separar observação, interpretação e diagnóstico |
| RSK-203 | Exposição excessiva de informações do estudante | Alto | Potencial combinação de dados escolares e sensíveis | Finalidade, minimização e acesso justificado nas fases adequadas |
| RSK-204 | Viés observacional | Alto | Profissionais podem interpretar comportamentos de formas distintas | Contextualização, formação, semântica cuidadosa e ausência de conclusões automáticas |
| RSK-205 | Transformar cuidado em vigilância comportamental | Alto | Possibilidade de registros frequentes sobre comportamento | Evitar coleta excessiva, scoring e monitoramento indiscriminado |
| RSK-206 | Apagar autoria durante consolidação | Alto | Fluxo atual possui retransmissão | Preservar autor, origem, momento, contexto e histórico |
| RSK-207 | Acúmulo de funções gerar conflito de autoridade | Médio/Alto | Professores podem exercer funções socioemocionais e outras | Separar pessoa, função, responsabilidade e autoridade |
| RSK-208 | Perder contexto na transcrição/republicação | Alto | Papel → consolidação → ClassApp | Reduzir retranscrição e preservar informação original |
| RSK-209 | Papel, Kademis e ClassApp coexistirem de modo permanente | Alto | Adoção progressiva pode gerar duplicidade | Planejar transição sem institucionalizar trabalho triplo |
| RSK-210 | Digitalizar uma intermediação que só existe por causa do papel | Alto | Secretária da Coordenação hoje retransmite dados | Descobrir a razão de cada etapa antes de reproduzi-la digitalmente |

Os riscos estratégicos RSK-101 a RSK-109 do Product Charter permanecem vigentes.

---

# 16. Pendências

## 16.1 BLOQUEANTES

**Nenhuma pendência bloqueante identificada para o encerramento da Fase 2.**

## 16.2 NÃO BLOQUEANTES

### PEN-201 — Autoridade sobre vida escolar e documentação oficial

**Status:** PENDENTE

Formalizar, após descoberta dos processos, quem possui autoridade institucional especializada para validar regras de vida escolar e documentação.

### PEN-202 — Validação interna de privacidade e proteção de dados

**Status:** PENDENTE

Identificar, quando necessário, encarregado, assessoria jurídica, consultoria ou outra autoridade especializada interna/contratada para validação de questões específicas de LGPD e proteção de dados.

A ANPD permanece regulador externo.

### PEN-203 — Semântica do acompanhamento contextual

**Status:** PENDENTE — Fase 3

Descobrir conceitos, limites, contexto, autoria, significado e relações do acompanhamento pedagógico/psicopedagógico/socioemocional.

### PEN-204 — Processo da Secretária da Coordenação após digitalização

**Status:** PENDENTE — Fase 3

Identificar quais responsabilidades permanecem, mudam ou deixam de ser necessárias quando a transferência manual entre papel e plataforma for eliminada.

### PEN-205 — Substituição do ClassApp

**Status:** PROPOSTO — Fase 5

Avaliar formalmente se a comunicação do Kademis substituirá integralmente o ClassApp no escopo aprovado do produto.

### PEN-206 — Tratamento detalhado de dados socioemocionais

**Status:** PENDENTE — fases posteriores

Definir finalidade, base legal, minimização, retenção, acesso, transparência, segurança, auditoria e demais obrigações aplicáveis quando o tratamento concreto estiver definido.

## 16.3 Pendências herdadas da Fase 1

Permanecem não bloqueantes:

- modelo comercial definitivo;
- metodologia detalhada da meta de redução de 50%;
- baseline operacional dos processos do piloto;
- custos reais de operação, manutenção e suporte;
- caracterização dos mercados posteriores;
- validação das hipóteses de adoção progressiva e simplicidade operacional.

## 16.4 ROADMAP

Permanecem conforme Product Charter:

- Educação Infantil;
- EJA;
- Ensino Técnico;
- Ensino Superior;
- cursos livres;
- outros contextos educacionais ainda não priorizados.

---

# 17. Encaminhamentos obrigatórios às fases posteriores

## Fase 3 — Descoberta do Domínio

Prioridades identificadas:

1. vida escolar e documentação;
2. registro de aula e autoria;
3. frequência;
4. relação professor → registro → estudante/responsável;
5. comunicação escola–família;
6. papel atual da Secretária da Coordenação;
7. acompanhamento psicopedagógico;
8. acompanhamento socioemocional;
9. observação contextual do estudante;
10. intervenções e participação da família;
11. pessoas com múltiplas funções institucionais.

A presença nesta lista não transforma esses itens automaticamente em módulos.

## Fase 4 — Estratégia Multi-instituição

Deverá considerar:

- variação de organogramas;
- variação de nomes de funções;
- acumulação de funções;
- separação entre responsabilidades estruturais e particularidades institucionais.

Nenhuma estratégia técnica é definida aqui.

## Fase 5 — Produto, Escopo e Roadmap

Deverá avaliar:

- extensão da comunicação direta com estudantes e responsáveis;
- eventual substituição do ClassApp;
- entrada da capacidade socioemocional no primeiro ciclo;
- priorização dos processos do piloto.

## Fase 6 — Engenharia de Requisitos

Somente após validações anteriores deverão ser definidos requisitos de:

- comportamento;
- segurança;
- privacidade;
- auditoria;
- rastreabilidade;
- retenção;
- autorização;
- acessibilidade;
- notificações;
- demais requisitos necessários.

## Fase 7 — UX/UI

Somente então deverão ser avaliados:

- emojis;
- escalas;
- controles rápidos;
- fluxos;
- estados;
- visualização de histórico;
- comunicação visual;
- acessibilidade;
- experiência de professores, estudantes, responsáveis e equipes especializadas.

---

# 18. Decisões consolidadas

## 18.1 VALIDADO

- Colégio Victorino é fonte de evidência local, não modelo organizacional universal.
- Gestão Institucional/Mantença é stakeholder e autoridade institucional relevante.
- Direção Pedagógica é autoridade de validação pedagógica.
- Coordenação Pedagógica é stakeholder e usuário direto.
- Docentes são stakeholders, usuários diretos e especialistas na rotina docente.
- Secretaria Escolar é setor distinto da Secretária da Coordenação.
- Secretária da Coordenação é função própria de apoio.
- Coordenação de Tecnologia Educacional é stakeholder-chave, usuário operacional e responsável pela administração operacional do Kademis no piloto.
- Psicopedagogia é stakeholder, usuário direto e autoridade especializada.
- Atuação socioemocional é stakeholder, usuário direto e autoridade especializada.
- Uma pessoa pode exercer múltiplas funções.
- Estudantes são stakeholders internos e usuários diretos, sem autoridade formal de governança do Kademis.
- Pais e responsáveis são stakeholders externos e usuários diretos.
- ANPD é regulador externo.
- Comunicação escola–família é relação de negócio relevante.
- Integração com ClassApp não faz parte da direção de escopo pretendida.
- Parte da intermediação atual da Secretária da Coordenação decorre da transferência manual entre papel e plataforma.
- O Kademis deve evitar preservar intermediações sem necessidade real.
- Autoria, origem e contexto devem ser preservados.
- Acompanhamento contextual/psicopedagógico/socioemocional deve prosseguir em descoberta.
- Acompanhamento socioemocional não terá finalidade diagnóstica.
- Emojis não definem o conceito de domínio.

## 18.2 PROPOSTO

- Kademis substituir futuramente o ClassApp como solução de comunicação escola–estudante–família, sujeito à Fase 5.
- Uso de emojis ou controles visuais rápidos, sujeito à Fase 7.
- RACI de acompanhamento contextual como base para refinamento na Fase 3.
- INEP e autoridades educacionais competentes como stakeholders externos dependentes dos processos efetivamente contemplados.

## 18.3 PENDENTE

- autoridade institucional especializada final sobre vida escolar/documentação;
- autoridade interna ou contratada de validação jurídica/privacidade;
- semântica e processo detalhado das observações contextuais;
- responsabilidades da Secretária da Coordenação após digitalização;
- escopo definitivo de substituição do ClassApp;
- tratamento detalhado dos dados socioemocionais.

## 18.4 BLOQUEANTE

Nenhum item bloqueante identificado.

---

# 19. Checklist técnico da Fase 2

- [x] stakeholder ≠ usuário;
- [x] usuário ≠ role técnica;
- [x] autoridades de domínio identificadas em nível suficiente para o Gate;
- [x] conflitos registrados;
- [x] pendências explicitadas;
- [x] stakeholders internos identificados;
- [x] stakeholders externos relevantes identificados;
- [x] usuários diretos identificados;
- [x] responsabilidades de negócio registradas;
- [x] múltiplas funções humanas consideradas;
- [x] Secretaria Escolar ≠ Secretária da Coordenação;
- [x] particularidades do Victorino não transformadas em regra universal;
- [x] SGSA - Old utilizado somente como histórico;
- [x] nenhuma role técnica criada;
- [x] nenhum RBAC criado;
- [x] nenhum banco, API, módulo ou arquitetura definido;
- [x] descoberta socioemocional preservada sem antecipar UX/implementação;
- [x] dependência atual do ClassApp registrada sem antecipar integração;
- [x] riscos da Fase 2 registrados;
- [x] não há pendência bloqueante conhecida.

---

# 20. Checklist de validação humana

O responsável pelo projeto validou:

- [x] as pessoas e grupos que influenciam o produto estão representados;
- [x] os usuários operacionais identificados estão corretos;
- [x] quem decide e valida regras pedagógicas está representado em nível suficiente para esta fase;
- [x] quem atua nas responsabilidades administrativas está representado em nível suficiente para esta fase;
- [x] a autoridade final sobre regras específicas de vida escolar/documentação pode permanecer como pendência não bloqueante até a descoberta dos processos;
- [x] não foi identificada autoridade crítica ausente que bloqueie a fase;
- [x] as responsabilidades estão adequadas ao nível de abstração da Fase 2;
- [x] os conflitos conhecidos estão representados;
- [x] nenhum stakeholder foi convertido em role técnica;
- [x] o modelo representa a realidade do Colégio Victorino sem transformá-la automaticamente em regra universal do Kademis;
- [x] a descoberta de acompanhamento contextual/psicopedagógico/socioemocional está corretamente registrada;
- [x] a posição sobre ClassApp está correta: integração não pretendida e substituição sujeita à decisão de produto na Fase 5.

---

# 21. Gate 2

O critério do Master Development Playbook v1.0 é:

> **Gate 2 aprovado quando decisões de negócio puderem ser encaminhadas à autoridade correta.**

Resultado:

- principais stakeholders mapeados;
- usuários diretos identificados;
- autoridades especializadas relevantes identificadas;
- lacunas de autoridade explicitadas;
- responsabilidades separadas de permissões;
- conflitos e dependências registrados;
- nenhuma estrutura técnica prematura criada;
- nenhuma pendência bloqueante conhecida.

O responsável pelo projeto aprovou formalmente o Gate 2 em 20/09/2026.

> **Gate 2 — APROVADO**

A **Fase 2 — Negócio e Stakeholders está concluída em conteúdo**.

A Fase 3 — Descoberta do Domínio não deve ser iniciada neste chat. Seu início dependerá de integração validada dos artefatos da Fase 2, handoff, novo chat, reconstrução do estado oficial e autorização explícita do responsável pelo projeto.

---

# 22. Limites após o Gate 2

A aprovação do Gate 2 não aprova ou define:

- roles técnicas;
- RBAC;
- permissões técnicas;
- arquitetura;
- stack;
- banco de dados;
- APIs;
- módulos;
- menus;
- navegação;
- telas;
- componentes de interface;
- estratégia física de multi-tenancy;
- emojis como solução de UX;
- substituição do ClassApp como requisito funcional.

Essas decisões pertencem às fases posteriores do Master Development Playbook.

---

# 23. Artefatos relacionados

- `docs/playbook/Kademis_Master_Development_Playbook_v1.0.md` — APROVADO — BASELINE METODOLÓGICO;
- `docs/governance/Kademis_Governanca_v1.0.md` — APROVADO — BASELINE DE GOVERNANÇA;
- `docs/product/Kademis_Product_Charter_v0.1.md` — APROVADO — BASELINE ESTRATÉGICO DA FASE 1;
- `andrecnk5/sgsa` — HISTÓRICO / evidência.
