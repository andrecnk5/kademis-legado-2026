# D2-REC-03 — Relatório de saneamento documental

**Estado:** execução documental parcial concluída para handoff independente. Nenhuma publicação.
**Data:** 12/10/2026 UTC. **Base remota consultada em leitura:** `andrecnk5/kademis`, `main=61e6d8584b53f323a55908ec277b6c81d61a81c1`.

## Resultado

As frentes F01–F03 e F07 receberam correções locais rastreáveis. A busca dirigida F04–F06 localizou bytes adicionais de I03-R05 D2 (488×15), I03-R04-A Glossário (127 linhas) e I03-R04-C (50 linhas `OD-*`). A fonte primária nativa das conversas e aprovações não foi exportada/localizada; documentos recuperados não foram promovidos a decisões ou baseline.

A matriz revisada conserva 334 IDs/19 colunas, mesmo conjunto de chaves da D2-REC-02. O pacote D2-REC-02 e a referência D2-REC-01 são preservados byte a byte. O delta deste incremento registra apenas alterações de campo feitas em resposta a F01–F03.

## AUD-D2-02 F01–F07

| Achado | Execução e limite |
|---|---|
| F01 — `EVT-CONS-02` | A matriz e o mapa distinguem denominação histórica `Decisão Acadêmica Tomada` da denominação final refinada `Decisão ou Encaminhamento do Conselho Registrado`. O mesmo ID foi mantido; não absorvido nem recriado. I03-R02 §6 consultado como relatório derivado; turno nativo não localizado. |
| F02 — `EVT-EXEC-10` / `EVT-PROT-04` | Campos de decisão e ato individual foram qualificados como `DOCUMENTADO EM TRANSIÇÃO/ESTADO APROVADO; ATO INDIVIDUAL DO EVENTO NÃO COMPROVADO`. As transições/estados documentados permanecem como fonte; aprovação individual não foi inferida. |
| F03 — 34 estados | Verificados os dois arquivos distintos: Relatório I03-R03 SHA `4f05411ef4817f9c74dc8019aed1a3b4c9c4b3bbf4a0392b098340a6cadd35d3`; Matriz I03-R03 SHA `dcbd57a81d1f33fa18d6ab2766f8395d4dc272a33a4b7a8a5e1634993a77736b`. Os 34 registros apontam para o hash da matriz consultada. O hash do relatório segue associado separadamente na proveniência. |
| F04 — Fase 3.9 | Consultados o histórico de 410 linhas e o relatório de continuidade. O L3 mantém M06 como PROPOSTO e preserva o ato prospectivo apenas como citação reproduzida por relatório derivado; mensagem nativa ausente. O relatório de continuidade recomenda futura reconciliação L4/L5 e reserva L6; não comprova aprovações específicas. Os atos e escopos individuais L4/L5 não foram recuperados; L6 não comprovado. A aprovação geral M07 é separada de aprovações por lote. |
| F05 — I03-R05 / glossário / objetos | Recuperados os bytes da matriz candidata I03-R05 (488 registros, 15 colunas), matriz I03-R04-A (127 linhas; 106 documentariamente comprovadas e 21 parciais segundo a fonte) e I03-R04-C (50 chaves OD). Nenhum dos artefatos foi elevado a baseline. O termo de aceite aceita execução documental, não aprova os enunciados item a item. O manifesto de aceite não vinculou SHA individual do CSV materializado; fica dependência de confirmação do hash do pacote original. |
| F06 — 133 enunciados | Mantida distinção entre texto em documento de recuperação e aprovação por turno humano original. Os 38 RD, 61 EVT e 34 EST são totais informados na auditoria independente anterior; não se criou correspondência fictícia entre os 61 títulos e os 68 IDs do mapa. Os 47 invariantes insuficientes permanecem sem alteração. |
| F07 — proveniência | A matriz principal continua com 19 colunas, incluindo `localizador_primario`. A auxiliar separa fonte consultada, natureza, localizador documental, localizador de mensagem original, SHA, evidência de ato e limitação. Localizador de relatório/matriz derivada não é apresentado como ponteiro de turno nativo. |

## Recuperação e dependências humanas

A busca na Biblioteca encontrou as matrizes I03-R05/I03-R04-A/I03-R04-C. Foram verificadas contagens, estrutura, hashes locais e status/ressalvas. O chat original “Fase 3.9” e o chat de continuidade “Fase 3.10” não puderam ser inspecionados diretamente para verificar turnos nativos. Consultas específicas por atos L3/L4/L5/L6 retornaram apenas arquivos derivados e a referência do contrato, não export original. Cada solicitação e próximo passo consta em `D2-REC-03_Catálogo_Pendencias_de_Fonte.csv`.

## Estado separado e inalterado

Gate 3 permanece APROVADO COM RESSALVAS conforme estado recebido; não foi reavaliado. As 14 pendências formais permanecem ABERTAS e os dois encerramentos deliberados permanecem preservados. As 12 oportunidades BF-R02 permanecem PROPOSTAS. Fase 4 NÃO INICIADA; D3–D5 não iniciadas. Nenhuma alteração ou encerramento de pendência formal.

## Validação executada

- SHA-256 do pacote D2-REC-02 de entrada: `096c6b0a25b7dfeec575cd802b6398d3197f5cd008423afc6a873c3c624d6b50`; ZIP testado, 21 entradas.
- Matriz D2-REC-01: 332×19, SHA `099da1a51b189614dd3d75f37c4fd30a5175b77e61d6f5067c543f763b322bd3`. D2-REC-02: 334×19, SHA `49406c37f4f4da9c04d18dd61445534151d297b82da32b2b1bf546ec5c62eae9`.
- Os arquivos zip históricos internos foram extraídos para verificação; ambos os pacotes imutáveis do output são cópias byte idênticas das entradas recebidas.
- I03-R05 = 488×15; R04-A = 127 linhas; R04-C = 50 IDs; I03-R03 relatório/matriz/tabela de transições tiveram hashes conferidos.
- Foram conferidos conjunto de chaves, contagem de delta, classificação de eventos e estado formal recebido; verificações detalhadas estão no handoff.

## Limite e parada

Este é um saneamento documental parcial. Não declarar D2 completo, catálogo canônico ou aprovação de textos. Ponto de parada: submeter pacote local a auditoria independente. Nenhuma publicação, edição remota, PSD-I04, Gate 3, D3–D5 ou Fase 4.
