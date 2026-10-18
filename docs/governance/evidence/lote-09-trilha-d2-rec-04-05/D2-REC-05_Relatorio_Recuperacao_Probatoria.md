# D2-REC-05 — Relatório de recuperação probatória

**Data:** 12/10/2026  
**Estado:** execução documental focal local concluída; handoff AUD-D2-05.  
**Escopo:** F01–F04; fontes externas apenas em leitura.  
**Resultado geral:** dependências originais não foram integralmente recuperadas. O pacote documenta texto disponível, prova derivada, limitações e encaminhamentos. Não houve reescrita de matriz nem publicação.

## Resultado executivo

A `main` do GitHub foi reconfirmada no SHA `61e6d8584b53f323a55908ec277b6c81d61a81c1`; a árvore recursiva (tree `22c6c948c0c1b71d794b13cd71397932b867c336`) possui 12 arquivos, sem `docs/domain/` nem PSD-I02 como arquivo autônomo. Foram lidos, nesse SHA, README, Playbook v1.0, Governança v1.0, GOV-CONT-01 v0.1 e inventário/índice de proveniência Pré-Fase 4. Não se altera nenhuma posição de Gate ou pendência.

**F01 — Lotes L3–L6:** há um trecho literal de L3 visível no contexto do projeto e citado em relatório de continuidade. Ele expressa aprovação prospectiva de 12 recomendações com ressalvas, veda retroatividade a M06 e mantém 16 IDs abertos. O export nativo, timestamp/metadata verificáveis, mensagem anterior com objeto e sequência posterior não estão materializados. L4–L6 aparecem em índice/p parecer AUD-D2-04 como referências humanas, com pistas de horário e objeto, mas não há turnos nativos. L5/L6 têm somente fragmentos/contexto (“Validado, dê andamento” / “Validado, siga”) que não provam escopo isoladamente. A aprovação de L6 não foi convertida em execução histórica.

**F02 — Eventos 3.7:** R03 relata transições aprovadas e associa `EVT-EXEC-10` e `EVT-PROT-04`; relata também uma manifestação em bloco da 3.7 que nomeia EVT-PROT-04. R05 registra ambos como “APROVADO, em complemento posterior”. D2-REC-03 distingue aprovação de transição/estado de ato individual. Esses artefatos são relatórios/matrizes de recuperação, não a exportação das mensagens originais. A distinção entre (a) transição, (b) complementação em bloco e (c) ato individual permanece explícita; a divergência documental não é resolvida por esta execução.

**F03 — I03-R05:** o pacote original D1–D7 e manifesto de saída que vincule por SHA-256 o CSV ao aceite não foram localizados nas fontes disponíveis ou nas buscas direcionadas. Foi reconstituída a cadeia apenas desde os snapshots preservados: CSV recebido `fdaaa81bc26095dbb0423e3278f648e3f4f1871a2e4e8f6d2da8799702c3cce9` e candidata D2-REC-04 `223c9ac144c16b4edf99a3fffc20ec1b77e4c4732ed6e3f922c597405466843e`. Conclusão: `CADEIA RECONSTRUÍDA / VÍNCULO HISTÓRICO NÃO COMPROVADO`. O termo de aceite e o manifesto D1 de fontes permanecem preservados como documentos distintos; não são substituídos por um hash criado agora.

**F04 — Consolidação:** nenhum fato primário novo, completo e autenticado sustenta alterar D2-REC-01..04 ou I03-R05; o delta proposto é vazio (somente cabeçalho). Ledger e CSVs separados registram o que foi aprovado, referenciado por derivado, conflitado ou não demonstrado. As fontes e pedidos dirigidos aos chats de origem estão anexados.

## F01 — Lotes 3.9: estados em linhas temporais distintas

- **M06 histórico:** os relatos acessíveis descrevem o L3 como proposto, sem validação individual no instante M06; M07 é aprovação geral da fase e não equivale a aprovação item a item. Lotes 4–6 constam como planejados/reservados, sem execução específica comprovada no relatório histórico.
- **Deliberação posterior L3:** o trecho literal no contexto do projeto é a citação contida no ledger. Ele declara prospectividade e proíbe retroatividade. O índice aponta `2026-10-09T17:43:36Z`, mas a data/hora não foi verificada contra export original. O texto do objeto de 12 recomendações é reproduzido em relatório secundário, sem prova de que essa versão era a mensagem imediatamente antecedente.
- **L4:** AUD-D2-04/índice relatam referência de aprovação prospectiva em bloco de L4-R01..R08, com ressalvas; ato e objeto íntegros não acessíveis.
- **L5:** “Validado, dê andamento” só aparece como fragmento/pista associado a L5-R01..R10. Mensagem anterior ausente; alcance não comprovado.
- **L6:** “Validado, siga” é pista para AT-L6-01..05. A fonte histórica descreve L6 como reservado; não se infere execução do lote.

As datas/horários L4 `18:18:46Z`, L5 `18:20:05Z`, L6 `18:23:19Z` permanecem **pistas de índice**, não timestamps verificados. O ledger não trata ausência de export como revogação.

## F02 — Eventos complementares da Fase 3.7

O relatório R03 §3.5 registra a manifestação “Adoro suas sugestões, aprovado, siga” e diz que a direção aprova também as complementações eventuais `EVT-DOC-08` e `EVT-PROT-04`; é evidência derivada de inclusão de EVT-PROT-04 em bloco, não um turno original/objeto completo. R03 §3.6 registra “Li e aprovo a suas sugestões. Siga” no contexto das sugestões às perguntas 1–8, além dos estados `EST-JUST-01/02`; o vínculo exato do ato ao ID `EVT-EXEC-10` permanece documentado por R03, não autenticado por export nativo.

| Escopo de aprovação | EVT-EXEC-10 | EVT-PROT-04 |
|---|---|---|
| Transição de estado | R03 lista como aprovada a transição associada e relaciona o evento; relato derivado | R03 lista como aprovada a transição associada e relaciona o evento; relato derivado |
| Complementação em bloco | I03-R05 diz “aprovado em complemento”; R03 associa EVT-EXEC-10 à decisão/transição, mas resposta e objeto primários faltam | R03 relata bloco que nomeia a complementação EVT-PROT-04; objeto/turno nativos faltam |
| Evento individual | Não demonstrado em mensagem nativa | Não demonstrado como ato individual separado; a menção de bloco é distinta |

A fotografia D2-REC-03 e a fotografia I03-R05 são ambas mantidas. Nenhum estado decisório foi substituído. A resolução exigiria mensagem/objeto e contexto do chat de origem.

## F03 — Cadeia de custódia

O encadeamento local, hashes, fontes e limites estão em `D2-REC-05_Cadeia_Custodia_I03-R05.md`. O CSV recuperado de entrada, sua candidata D2-REC-04, o termo de aceite, o manifesto D1 de fontes e o pacote D2-REC-04 estão preservados com hashes separados. A soma de verificação do ZIP desta execução documenta bytes do pacote D2-REC-05, não prova retroativamente o conteúdo do D1–D7 original.

## F04 — preservação, riscos e saída

- Matrizes D2-REC-01 (332×19), D2-REC-02 (334×19), D2-REC-03 (334×19), I03-R05 original e candidata D2-REC-04 (ambas 488×15) foram conferidas por SHA-256 e copiadas como imutáveis; nenhuma linha foi reescrita.
- Os 315 deltas D2-REC-04 e as classificações anteriores permanecem congelados e anexos à fonte. `Delta_Proposto_Nao_Aplicado.csv` tem zero linhas de dados porque não houve prova primária nova para alteração.
- O uso das solicitações A/B/C foi documental: estão anexadas sem alteração e mapeadas a chats/alvos. Não há envio a outros chats nesta execução.
- Gate 3 permanece APROVADO COM RESSALVAS; 14 pendências formais abertas + 2 encerramentos; 12 BF-R02 propostas; Fase 4 não iniciada. Nada foi encerrado ou reavaliado.
- Não houve alteração em GitHub, Figma, código, banco, dados, infraestrutura ou documentos remotos.

**Parada:** handoff à AUD-D2-05. A auditoria deve avaliar suficiência do texto L3, escopos derivados 3.7, cadeia reconstruída e solicitações pendentes antes de qualquer publicação ou novo contrato.
