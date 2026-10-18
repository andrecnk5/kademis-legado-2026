# KADEMIS — PSD-I03 / I03-R02
## Relatório Primário Integral de Eventos de Domínio — Fase 3.6

**Atividade:** I03-R02 — Recuperação Primária Integral de Eventos de Domínio  
**Modo:** somente leitura  
**Resultado:** recuperação primária integral executada; pronta para validação/reconciliação Pré-Gate 3

---

# 1. Escopo

Recuperar diretamente do histórico original da Fase 3.6:

1. todos os `EVT-*` da Etapa 1;
2. o alcance da validação da Etapa 1;
3. os ajustes da Etapa 2;
4. a manifestação humana de encerramento;
5. dependências posteriores estritamente necessárias, preservando fase de origem.

Não constitui nova descoberta, não altera IDs e não consolida baseline oficial.

# 2. Fontes primárias recuperadas

## 2.1 Etapa 1 — Critério e inventário inicial

A mensagem original definiu evento de negócio como fato relevante já ocorrido no domínio e distinguiu comando/intenção, processo, evento, estado e regra.

Também declarou que `EVT-*` não implica filas, Kafka, webhooks, event sourcing, microserviços ou arquitetura orientada a eventos.

O relatório intermediário referencia essa mensagem em **06/10/2026 23:57:46Z**. Esse horário é mantido como metadado secundário corroborador; a comprovação textual decorre do corpo primário recuperado nesta conversa.

## 2.2 Validação humana da Etapa 1

Manifestação do responsável:

> **“Validado, aiga”**

A mensagem subsequente registrou:

> **“A primeira etapa da 3.6 fica VALIDADA.”**

O relatório intermediário referencia a manifestação em **07/10/2026 00:11:55Z**.

## 2.3 Etapa 2 — Granularidade, causalidade e cobertura

A Etapa 2:

- adicionou `EVT-CICLO-09..10`;
- adicionou `EVT-TRAJ-12`;
- adicionou `EVT-RESP-01..02`;
- absorveu `EVT-EXEC-04` por `EVT-EXEC-02`;
- absorveu `EVT-DOC-05` por `EVT-DOC-04`;
- refinou `EVT-CONS-02`;
- classificou `EVT-CICLO-01` como marco derivado;
- reafirmou que sequência de eventos não implica causalidade automática.

## 2.4 Encerramento humano

A resposta humana imediatamente posterior declarou:

> **“Fase Concluida. Vamos iniciar a fase 3.7 em um novo chat...”**

Como a Etapa 2 condicionava o encerramento da 3.6 à validação desses ajustes, a declaração sustenta **VALIDAÇÃO EM BLOCO do resultado da Etapa 2** e o encerramento conceitual da Fase 3.6.

Não é convertida em `APROVADO` individual por inferência.

# 3. Inventário integral da Etapa 1

Total confirmado: **60 identificadores**.

| ID | Enunciado original |
|---|---|
| `EVT-CICLO-01` | Ano Letivo Preparado |
| `EVT-CICLO-02` | Calendário Acadêmico Definido |
| `EVT-CICLO-03` | Calendário Acadêmico Alterado |
| `EVT-CICLO-04` | Oferta Curricular Definida |
| `EVT-CICLO-05` | Oferta Curricular Alterada |
| `EVT-CICLO-06` | Turma Constituída |
| `EVT-CICLO-07` | Organização de Turma Alterada |
| `EVT-CICLO-08` | Horário Acadêmico Definido ou Alterado |
| `EVT-TRAJ-01` | Matrícula Institucional Estabelecida |
| `EVT-TRAJ-02` | Matrícula Acadêmica Estabelecida |
| `EVT-TRAJ-03` | Enturmação Efetivada |
| `EVT-TRAJ-04` | Enturmação Alterada |
| `EVT-TRAJ-05` | Trajetória Acadêmica Externa Incorporada |
| `EVT-TRAJ-06` | Transferência de Saída Efetivada |
| `EVT-TRAJ-07` | Vínculo Acadêmico Reativado |
| `EVT-TRAJ-08` | Classificação Decidida |
| `EVT-TRAJ-09` | Reclassificação Decidida |
| `EVT-TRAJ-10` | Estudos Anteriores Reconhecidos |
| `EVT-TRAJ-11` | Trajetória Acadêmica Concluída |
| `EVT-EXEC-01` | Aula Realizada |
| `EVT-EXEC-02` | Registro de Aula Efetuado |
| `EVT-EXEC-03` | Registro de Aula Retificado |
| `EVT-EXEC-04` | Conteúdo Ministrado Registrado |
| `EVT-EXEC-05` | Frequência Registrada |
| `EVT-EXEC-06` | Frequência Retificada |
| `EVT-EXEC-07` | Justificativa de Ausência Recebida |
| `EVT-EXEC-08` | Documento Comprobatório Recebido |
| `EVT-EXEC-09` | Regularização ou Compensação de Frequência Reconhecida |
| `EVT-AVAL-01` | Instrumento Avaliativo Aplicado |
| `EVT-AVAL-02` | Resultado Avaliativo Registrado |
| `EVT-AVAL-03` | Resultado Avaliativo Retificado |
| `EVT-AVAL-04` | Recuperação Realizada |
| `EVT-AVAL-05` | Síntese Avaliativa Consolidada |
| `EVT-AVAL-06` | Período Avaliativo Fechado |
| `EVT-AVAL-07` | Período Avaliativo Reaberto |
| `EVT-CONS-01` | Sessão de Conselho de Classe Realizada |
| `EVT-CONS-02` | Decisão Acadêmica Tomada |
| `EVT-AVAL-08` | Resultado Final Consolidado |
| `EVT-AVAL-09` | Pedido de Reconsideração Apresentado |
| `EVT-AVAL-10` | Reconsideração Decidida |
| `EVT-DOC-01` | Solicitação Documental Recebida |
| `EVT-DOC-02` | Documento Escolar Constituído |
| `EVT-DOC-03` | Documento Escolar Validado |
| `EVT-DOC-04` | Documento Escolar Emitido |
| `EVT-DOC-05` | Segunda Via Emitida |
| `EVT-DOC-06` | Documento Escolar Retificado |
| `EVT-DOC-07` | Documento Externo Incorporado à Vida Escolar |
| `EVT-COM-01` | Comunicação Institucional Emitida |
| `EVT-COM-02` | Comunicação Entregue ao Destinatário |
| `EVT-COM-03` | Ciência do Destinatário Registrada |
| `EVT-COM-04` | Manifestação do Destinatário Recebida |
| `EVT-OCO-01` | Ocorrência Registrada |
| `EVT-OCO-02` | Ocorrência Retificada |
| `EVT-OBS-01` | Observação Contextual Registrada |
| `EVT-OBS-02` | Observação Contextual Retificada |
| `EVT-PSI-01` | Orientação Psicopedagógica Realizada |
| `EVT-SOC-01` | Aconselhamento Socioemocional Realizado |
| `EVT-PROT-01` | Situação Protetiva Identificada |
| `EVT-PROT-02` | Providência Protetiva Adotada |
| `EVT-PROT-03` | Rede Externa de Proteção Acionada |

# 4. Adições da Etapa 2

Cinco identificadores foram adicionados e incorporados ao fechamento:

- `EVT-CICLO-09` — **Vínculo Docente com Oferta Estabelecido**
- `EVT-CICLO-10` — **Vínculo Docente com Oferta Encerrado**
- `EVT-TRAJ-12` — **Transferência de Entrada Efetivada**
- `EVT-RESP-01` — **Vínculo Estudante–Responsável Reconhecido**
- `EVT-RESP-02` — **Vínculo Estudante–Responsável Encerrado**

# 5. Absorções comprovadas

## 5.1 `EVT-EXEC-04 → EVT-EXEC-02`

Fonte primária:

> **`EVT-EXEC-04 — Conteúdo Ministrado Registrado` — ABSORVIDO por `EVT-EXEC-02 — Registro de Aula Efetuado`.**

Justificativa:

> “O Conteúdo Ministrado continua sendo objeto/conceito de domínio validado, mas seu registro não precisa obrigatoriamente gerar evento independente toda vez que o Registro de Aula for produzido.”

Decisão adicional:

> **“O ID `EVT-EXEC-04` não será reutilizado.”**

Natureza: **ABSORÇÃO**, sem apagar o conceito Conteúdo Ministrado e sem excluir o ID histórico.

## 5.2 `EVT-DOC-05 → EVT-DOC-04`

Fonte primária:

> **`EVT-DOC-05 — Segunda Via Emitida` — ABSORVIDO por `EVT-DOC-04 — Documento Escolar Emitido`.**

Justificativa:

> “A segunda via é uma nova Emissão Documental, mas não exige um tipo diferente de evento.”

Decisão adicional:

> **“O ID `EVT-DOC-05` também fica reservado e não reutilizado.”**

Natureza: **ABSORÇÃO**, preservando a natureza/contexto da reemissão.

# 6. Refinamento comprovado de `EVT-CONS-02`

Enunciado original:

> **`EVT-CONS-02 — Decisão Acadêmica Tomada`**

Problema registrado:

> “é amplo demais, porque Decisão Acadêmica também existe fora do Conselho.”

Enunciado refinado:

> **`EVT-CONS-02 — Decisão ou Encaminhamento do Conselho Registrado`**

Natureza: **REFINAMENTO**. O mesmo ID foi preservado; não houve absorção.

# 7. `EVT-CICLO-01` como marco derivado

`EVT-CICLO-01 — Ano Letivo Preparado` foi mantido, porém classificado como:

> **EVENTO/MARCO DERIVADO DE NEGÓCIO**

e não como evento necessariamente elementar.

# 8. Resultado quantitativo consolidado

- Etapa 1: **60 IDs**
- Etapa 2: **5 novos IDs**
- Total originado na Fase 3.6: **65 IDs**
- Ativos/retidos no fechamento: **63**
- Históricos absorvidos: **2**
- Refinado mantendo identidade: **1 (`EVT-CONS-02`)**

Importante:

> **65 é a contagem de identificadores originados na Fase 3.6, não de eventos ativos após as absorções.**

# 9. `EVT-DOC-08` — origem posterior

`EVT-DOC-08 — Solicitação de Documento Encerrada` não pertence ao inventário de origem da Fase 3.6.

Sua origem é a **Fase 3.7**. Ele pode aparecer em reconciliação transversal posterior, mas não aumenta a contagem originária de 65 para 66.

# 10. Compatibilidade com Fases 3.4 e 3.5

As decisões recuperadas respeitam:

- regras `RD-EXEC-*`, `RD-DOC-*`, `RD-CONS-*` e `RD-CTX-*`;
- preservação de histórico e contexto;
- distinção entre fato, registro e autoria;
- `INV-110` para reemissão documental.

Não foi encontrado conflito que exija reabrir regras ou invariantes.

# 11. Divergências com consolidações secundárias

- As duas absorções descritas em RDOC-03 são confirmadas pela fonte primária.
- `EVT-CONS-02` é refinamento, não absorção.
- `EVT-DOC-08` tem origem em 3.7 e não deve ser retroatribuído à 3.6.
- A contagem integral, antes indisponível no relatório intermediário, é agora comprovada: **65 IDs originados na Fase 3.6**.

# 12. Situação documental

### Etapa 1

- 60/60 identificadores: **COMPROVADOS** quanto à existência e enunciado.
- decisão: **VALIDADOS EM BLOCO**.

### Etapa 2

- 5 adições: **COMPROVADAS / VALIDADO EM BLOCO**.
- 2 absorções: **COMPROVADAS / VALIDADO EM BLOCO**.
- 1 refinamento: **COMPROVADO / VALIDADO EM BLOCO**.
- marco derivado `EVT-CICLO-01`: **COMPROVADO**.

Nenhum item é promovido individualmente a `APROVADO` por inferência.

# 13. Parecer de suficiência

**SUFICIENTE para a I03-R02 quanto à recuperação primária integral dos eventos originados na Fase 3.6.**

A limitação do relatório intermediário — ausência do inventário integral primário — está superada por esta execução.

Isso não torna o catálogo automaticamente baseline oficial e não encerra identificadores Pré-Gate 3.

# 14. Pendências preservadas

Esta execução não encerra:

- `P3.4-PEN-DOC-01`;
- identificadores formais Pré-Gate 3;
- reconciliações posteriores da Fase 3.8;
- pendências da Fase 3.10;
- Gate 3.

# 15. Checklist técnico

- [x] Etapa 1 recuperada integralmente.
- [x] 60 IDs iniciais conferidos.
- [x] Validação humana da Etapa 1 confrontada.
- [x] Etapa 2 recuperada integralmente.
- [x] 5 novos IDs recuperados.
- [x] Duas absorções comprovadas.
- [x] `EVT-CONS-02` comprovado como refinamento.
- [x] IDs absorvidos preservados e não reutilizáveis.
- [x] `EVT-CICLO-01` classificado como marco derivado.
- [x] `EVT-DOC-08` separado por origem em 3.7.
- [x] Nenhum evento criado nesta auditoria.
- [x] Nenhum ID renumerado.
- [x] Nenhuma aprovação retroativa atribuída.
- [x] GitHub/Figma não alterados.
- [x] Gate 3 não avaliado.
- [x] Fase 4 não iniciada.

# 16. Estado recomendado para PSD-I03

| Controle | Estado após esta execução |
|---|---|
| I03-R02 — Eventos | **RECUPERAÇÃO PRIMÁRIA INTEGRAL EXECUTADA — AGUARDANDO VALIDAÇÃO/RECONCILIAÇÃO** |
| Identificadores formais Pré-Gate 3 | não encerrados |
| Gate 3 | NÃO AVALIADO |
| Fase 4 | NÃO INICIADA |
| GitHub/Figma | nenhuma alteração |

# 17. Encerramento

Resultado de origem recuperado:

> **65 identificadores `EVT-*` originados na Fase 3.6: 63 ativos/retidos no encerramento + 2 históricos absorvidos.**

`EVT-DOC-08` permanece corretamente separado como origem posterior da Fase 3.7.