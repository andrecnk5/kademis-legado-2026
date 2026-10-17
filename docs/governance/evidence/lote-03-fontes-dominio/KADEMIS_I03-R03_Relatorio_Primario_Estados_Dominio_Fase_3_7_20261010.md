# KADEMIS — I03-R03
## Relatório Primário — Recuperação Integral dos Estados de Domínio da Fase 3.7

**Frente:** PSD-I03 — Organização e Proveniência dos Catálogos de Domínio  
**Atividade:** I03-R03  
**Modo:** somente leitura  
**Fonte primária:** histórico original do chat `Fase 3.7 Estados`  
**Fontes secundárias de cotejo:** RDOC-04; CCD-02/REC-3.8-02; índice PSD-I02 vigente na `main`; contrato I03-R03  
**Estado de saída:** `I03-R03 — RECUPERAÇÃO PRIMÁRIA EXECUTADA; AGUARDANDO VALIDAÇÃO/RECONCILIAÇÃO PELA PSD-I03`  
**Gate 3:** NÃO AVALIADO  
**Fase 4:** NÃO INICIADA  
**Mutações externas:** nenhuma

---

## 1. Resumo executivo

A I03-R03 percorreu a sequência documental da Fase 3.7 e recuperou **34 identificadores concretos `EST-*`**, distribuídos por **15 famílias/entidades de domínio**. Não foram completados intervalos por sequência numérica e não foram contados padrões genéricos ou exemplos rejeitados sem número concreto.

A auditoria encontrou:

- **34/34 IDs com existência e cadeia decisória primária recuperadas**;
- **12 IDs com situação decisória final APROVADA**;
- **22 IDs com situação decisória final VALIDADA**, sendo `EST-PERAV-01/02` estados validados cuja **nomenclatura canônica final** foi posteriormente aprovada como `Unidade Avaliativa`;
- **1 estado de aplicabilidade condicionada**, `EST-MATAC-04 — Suspensa`, que não é universal e depende de fundamento jurídico/regimental;
- **25 registros de transição documentada** na matriz específica, equivalentes a **22 arestas estado→estado únicas**, porque `EST-MATAC-01 → EST-MATAC-02` foi documentada com mais de uma condição/ato;
- nenhuma evidência de renumeração ou reutilização de `EST-*`;
- um refinamento nomenclatural relevante sem troca de ID: `Período Avaliativo` → `Unidade Avaliativa` para `EST-PERAV-01/02`.

A recuperação confirma que a Fase 3.7 trabalhou deliberadamente para **reduzir estados artificiais**. Diversas formas como `Aluno Ativo/Inativo`, `Transferida`, `Reativada`, `Aprovada`, `Reprovada`, `Graduada`, `Emitido`, `Retificado`, `Entregue`, `Reaberto` e equivalentes foram tratadas como outros conceitos, exemplos rejeitados ou eventos/desfechos, e não como estados catalogados.

---

## 2. Fontes e precedência probatória

### 2.1 Fonte primária

O histórico original do chat `Fase 3.7 Estados` foi usado como fonte de verdade para:

- nascimento de cada ID;
- enunciado/semântica original;
- respostas humanas subsequentes;
- refinamentos;
- transições;
- ressalvas;
- encerramento da 3.7.

A localização é registrada por **Lote/Parte/subseção e ordem relativa**, porque o corpus primário disponível não fornece timestamp forense individual para cada mensagem. A data contextual da Fase 3.7 é 08/10/2026, conforme documentação focal anterior; horários não foram inventados.

### 2.2 Fontes secundárias de cotejo

**RDOC-04** foi utilizado somente para cotejar `EST-DOCREQ-01/02`, `EST-SOLDOC-01/02`, `EVT-DOC-08` e `P3.7-PEN-DOC-02`. O RDOC-04 já comprova focalmente esses itens e não foi tratado como substituto da fonte primária.

**CCD-02 / REC-3.8-02** foi usado somente para confirmar a preservação posterior da condição jurídica/regimental de `EST-MATAC-04 — Suspensa`; não foi usado para originar o estado.

**PSD-I02 vigente na `main`** foi consultado somente para o estado atual de proveniência e pendências Pré-Gate 3.

---

## 3. Inventário bruto cronológico reconstruído

### 3.1 Lote 1 — Matrícula e trajetória

**Parte B:** surgem `EST-MATAC-01`, `EST-MATAC-02` e a proposta `EST-MATAC-03`. A manifestação humana subsequente foi:

> “Aceito as suas sugestões e aprovo a prática dos SGSAs maduros como modelo para o KADEMIS nesses quesitos”

O bloco consolida `Vigente`, `Encerrada` e `Futura` para Matrícula Acadêmica.

**Parte C:** surgem `EST-ENT-01` e `EST-ENT-02`. A manifestação humana subsequente repetiu aprovação das sugestões e da prática comparativa. Enturmação anterior é preservada historicamente e mudança de turma não recria automaticamente a Matrícula Acadêmica.

**Parte D:** não cria novos IDs; elimina estados artificiais como status global de aluno, “Reativada” e outros.

### 3.2 Lote 2 — Estrutura/Ciclo e vínculos

São propostos:

- `EST-ANO-01..03`;
- `EST-OFE-01..03`;
- `EST-VDO-01..02`;
- `EST-RESP-01..02`.

Manifestação humana:

> “Todas validadas”

Não foram criados estados para Calendário ou Turma.

### 3.3 Lote 3 — Execução pedagógica e avaliação

**Parte A:** `EST-AULA-01/02` e `EST-PERAV-01/02`.  
Manifestação humana: “Todas validadas.”

**Parte B:** `EST-INSTAV-01/02` e `EST-RECON-01/02`.  
Manifestação humana: “Todas validadas”.

Não foram criados estados para Registro de Aula, Registro de Frequência, Resultado Avaliativo, Síntese Avaliativa, Recuperação, Resultado Final ou Decisão Acadêmica.

### 3.4 Lote 4 — Documentação, comunicação e proteção

**Parte A:** `EST-DOCREQ-01/02` e `EST-SOLDOC-01/02`.  
Manifestação humana: “Todas validadas.”

O RDOC-04 posterior confirma integralmente os enunciados literais desses quatro estados e a separação entre Solicitação de Documento e Documento Escolar.

**Parte B:** `EST-PROT-01/02`.  
Manifestação humana: “Aprovado”.

Não foram criados estados para Ocorrência, Observação Contextual, Orientação Psicopedagógica, Orientação Socioemocional, Emissão ou Comunicação.

### 3.5 Auditoria transversal da 3.7

A auditoria transversal identifica lacuna para **Atuação Institucional** e propõe:

- `EST-ATUINST-01 — Vigente`;
- `EST-ATUINST-02 — Encerrada`.

Também identifica a ambiguidade `Unidade Avaliativa × Período Avaliativo`. Na rodada seguinte, a recomendação é usar **Unidade Avaliativa como conceito acadêmico canônico**, preservando os IDs `EST-PERAV-01/02`.

A manifestação humana:

> “Adoro suas sugestões, aprovado, siga”

aprova essa direção, além das complementações eventuais `EVT-DOC-08` e `EVT-PROT-04`, sem publicação externa.

### 3.6 Rodada final de melhores práticas das pendências

Na resposta às perguntas 1–8, são aprovados:

- `EST-MATAC-04 — Suspensa`, com aplicabilidade condicionada;
- `EST-JUST-01 — Pendente de decisão`;
- `EST-JUST-02 — Decidida`.

Manifestação humana:

> “Li e aprovo a suas sugestões. Siga”

O fechamento subsequente consolida o inventário em **34 estados**, sendo 33 ordinários e 1 condicional (`EST-MATAC-04`).

---

## 4. Contagens verificadas

### 4.1 Por família

| Família/entidade | Quantidade |
|---|---:|
| Ano Letivo | 3 |
| Atuação Institucional | 2 |
| Aula | 2 |
| Documento Escolar | 2 |
| Enturmação | 2 |
| Instrumento Avaliativo | 2 |
| Justificativa | 2 |
| Matrícula Acadêmica | 4 |
| Oferta de Componente | 3 |
| Pedido de Reconsideração | 2 |
| Situação Protetiva | 2 |
| Solicitação de Documento | 2 |
| Unidade Avaliativa | 2 |
| Vínculo Docente–Oferta | 2 |
| Vínculo Estudante–Responsável | 2 |

**Total:** **34** IDs concretos e únicos.

### 4.2 Por situação decisória

- **APROVADO:** 12 IDs.
- **VALIDADO:** 22 IDs.
- `EST-PERAV-01/02`: existência dos estados VALIDADA; refinamento nomenclatural final para `Unidade Avaliativa` APROVADO.

### 4.3 Por situação documental

- **COMPROVADO:** 34 IDs.
- **PARCIALMENTE COMPROVADO:** 0 IDs no inventário de identificação/decisão.
- **NÃO COMPROVADO:** 0 IDs concretos recuperados.

Essa classificação não significa que toda condição operacional, autoridade ou fundamento jurídico esteja comprovado. As ressalvas estão registradas por ID, especialmente em `EST-MATAC-04`, `EST-SOLDOC-*` e `EST-JUST-*`.

---

## 5. Refinamentos e alterações históricas

### 5.1 `EST-PERAV-01/02`

**Original:** estados de **Período Avaliativo**:

- `EST-PERAV-01 — Aberto`
- `EST-PERAV-02 — Fechado`

**Refinamento aprovado:** `Unidade Avaliativa` tornou-se o conceito acadêmico canônico. Os IDs históricos foram preservados:

- `EST-PERAV-01 — Unidade Avaliativa Aberta`
- `EST-PERAV-02 — Unidade Avaliativa Fechada`

Não houve renumeração.

### 5.2 `EST-MATAC-04`

O estado apareceu tardiamente, na rodada final da 3.7. Sua aprovação foi expressamente **condicionada**:

> somente onde houver base jurídica/regimental para uma suspensão temporária e reversível da Matrícula Acadêmica.

A própria continuidade em CCD-02/REC-3.8-02 preservou a proibição de criar evento universal de suspensão/trancamento sem essa confirmação.

### 5.3 `EST-SOLDOC-*`

Os estados foram validados na Parte A. Posteriormente foi aprovada a orientação de que **validação não é obrigatória para todo tipo documental**. Isso não elimina `EST-SOLDOC-02`; limita sua aplicabilidade ao fluxo/documento em que validação institucional seja realmente exigida.

`P3.7-PEN-DOC-02` permanece ABERTA — NÃO BLOQUEANTE porque o Victorino não teve seus procedimentos por tipo documental comprovados.

### 5.4 `EST-JUST-*`

Os estados foram aprovados com condição explícita:

> aplicar o lifecycle `Pendente de decisão → Decidida` apenas quando a justificativa exigir decisão humana/institucional formal.

`Aceita` e `Não aceita` permanecem desfechos, não estados.

---

## 6. Transições documentadas

A matriz separada contém **25 registros** de transição documentada. Eles correspondem a **22 pares estado→estado únicos**.

As transições com evento correlato explicitamente sustentado incluem:

- `EST-ENT-01 → EST-ENT-02` — `EVT-TRAJ-04 — Enturmação Alterada`;
- `EST-MATAC-01 → EST-MATAC-02` por transferência — `EVT-TRAJ-06`;
- `EST-VDO-01 → EST-VDO-02` — `EVT-CICLO-10`;
- `EST-RESP-01 → EST-RESP-02` — `EVT-RESP-02`;
- `EST-AULA-01 → EST-AULA-02` — `EVT-EXEC-01`;
- `EST-PERAV-01 ↔ EST-PERAV-02` — `EVT-AVAL-06/07`;
- `EST-INSTAV-01 → EST-INSTAV-02` — `EVT-AVAL-01`;
- `EST-RECON-01 → EST-RECON-02` — `EVT-AVAL-10`;
- `EST-DOCREQ-01 → EST-DOCREQ-02` — `EVT-DOC-08`, originado na 3.7;
- `EST-SOLDOC-01 → EST-SOLDOC-02` — `EVT-DOC-03`;
- `EST-PROT-01 → EST-PROT-02` — `EVT-PROT-04`, aprovado na 3.7;
- `EST-JUST-01 → EST-JUST-02` — `EVT-EXEC-10`, aprovado na 3.7.

Transições de Ano Letivo, Oferta e Atuação Institucional foram conceitualmente documentadas sem evento `EVT-*` específico comprovado para cada aresta. Nenhum evento foi inventado.

---

## 7. Transições e estados deliberadamente não inferidos

A 3.7 contém decisões negativas relevantes:

- uma Matrícula Acadêmica validamente `Encerrada` **não** volta simplesmente a `Vigente` por edição; retorno posterior deve preservar a saída anterior;
- `Reativada` não foi adotado como estado;
- `Transferida` não foi adotado como estado estrutural da Matrícula Acadêmica;
- `Aprovada`, `Reprovada`, `Graduada` e `Em DP` não foram adotados como estados da Matrícula Acadêmica;
- `Reaberto` não foi adotado como estado da Unidade Avaliativa;
- `Emitido` e `Retificado` não foram adotados como estados do Documento Escolar;
- `Entregue` não foi adotado como estado global de Comunicação;
- `Ocorrência Resolvida` não foi criada como estado genérico;
- `Aluno Ativo/Inativo` não foi criado como estado central.

Padrões exemplificativos sem número concreto não integram a contagem de 34.

---

## 8. Conferências obrigatórias do contrato

### 8.1 Solicitação de Documento

Comprovação primária e RDOC-04 convergem:

- `EST-DOCREQ-01 — Em aberto`: solicitação recebida cujo tratamento ainda não terminou;
- `EST-DOCREQ-02 — Encerrada`: tratamento terminado, desfecho separado;
- `EVT-DOC-08`: encerramento da Solicitação de Documento, originado na Fase 3.7 e aprovado para reconciliação da 3.6.

Não foi inferida equivalência com emissão, entrega ou recebimento.

### 8.2 Documento Escolar

Comprovado:

- `EST-SOLDOC-01 — Constituído` ≠ `EST-SOLDOC-02 — Validado`;
- `EVT-DOC-04 — Documento Escolar Emitido` permanece evento;
- `EVT-DOC-06 — Documento Escolar Retificado` permanece evento;
- emissão ≠ entrega ≠ recebimento;
- segunda via não cria novo fato escolar.

A obrigatoriedade de validação por **tipo documental no Victorino** não está comprovada.

### 8.3 `EST-MATAC-04 — Suspensa`

Comprovado primariamente e preservado depois em REC-3.8-02:

- existe como estado aprovado;
- possui aplicabilidade condicionada;
- não autoriza evento universal de trancamento/suspensão;
- não universaliza práticas do Victorino.

### 8.4 `P3.7-PEN-DOC-02`

Formulação recuperada pelo RDOC-04:

> **`P3.7-PEN-DOC-02 — PENDENTE — NÃO BLOQUEANTE`**  
> “Confirmar, por tipo documental, quando o Victorino exige conferência/validação antes da emissão.”

A pendência continua **ABERTA — NÃO BLOQUEANTE**. A validação conceitual de `EST-SOLDOC-*` não substitui evidência operacional local.

---

## 9. Cotejo com PSD-I02 vigente na `main`

A leitura read-only da `main` em 10/10/2026 confirma que o índice de proveniência atual registra:

- **16 identificadores formais totais**;
- **14 ABERTOS**;
- **2 ENCERRAMENTOS FORMALMENTE DELIBERADOS**: `P3.4-PEN-DOC-01` e `REC-3.8-06`;
- `P3.7-PEN-DOC-02` ABERTO / não bloqueante;
- `REC-3.8-02` ABERTO.

O HEAD observado na verificação é posterior ao PR #10 e inclui o commit `9465ebe3be67db53e8dd5af766597ec381f7f85e` (“docs: record CCD-03 deliberated closures in provenance index”).

### 9.1 Divergência documental atual observada

O **índice PSD-I02** registra corretamente `14 abertos + 2 encerramentos deliberados`, enquanto o `README.md` atual ainda contém a frase “16 identificadores formais ainda abertos”.

Classificação nesta I03-R03:

**DIVERGÊNCIA DOCUMENTAL OBSERVADA — FORA DO ESCOPO DE ESCRITA DESTE CONTRATO.**

Nenhuma correção foi executada.

---

## 10. Limites de suficiência

A I03-R03 comprova integralmente o inventário de IDs concretos recuperados da Fase 3.7 e suas cadeias de validação/aprovação.

Isso **não** significa:

- publicação de catálogo oficial;
- validação jurídica de `EST-MATAC-04` para todas as instituições;
- comprovação operacional do Victorino em `P3.7-PEN-DOC-02`;
- definição técnica de máquina de estados;
- criação de enums, tabelas, APIs ou eventos técnicos;
- encerramento de `REC-3.8-02`;
- avaliação do Gate 3.

---

## 11. Parecer de suficiência documental

**PARECER:** **I03-R03 EXECUTADA QUANTO À AUDITORIA INVENTARIAL.**

A fonte primária permitiu recuperar e individualizar **34/34 IDs concretos `EST-*` localizados**, com:

- família/entidade;
- enunciado original;
- enunciado final;
- semântica;
- localização relativa;
- manifestação humana;
- situação documental;
- situação decisória;
- transições documentadas;
- eventos/relações correlatas;
- refinamentos e limites.

Nenhum intervalo foi completado por inferência.

A publicação canônica de catálogo continua dependente de validação/reconciliação pela PSD-I03 e de autorização independente.

---

## 12. Checklist técnico

- [x] Histórico original da Fase 3.7 examinado em ordem lógica/lotes.
- [x] IDs concretos `EST-*` deduplicados.
- [x] 34 IDs individualizados.
- [x] Enunciado original/final registrado.
- [x] Autoria e localização relativa registradas.
- [x] Manifestação humana classificada.
- [x] 25 registros de transição documentada separados de inferências.
- [x] Estados/eventos/desfechos separados.
- [x] `EST-DOCREQ-*` auditados.
- [x] `EST-SOLDOC-*` auditados.
- [x] `EST-MATAC-04` auditado com condicionante.
- [x] `EVT-DOC-08` tratado como evento originado na 3.7.
- [x] `P3.7-PEN-DOC-02` preservada ABERTA — NÃO BLOQUEANTE.
- [x] Pseudo-identificadores/rejeições excluídos da contagem.
- [x] PSD-I02 atual cotejado em leitura.
- [x] Nenhuma mutação externa realizada.
- [x] Gate 3 não avaliado.
- [x] Fase 4 não iniciada.

---

## 13. Estado de saída

**I03-R03 — RECUPERAÇÃO PRIMÁRIA EXECUTADA; AGUARDANDO VALIDAÇÃO/RECONCILIAÇÃO PELA PSD-I03.**

**Contagem recuperada:** 34 IDs concretos `EST-*`.  
**Situação formal Pré-Gate 3 vigente:** 14 pendências/identificadores formais ABERTOS + 2 encerramentos formalmente deliberados.  
**Gate 3:** NÃO AVALIADO.  
**Fase 4:** NÃO INICIADA.  
**GitHub/Figma/outros artefatos:** nenhuma mutação por esta atividade.
