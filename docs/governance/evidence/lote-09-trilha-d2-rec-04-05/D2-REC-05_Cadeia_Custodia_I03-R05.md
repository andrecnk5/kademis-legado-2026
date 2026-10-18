# D2-REC-05 — Cadeia de custódia I03-R05

**Classificação final:** `CADEIA RECONSTRUÍDA / VÍNCULO HISTÓRICO NÃO COMPROVADO`.

Este documento descreve somente os bytes disponíveis e sua linhagem local. Não é manifesto histórico, não declara que um arquivo foi entregue em D1–D7 e não simula a cadeia de custódia original.

| Marco | Artefato/estado | SHA-256 / evidência | Limite |
|---|---|---|---|
| A | Pacote preparatório recebido para D2-REC-05 | `13ca6e196f7d2f08f082750ca3b965d0fd9efe8a88be87baf5d11faa22452734`; ZIP sem erro CRC | Pacote de trabalho de 12/10; não é pacote D1–D7 |
| B | D2-REC-04_Pacote_Para_Auditoria_IMUTAVEL.zip recebido dentro do pacote | `df8ff2912169f9a5c828301810bca0f2e9ce8fbe9f808b93d7e674473d01cb07`; 77 entradas; SHA256SUMS principal 72/72 validado | Contém cópia imutável de D2-REC-04 e fontes; não é pacote original I03-R05 |
| C | CSV de entrada I03-R05 `v0.2_CANDIDATA_20261010.csv` | `fdaaa81bc26095dbb0423e3278f648e3f4f1871a2e4e8f6d2da8799702c3cce9`; 412425 bytes; 488 registros / 15 colunas | Hash comprova a identidade do snapshot neste pacote. Não vincula ao output aceito originalmente |
| D | I03-R05 candidata reconciliada D2-REC-04 | `223c9ac144c16b4edf99a3fffc20ec1b77e4c4732ed6e3f922c597405466843e`; 421485 bytes | Derivação posterior D2-REC-04; distinta do CSV de entrada, preservada sem escrita |
| E | D1 manifesto de fontes (documento local) | `62a180533648001c7c4454bae4993f34f39663e4ea0cb4008eebfebdbcbf47f8` | Lista snapshots/fontes e hashes declarados; não contém prova de SHA-256 do CSV como output do D1–D7 aceito |
| F | Termo de aceite documental I03-R05 | `3dee98cb09749db426beae23b7060f1654b96a686f432a54a848693ba43f8fcd` | Registro de aceite documental acessível; não vincula criptograficamente o CSV ao pacote original |
| G | ZIP original D1–D7 e manifesto de saída | NÃO LOCALIZADOS nos arquivos do pacote nem nos resultados das buscas direcionadas registradas | Vínculo histórico não comprovado; ausência não invalida/retira o aceite e não comprova inexistência do pacote |

## Procedimento e limite

1. Conferidos os bytes do ZIP D2-REC-05 e o ZIP D2-REC-04 aninhado; teste CRC limpo.
2. Recomputados os hashes do CSV de entrada e da candidata D2-REC-04; ambos conferem com os valores declarados nos respectivos artefatos.
3. O D2-REC-04 é preservado byte a byte como fonte de D2-REC-05. Matrizes D2-REC-01, 02, 03 e ambas as versões da I03-R05 estão copiadas no diretório `Matrizes_Protegidas_Imutaveis` e conferidas contra os hashes de baseline.
4. Consultas de Library por D1–D7/manifesto/CSV localizaram o termo de aceite, D1 manifesto e relatórios derivados, mas nenhum ZIP/manifesto original de saída identificável. Histórico nativo do chat de entrega não está acessível nesta execução.
5. O novo `SHA256SUMS.txt` cobre os bytes efetivamente incluídos no pacote D2-REC-05. **Não** deve ser interpretado como manifesto histórico do dossiê D1–D7.

Nenhuma hash nova é retrodatada. Nenhuma matriz é substituída ou reescrita. Para elevar esta cadeia a evidência histórica, é necessária a exportação original D1–D7 com `SHA256SUMS`/manifesto de saída e prova de entrega/aceite.
