# Lote 07 — Trilha histórica D2-REC-03 e auditoria

Preservação de artefatos de recuperação documental de 12/10/2026. Publicação autorizada pela instrução contínua do responsável em 18/10/2026. Não constitui novo baseline de domínio, aprovação individual ou encerramento D2.

## Fontes e integridade

Origem física: KADEMIS_DOC-AUTOSUF-01_D2-REC-04_Pacote_Preparatorio_20261012.zip, custódia controlada libfile_897d555c7a108191b7d99e802ef2cdbf. Dez arquivos vêm do D2-REC-03_Pacote_Validado.zip interno; o parecer AUD-D2-03 está no nível externo. Cópias integrais; nomes, bytes, CSVs, grafias e estados históricos preservados.

| Arquivo | SHA-256 |
|---|---|
| [D2-REC-03_Catálogo_Pendencias_de_Fonte.csv](D2-REC-03_Catálogo_Pendencias_de_Fonte.csv) | `dd6980ea861981bcadc1479a0d85b7124145d53cc27f17383eab852c2fa57425` |
| [D2-REC-03_Cobertura_Dominio.md](D2-REC-03_Cobertura_Dominio.md) | `15a4290b66fd43e7357ef89c88eae37f7da92e69bce751154e5be008e97f35f5` |
| [D2-REC-03_Cronologia_3_9.csv](D2-REC-03_Cronologia_3_9.csv) | `460bc9e1927aab391e9e9faa8d0bf5dda51d49155bfef360f2a9c75daa43c885` |
| [D2-REC-03_Delta_Auditavel.csv](D2-REC-03_Delta_Auditavel.csv) | `11a1aca432c632c6f777b1110ec76b2c08bd7b45245b0dc7393fbe78ceebec2e` |
| [D2-REC-03_Handoff_Auditoria.md](D2-REC-03_Handoff_Auditoria.md) | `f2376fae68da11a7c18aef80a3bad3e5fbece874f0b6cb2aeab54c65b86822d0` |
| [D2-REC-03_Mapa_Eventos_68.csv](D2-REC-03_Mapa_Eventos_68.csv) | `0d5fd22d8af19dae2de033a28d9f05803338cde90e6fc88038741869cd06df8a` |
| [D2-REC-03_Matriz_Evidencias_Revisada.csv](D2-REC-03_Matriz_Evidencias_Revisada.csv) | `3d25b8d6bb89cef52fa305ab0a8b38de2396e680697f2714a65d1996c5c8bee7` |
| [D2-REC-03_Matriz_Proveniencia.csv](D2-REC-03_Matriz_Proveniencia.csv) | `b796b01a05b49845cf1074b99a51b780a4629bb9514a07e9b495883af951c766` |
| [D2-REC-03_Registro_Fontes_SHA256.md](D2-REC-03_Registro_Fontes_SHA256.md) | `6851dc71773bbd33d2d416b29091735e052f1124adec898577fe3adf7e698870` |
| [D2-REC-03_Relatorio_Saneamento.md](D2-REC-03_Relatorio_Saneamento.md) | `022bc9600dace0e2a033433b29d548eda768a44e261ba7b3ca7cea32e545f849` |
| [KADEMIS_D2-REC-03_AUD-D2-03_Parecer_Independente_20261012.md](KADEMIS_D2-REC-03_AUD-D2-03_Parecer_Independente_20261012.md) | `c04a516e0e251c9512e694a73bc6b909bec44eb14b3b2ab3f416b5f183710d37` |

## Leitura por função

A matriz principal contém 334 registros e 19 colunas. O delta registra 45 mudanças de campo em 37 IDs contra D2-REC-02, com as mesmas chaves. A proveniência tem 1.002 vínculos, três por registro. Mapa de eventos: 68 IDs; cronologia: sete linhas; catálogo de dependências: sete entradas. Essas medidas são de universos distintos e não se somam ao candidato 488×15.

A verificação atual reproduziu a igualdade exata das 45 mudanças e do conjunto de 334 IDs contra os bytes D2-REC-02 custodiados no ZIP original. Nenhuma matriz foi reeditada. O parecer independente é documento histórico; seus checks e recomendações não são novos resultados de Gate nesta publicação.

## Precedência temporal e limites obrigatórios

- A expressão localizador_primario da matriz legada não autentica um turno original. Ler junto com a matriz auxiliar, que distingue fonte derivada e mensagem nativa não localizada. evidencia_ato_humano pode reproduzir atribuição derivada; não equivale automaticamente a ato literal verificado.
- A fotografia histórica sobre 177 placeholders e NÃO PUBLICADO refere-se ao CSV integrado de então (SHA fdaaa81b...). O candidato publicado posteriormente na main tem SHA 223c9ac1... e foi reconciliado por PR16. Preservar ambas as versões, sem usar a observação antiga para reinstalar uma lacuna já tratada ou alterar o catálogo.
- L3: doze recomendações aprovadas prospectivamente EM BLOCO, sem retroação a M06. L4/L5/L6: 23 referências e limitações aceitas com ressalvas; não 23 aprovações individuais. Solicitações antigas nos CSVs de dependência não são tarefas atuais automáticas.
- B: aplicar o adendo posterior de EVT-EXEC-10. Declaração humana nominal de aprovação na abertura de 3.8 documentada; cadeia originária exata em 3.7 NÃO COMPROVADA. EVT-PROT-04 conserva aprovação em bloco documentada. Não substituir o adendo por classificação histórica desta matriz.
- C: cópia candidata I03-R05 acessível; identidade com ZIP original aceito e manifesto de origem NÃO COMPROVADOS. Publicar estes relatórios não encerra C.
- Invariantes, glossário parcial e versões preliminares: mesmas limitações conhecidas; não criar novas pendências nem solicitar recuperação repetida. Não promover correspondência textual a autenticação de aprovação.
- Histórico de main com 12 arquivos e ausência de docs/domain é fotografia de 12/10, superada pelas publicações posteriores. Recomendações de execução D2-REC-04 não comprovam execução só porque existe contrato preparado.

## Custódia dos antecedentes

Os ZIPs históricos D2-REC-01 e D2-REC-02 não são duplicados neste lote. Permanecem no contêiner controlado acima → D2-REC-03_Pacote_Validado.zip → D2-REC-01_Pacote_Entrega_Referencia_Imutavel.zip (SHA 3a335b9f8fe082bfacdf992e2b3cd6b9bd4e8555d20384f3619d5407275e978e) e D2-REC-02_Pacote_Validado_Imutavel.zip (SHA 096c6b0a25b7dfeec575cd802b6398d3197f5cd008423afc6a873c3c624d6b50). Acesso depende da custódia autorizada; não são URLs públicos nem backup independente testado. Caminhos work/... no registro de fontes são localizadores históricos, sem persistência presumida.

## Controles atuais

- [PSD-I02](../../Kademis_Indice_Proveniencia_Pre_Gate_3_v0.1.md): 14 ABERTOS + dois encerramentos deliberados.
- [Gate 3 / BF-R02](../../Kademis_Registro_Sincronizacao_Gate_3_BF-R02_v0.1.md): Gate 3 aprovado com ressalvas não bloqueantes; 12 oportunidades propostas.
- [Consolidação A/B/C](../../d2-suf-01/README.md) e [adendo B](../../../domain/candidates/Kademis_D2_Adendo_Proveniencia_EVT-EXEC-10_v0.1.md).
- [Controle estável](../lote-02-invariantes/README.md).
- [README do projeto](../../../../README.md).

D2 PARCIAL; D3–D5/Fase 4 NÃO INICIADOS. O Gate 3 já aprovado não é reavaliado pela preservação da trilha. Publicação não torna os documentos primários nativos, nem encerra o espelho.
