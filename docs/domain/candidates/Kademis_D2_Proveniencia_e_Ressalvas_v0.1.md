# Kademis — Proveniência e ressalvas D2 v0.1 (CANDIDATO)

**ESTADO: CANDIDATO / EM REVISÃO POR PR. NÃO INTEGRADO À `main`. NÃO É BASELINE DE DOMÍNIO.**

## Autoridade e integridade

- Playbook vigente: `docs/playbook/Kademis_Master_Development_Playbook_v1.0.md` — APROVADO.
- Governança vigente: `docs/governance/Kademis_Governanca_v1.0.md` — APROVADA.
- GOV-CONT-01 v0.1: `docs/governance/Kademis_Politica_Continuidade_Documental_v0.1.md` — APROVADA/INTEGRADA, não automaticamente v1.0.
- PSD-I02: `docs/governance/Kademis_Indice_Proveniencia_Pre_Gate_3_v0.1.md` — 14 PENDÊNCIAS ABERTAS + 2 ENCERRAMENTOS HUMANOS DELIBERADOS.
- Gate 3/BF-R02: `docs/governance/Kademis_Registro_Sincronizacao_Gate_3_BF-R02_v0.1.md` — Gate 3 APROVADO COM RESSALVAS, 12 oportunidades BF-R02 PROPOSTAS.
- I03-R05 de entrada: SHA-256 `fdaaa81bc26095dbb0423e3278f648e3f4f1871a2e4e8f6d2da8799702c3cce9`.
- I03-R05 candidata reconciliada: SHA-256 `223c9ac144c16b4edf99a3fffc20ec1b77e4c4732ed6e3f922c597405466843e`.
- D2-REC-05 ZIP final: SHA-256 `90b030897ddcfd5fbd4b91116394c1499df6fa9b2e376d48571ecdb13906d667`, 47 entradas, CRC sem erro; manifesto principal 45/45, preparatório 7/7 e D2-REC-04 aninhado 72/72 conferidos por auditoria.
- AUD-D2-05 e adendo de integridade: APROVADOS pelo responsável, com ressalvas; isso não aprova um catálogo canônico.
- D2-SUF-01: orientação editorial APROVADA em 13/10/2026 pela resposta humana “Aprovado, autorizado, siga”; essa aprovação inicial era limitada à preparação editorial, **não à publicação**.
- D2-PUB-01 / PR A: autorização posterior, expressa no chat de Governança, para prosseguir com branch, commit, push e abertura de PR contendo somente estes dois documentos; **merge permanece pendente de autorização separada**.

## Lacunas A/B/C — NÃO RESOLVIDAS

| Dependência | Estado | Prova ainda necessária |
|---|---|---|
| A — Fase 3.9 L3–L6 | PARCIAL/DERIVADA | Export original do ato e da proposta antecedente, contexto, autoria, timestamp e escopo. L3 tem texto citado, mas metadados e objeto anterior não autenticados. Não retroagir a M06. |
| B — EVT-EXEC-10/EVT-PROT-04 | CONFLITO PROBATÓRIO | Distinção de aprovação da transição, aprovação da complementação em bloco e de evento individual. Aprovação em bloco poderia bastar quando objeto e ato forem comprovados. |
| C — I03-R05 D1–D7 | CADEIA RECONSTRUÍDA | ZIP D1–D7 original, manifesto de saída e prova que conecta CSV aceito aos bytes originais. A ausência de artefato não revoga o aceite. |

## Limites de conteúdo

1. A fonte candidata é registro documental derivado, não automaticamente baseline aprovado. Campos com `COMPROVADO` podem provar a existência de item e não seu texto final ou aprovação individual.
2. A linha 127 do glossário permanece EM DESCOBERTA. Objetos OD não são convertidos em definições; menções em transições não substituem validação de eventos.
3. Matrizes D2-REC-01 (332×19), D2-REC-02 e 03 (334×19), duas matrizes I03-R05 (488×15) e os 315 deltas de D2-REC-04 permanecem historicamente distintos; D2-REC-05 possui 0 delta aplicado.
4. Fontes originais armazenadas fora do GitHub exigem localização, autorização, hashes, acesso controlado e procedimento de recuperação reais. **Não afirmar que há links para anexos locais na `main`.**
5. Fontes primárias ainda ausentes devem aparecer como `PENDENTE`/`NÃO COMPROVADO` no aspecto probatório pertinente; não como rejeitadas, revogadas ou inexistentes.
6. Qualquer catálogo de D2 publicado tem de preservar risco LGPD, ressalvas documentais e status de revisão, bem como distinguir documento publicado de decisão aprovada.

## O que este artefato não faz

Não altera Gate 3, as 14+2 pendências, BF-R02, Fase 4; não executa D3–D5; não aprova arquitetura, stack, banco, RBAC, endpoints ou implementação de produto; não transforma o SGSA - Old em baseline; não autoriza GitHub, Figma ou publicação de dados pessoais.
