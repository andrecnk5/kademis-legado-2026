# KADEMIS — AUD-D2-03 | Parecer independente pós-execução D2-REC-03

**Emissão:** 12/10/2026 (data de auditoria do pacote)  
**Frente:** DOC-AUTOSUF-01 / D2 / D2-REC-03  
**Objeto:** validação independente documental e estrutural dos entregáveis do Work; sem operações de escrita externas.  
**Resultado:** **CONFORME COM RESSALVAS PARA ACEITE PARCIAL; NÃO HOMOLOGADO PARA PUBLICAÇÃO CANÔNICA**.

## 1. Fontes e integridade

- ZIP original fornecido: `D2-REC-03_Pacote_Validado.zip`, **SHA-256 `5ebbd5c6f245e501da2f96263a99f09ecafbdbe161673e30c07864ac94555c29`**, 805067 bytes.
- **22 membros**, `testzip` sem corrupção; **21/21** entradas do `SHA256SUMS.txt` verificadas.
- ZIP imutável D2-REC-01 preservado: `3a335b9f8fe082bfacdf992e2b3cd6b9bd4e8555d20384f3619d5407275e978e`; matriz original 332 × 19 preservada, SHA `099da1a51b189614dd3d75f37c4fd30a5175b77e61d6f5067c543f763b322bd3`.
- ZIP imutável D2-REC-02 preservado: `096c6b0a25b7dfeec575cd802b6398d3197f5cd008423afc6a873c3c624d6b50`; matriz 334 × 19 SHA `49406c37f4f4da9c04d18dd61445534151d297b82da32b2b1bf546ec5c62eae9`.
- Matriz D2-REC-03: **334 × 19**, mesmo conjunto de 334 chaves família/ID, sem inclusões nem exclusões; SHA `3d25b8d6bb89cef52fa305ab0a8b38de2396e680697f2714a65d1996c5c8bee7`.
- **45/45 deltas** correspondem exatamente às diferenças entre as matrizes D2-REC-02 e D2-REC-03 (**37 IDs** afetados: 34 estados e três eventos). O delta tem **34 mudanças de SHA** de estados e **11 mudanças de outros campos** em eventos.
- Matriz auxiliar de proveniência: **1.002 linhas** (3 vínculos/registro). Mapa de eventos: **68/68 IDs únicos**; cronologia 3.9: 7 linhas; catálogo de fonte: 7 entradas.
- Repositório remoto conferido independentemente: `main=61e6d8584b53f323a55908ec277b6c81d61a81c1`, 12 arquivos, nenhum `docs/domain/`; nenhum novo merge detectado.

## 2. Resultado das frentes do contrato

| Achado anterior | Parecer | Evidência |
|---|---|---|
| F01, `EVT-CONS-02` | **SANADO documentalmente** | Nome anterior e final corretos no mapa; mesmo ID; refinamento sem absorção. |
| F02, `EVT-EXEC-10` e `EVT-PROT-04` | **SANADO na matriz de trabalho; conflito interfontes aberto** | Decisão individual não inferida de transição; I03-R05 registra classificação distinta de aprovação posterior. |
| F03, dois hashes I03-R03 | **SANADO** | 34 estados apontam ao blob de matriz `dcbd57a8...`; relatório distinto `4f05411e...`. |
| F04, atos da Fase 3.9 | **PARCIAL / PENDENTE** | L3 conhecido por relatório derivado; L4/L5/L6 sem mensagens primárias nos bytes auditados; aprovação geral M07 não cobre lotes individualmente. |
| F05, I03-R05/R04-A/R04-C | **RECUPERAÇÃO DE BYTES CONFORME; CONSOLIDAÇÃO PENDENTE** | 488 × 15; 127 glossário; 50 OD; falta manifesto original de identidade de I03-R05. |
| F06, 133 enunciados derivados | **LIMITAÇÃO PROBATÓRIA CORRETAMENTE PRESERVADA** | Sem elevação a aprovação individual, sem reabertura das 47 insuficiências de invariantes. |
| F07, localizadores | **SANADO POR MATRIZ AUXILIAR COM RESSALVA** | Fonte/documento e turno original separados; campo legado `localizador_primario` permanece semanticamente ambíguo se utilizado isoladamente. |

## 3. Verificação independente da matriz I03-R05

Fonte: `Fontes_Recuperadas_Copias/KADEMIS_I03-R05_D2_Matriz_Mestra_Proveniencia_R01_Integrada_v0.2_CANDIDATA_20261010.csv`; SHA **`fdaaa81bc26095dbb0423e3278f648e3f4f1871a2e4e8f6d2da8799702c3cce9`**. Conferidos efetivamente **488 registros × 15 colunas**, separados por ponto e vírgula (`;`), 488 chaves `namespace + chave` únicas.

| Namespace | Linhas |
|---|---:|
| GLOSSARIO | 127 |
| PROCESSO | 6 |
| OBJETO/CONCEITO | 50 |
| REGRA | 88 |
| INVARIANTE | 115 |
| EVENTO | 68 |
| ESTADO | 34 |
| **TOTAL** | **488** |

Situação documental do próprio artefato: **418 COMPROVADO**, **68 PARCIALMENTE COMPROVADO**, **2 NÃO COMPROVADO**. Isso não constitui homologação normativa individual de cada linha.

Matriz R04-A: 127 linhas documentais (106 COMPROVADO e 21 PARCIALMENTE COMPROVADO); hash `9c69e0df3ec8f286efe867dca1f257657bd91bb609b3c5cd1763c6885e94da1a`. Matriz R04-C: 50 chaves `OD-*`, hash `3b8814f3c191601ddaec4b6909faf5e4cfb2b1114c95d6eaa6dc59111a240042`. Não tratar `linha NNN` e `OD-*` como IDs formais de domínio.

## 4. Novas observações e riscos para a futura publicação

### AUD-D2-03-F01 — Enunciados de 177 linhas do catálogo integrado seguem sem transcrição
**BLOQUEANTE para declarar suficiência literal do I03-R05; não bloqueia recebimento da recuperação.**

A matriz candidata I03-R05 mantém `enunciado_original` e `enunciado_final` com marcador `NÃO TRANSCRITO` em **127/127 linhas GLOSSARIO** e **50/50 linhas OBJETO/CONCEITO**. A recuperação de seus arquivos de origem é efetiva, mas ainda é necessário conciliar o texto/definição de cada linha do glossário e a natureza/nome de cada objeto, usando fonte, chave, ressalva e delta. Muitas das definições R04-A agora são acessíveis; não completar os 21 parciais por inferência.

### AUD-D2-03-F02 — Divergência de alcance decisório entre dois catálogos
**PENDENTE de reconciliação probatória antes de baseline.**

Para `EVT-EXEC-10` e `EVT-PROT-04`, o I03-R05 candidato declara `APROVADO, em complemento posterior`, enquanto a D2-REC-03 usa `DOCUMENTADO EM TRANSIÇÃO/ESTADO APROVADO; ATO INDIVIDUAL DO EVENTO NÃO COMPROVADO`. Não apagar nenhuma fotografia. Identificar se a aprovação foi da **complementação em bloco** ou do **evento individual**, localizar fonte humana e registrar hierarquia e limites. A correção conservadora da D2-REC-03 evita aprovação individual indevida.

### AUD-D2-03-F03 — Cronologia da Fase 3.9
**PENDENTE por fonte primária exportável; não retroagir decisões.**

Auditoria histórica (410 linhas): L1 oito validações em bloco/contextuais, L2 dez validações individuais, L3 doze propostas em M06, execução de L4–L6 não comprovada naquele recorte. L3 possui ato prospectivo posterior citado literalmente em relatório derivado, sem mensagem nativa materializada no pacote. No histórico recuperável de conversas do projeto há referência à fala humana em 09/10/2026, mas **não há arquivo de export original com hash no ZIP**. Para L4/L5, menções anteriores feitas pelo assistente a oito/dez recomendações **não são manifestação humana primária autenticada**. L6 sem aprovação individual comprovada. Não confundir ausência documental com revogação de ato eventualmente existente.

### AUD-D2-03-F04 — Identificadores de regras e associação intercatálogos
**NÃO BLOQUEANTE; registrar antes de publicação.**

Os 88 IDs de regras dos catálogos D2-REC-03 e I03-R05 correspondem **quando comparados sem distinção de maiúsculas/minúsculas**; grafias exatas variam (p.ex. `RD-Aval-01` vs `RD-AVAL-01`). Não renomear nem normalizar silenciosamente: registrar a grafia literal de origem e uma chave de equivalência apenas para comparação editorial.

### AUD-D2-03-F05 — Fidelidade da proveniência
**NÃO BLOQUEANTE para entrega; bloqueia atribuição de prova primária.**

Há 1.002 referências derivadas e registro explícito de localizadores de mensagens não localizados em diversas linhas. A expressão `evidencia_ato_humano` na matriz auxiliar às vezes reproduz o enunciado documental ou uma atribuição derivada, não um comprovante literal de deliberação. Para catálogo futuro, incluir campos próprios para `ato_humano_literal_verificado`, `natureza_da_prova`, `timestamp`, `mensagem_origem`, `documento_derivado` e hash; onde não houver prova primária, declarar `NÃO COMPROVADO NO CORPUS` sem destruir o estado histórico reportado.

### AUD-D2-03-F06 — Vínculo do artefato I03-R05 ao aceite
**PENDENTE de confirmação de origem do pacote primitivo.**

SHA do CSV recuperado foi calculado de forma independente; porém o termo de aceite I03-R05 não traz hash individual que conecte criptograficamente esse exato CSV ao dossiê D1–D7 original. Recuperar manifesto original com SHA, ou registrar o vínculo como derivado não autenticado criptograficamente. O termo de aceite da execução documental não aprova automaticamente as 488 linhas como textos canônicos.

## 5. Pendências formais e Gates

Nenhuma diferença nos 334 registros-base fora das 45 correções autorizadas. O conjunto das 14 pendências formais abertas e dois encerramentos deliberados, Gate 3 APROVADO COM RESSALVAS, 12 oportunidades BF-R02 PROPOSTAS e Fase 4 NÃO INICIADA permanecem como descritos nos artefatos. Nenhuma migração, publicação, alteração de dados ou avanço de fase observado nesta auditoria.

As pendências documentais F01–F06 deste parecer **não constituem as 14 pendências formais PSD-I02**. Estas exigem decisões de domínio/jurídico/regimentais próprias, independentemente da recuperação textual.

## 6. Deliberação recomendada

**Aprovar o recebimento D2-REC-03 como EXECUÇÃO DOCUMENTAL PARCIAL CONFORME COM RESSALVAS**, sem declarar D2 fechada ou os catálogos homologados.

**Próximo incremento proposto, não iniciado — D2-REC-04:** reconciliar os 177 textos em I03-R05 a partir de R04-A/R04-C, com delta e identificação literal das 21 linhas parciais; registrar conflitos dos dois eventos e as grafias divergentes de RD; recuperar mensagem humana da Fase 3.9 (L3/L4/L5/L6) e manifesto original I03-R05 quando existentes; preparar matriz editorial proposta com marcação explícita `CANDIDATO / NÃO APROVADO / NÃO PUBLICADO`. Se faltar fonte, manter lacuna e sua ação humana específica. D2-REC-04 exige contrato/autorização próprios; não abrir PR nem iniciar D3–D5 ou Fase 4 por consequência deste parecer.

Posteriormente, submeter publicação controlada de artefatos de recuperação, incluindo estados e lacunas, a auditoria de suficiência e autorização operacional do responsável; o GitHub fiel ao Kademis pode publicar pendências honestas, não afirmações sem prova.

## 7. Checklist independente

- [x] SHA externo e integridade ZIP.
- [x] 21/21 entradas do manifesto principal conferidas.
- [x] Dois pacotes de entrada preservados integralmente.
- [x] 332/334/334 registros e conjunto de chaves.
- [x] 45/45 alterações campo a campo validadas, com antes/depois.
- [x] 68 eventos e `EVT-CONS-02` reconciliados.
- [x] Correções de status de dois eventos sem aprovações inferidas.
- [x] 34 estados vinculados ao hash da matriz.
- [x] I03-R05 488×15, glossário 127, objetos 50 e 106/21 documental auditados.
- [x] GitHub `main` mantida e 0 catálogos publicados.
- [ ] Conciliar 177 placeholders e vínculos primários.
- [ ] Resolver divergência intercatálogos de status dos complementos em 3.7.
- [ ] Anexar evidências de atos prospectivos originais e manifesto I03-R05 quando disponíveis.
- [ ] Autorizar em separado qualquer publicação GitHub.

**Ponto de parada:** auditoria independente concluída; encaminhar deliberação humana. Sem mutação remota executada.
