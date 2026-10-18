# KADEMIS — Handoff D2-REC-04 para auditoria independente

## Estado e limite

Execução documental local das frentes F01–F05 concluída. Este pacote contém candidatas, não catálogo aprovado. Nenhum conteúdo foi publicado. O próximo passo autorizado é somente auditoria independente do pacote. Não houve execução de D3–D5, PSD-I04, Gate 3 ou Fase 4.

## Entregáveis

- Relatório: `D2-REC-04_Relatorio_Reconciliacao.md`
- Matriz candidata 488×15: `D2-REC-04_I03-R05_Matriz_Mestra_CANDIDATA_Reconciliada.csv`
- Delta de 315 alterações: `D2-REC-04_Delta_Campo_a_Campo.csv`
- Inventário focal 177: `D2-REC-04_Inventario_177_Reconciliado.csv`
- Proveniência L3–L6: `D2-REC-04_Proveniencia_Atos_Fase_3_9.csv`
- Parecer de conflito EVT-EXEC-10 / EVT-PROT-04: `D2-REC-04_Parecer_Conflito_Eventos.md`
- Equivalências RD: `D2-REC-04_Equivalencias_Grafias_RD.csv`
- Proveniência/hash e identidade I03-R05: `D2-REC-04_Registro_Fontes_Hashes.md`, `D2-REC-04_Manifesto_I03-R05.md`
- Lacunas/ações humanas: `D2-REC-04_Lacunas_Dependencias_Acoes_Humanas.csv`
- Cobertura: `D2-REC-04_Mapa_Cobertura.md`

## Verificações para o auditor

1. Recalcular todos os SHA-256 do `SHA256SUMS.txt` e validar o arquivo `D2-REC-04_Pacote_Para_Auditoria.zip`.
2. Comparar a matriz candidata com o CSV I03-R05 original: somente 105×3 campos diferem; confirmar 488 chaves e ordem.
3. Verificar literalidade linha a linha contra R04-A; assegurar que parcial/linha 127/50 objetos não foram promovidos.
4. Revalidar os 177 cotejos e classificações, 315 linhas de delta, e campos decisórios intactos.
5. Conferir D2-REC-03 (334 registros), D2-REC-01/02 e suas hashes anexas.
6. Julgar suficiência de evidências L3–L6, os dois conflitos de evento, identidade do pacote R05, e ações humanas propostas; sem reabrir decisões fora do contrato.

## Riscos e ressalvas

- R04-A é uma fonte documental recuperada que reproduz definições e estados, sem mensagens nativas de cada turno neste pacote. As 105 transcrições provam literalidade perante a R04-A, não uma nova aprovação nem autenticação nativa individual.
- A prova nativa dos atos L3–L6 não está completa; L4/L5 são pistas do contrato.
- A identidade binária histórica do output I03-R05 em relação ao pacote aceito continua sem vínculo criptográfico demonstrado.
- EVT-EXEC-10 e EVT-PROT-04 permanecem em divergência probatória de escopo.
- As 50 observações R04-C não são definições formais; depender de fonte/decisão humana para qualquer redação formal.

## Hashes principais

- D2-REC-03 input ZIP: `5ebbd5c6f245e501da2f96263a99f09ecafbdbe161673e30c07864ac94555c29`
- I03-R05 input CSV: `fdaaa81bc26095dbb0423e3278f648e3f4f1871a2e4e8f6d2da8799702c3cce9`
- I03-R05 candidata: `223c9ac144c16b4edf99a3fffc20ec1b77e4c4732ed6e3f922c597405466843e`
- D2-REC-03 matriz: `3d25b8d6bb89cef52fa305ab0a8b38de2396e680697f2714a65d1996c5c8bee7`
- R04-A: `9c69e0df3ec8f286efe867dca1f257657bd91bb609b3c5cd1763c6885e94da1a`
- R04-C: `3b8814f3c191601ddaec4b6909faf5e4cfb2b1114c95d6eaa6dc59111a240042`

O SHA-256 final do ZIP de auditoria está no arquivo externo `D2-REC-04_Pacote_Para_Auditoria.zip.sha256` e é comunicado na entrega. A lista `SHA256SUMS.txt` cobre todos os entregáveis e fontes incorporadas antes da criação do ZIP, exceto o próprio arquivo de checksums e o ZIP, para evitar autorreferência.

**Ponto de parada:** entregar ao chat Auditoria e Governança e aguardar avaliação independente. Nenhuma publicação ou atividade subsequente está autorizada por este contrato.
