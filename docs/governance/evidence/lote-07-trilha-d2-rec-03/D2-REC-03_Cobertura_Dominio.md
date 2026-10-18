# D2-REC-03 — Cobertura documental e proveniência

Data: 12/10/2026 UTC. Escopo: D2-REC-03 autorizado. Este quadro não é catálogo aprovado.

## Universos mantidos separados

| Universo documental | Registros | Campos | Estado e nota |
|---|---:|---:|---|
| Matriz D2-REC-01 original | 332 | 19 | Baseline histórico, preservado byte a byte no pacote imutável. |
| Matriz D2-REC-02 de entrada | 334 | 19 | Base do trabalho; arquivo original preservado. |
| Matriz revisada D2-REC-03 | 334 | 19 | Mesmo conjunto de chaves; só correções focais autorizadas. |
| I03-R05 D2 candidato integrado R01 v0.2 | 488 | 15 | Universo heterogêneo; CANDIDATO / NÃO PUBLICADO. Termo de aceite limita aprovação a execução documental. |
| I03-R04-A matriz primária de glossário | 127 | tabela documental | Bytes recuperados; 106 itens documentais comprovados e 21 parciais segundo cabeçalho/linhas da fonte. Índices `linha NNN` não são IDs de domínio. |
| I03-R04-C matriz de objetos | 50 | tabela documental | Bytes recuperados; 50 chaves `OD-*`, classificadas como chaves da auditoria, não IDs oficiais do domínio. |

## I03-R05: subtotais por namespace e estado documental

A matriz CSV materializada contém 488 linhas, 15 colunas, sem duplicidades de chave-família no arquivo consultado. O termo de aceite de 10/10/2026 registra: 418 COMPROVADOS, 68 PARCIALMENTE COMPROVADOS e 2 NÃO COMPROVADOS; não se converte “comprovado” em decisão aprovada.

| Namespace | Linhas |
|---|---:|
| ESTADO | 34 |
| EVENTO | 68 |
| GLOSSARIO | 127 |
| INVARIANTE | 115 |
| OBJETO/CONCEITO | 50 |
| PROCESSO | 6 |
| REGRA | 88 |

O I03-R05 v0.2 não substitui o baseline 334 e não foi aprovado individualmente nem publicado. O termo de aceite registra 127 glossário, 6 processos, 50 objetos, 88 regras, 115 invariantes, 68 eventos e 34 estados.

## Cobertura probatória atual

- **Fase 3.9:** seis lotes preservados. L1: 8 validados em bloco/contextualmente; L2: 10 validados individualmente — ambos segundo relatório histórico derivado. L3: 12 propostas permanecem PROPOSTAS no instante M06; há relato derivado de aprovação prospectiva posterior, sem mensagem nativa localizada. L4 e L5 aparecem como reconciliações futuras recomendadas pelo relatório de continuidade, não como já aprovadas; referências de contagem do contrato não comprovam escopo/ato. L6 permanece reservado/não comprovado. A aprovação geral M07 é separada da validação por lote.
- **EVT-CONS-02:** nome histórico e nome final documentado reconciliados no mesmo ID; sem absorção ou novo ID.
- **EVT-EXEC-10 / EVT-PROT-04:** fonte I03-R03 sustenta transições/estados; ato individual de evento não comprovado.
- **Estados (34):** texto/localização atribuído à matriz I03-R03 (SHA `dcbd57a81d1f33fa18d6ab2766f8395d4dc272a33a4b7a8a5e1634993a77736b`). Relatório I03-R03 separado (SHA `4f05411ef4817f9c74dc8019aed1a3b4c9c4b3bbf4a0392b098340a6cadd35d3`).
- **133 enunciados auditados em D2-REC-02** (38 RD, 61 EVT, 34 EST): correspondência textual em fontes documentais derivadas; não se dispõe dos turnos nativos para autenticar a aprovação final. O escopo 61 títulos EVT não é expandido para os 68 eventos do universo sem mapeamento individual sustentado. O mapa contém 68 IDs separados.
- **Invariantes:** não modificar os 47 registros insuficientes apontados no parecer anterior; permanece necessário saneamento específico com evidência individual.

## Estados de governança preservados

Gate 3: APROVADO COM RESSALVAS (estado recebido; não reavaliado). 14 pendências formais ABERTAS e 2 encerramentos deliberados preservados. BF-R02: 12 oportunidades PROPOSTAS. Fase 4: NÃO INICIADA. D3–D5 não iniciadas. Nenhuma pendência formal foi alterada.
