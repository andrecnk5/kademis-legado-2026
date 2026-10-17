# Kademis — Lote 03 — Fontes documentais de glossário, objetos e estados

**Natureza:** preservação de fontes já recuperadas, sem nova descoberta ou homologação de domínio.  
**Preparação:** 17/10/2026. **Base Git:** `76a608be1e0695777a588c88b7f712c2180f16e7`.  
**Data contextual das fontes:** 10/10/2026; fotografias históricas preservadas integralmente.

## Fontes preservadas

| Arquivo | Uso correto | SHA-256 |
|---|---|---|
| [KADEMIS_I03-R03_Matriz_Primaria_Estados_Fase_3_7_20261010.md](KADEMIS_I03-R03_Matriz_Primaria_Estados_Fase_3_7_20261010.md) | 34 estados concretos e ressalvas por linha | `dcbd57a81d1f33fa18d6ab2766f8395d4dc272a33a4b7a8a5e1634993a77736b` |
| [KADEMIS_I03-R03_Matriz_Transicoes_Documentadas_Fase_3_7_20261010.md](KADEMIS_I03-R03_Matriz_Transicoes_Documentadas_Fase_3_7_20261010.md) | 25 registros / 22 pares de transição; sem arestas inferidas | `c4b960b26fb7630a8f9c3295a7478a7b5a71de242d70d1743b5cd1c92dc30af9` |
| [KADEMIS_I03-R03_Relatorio_Primario_Estados_Dominio_Fase_3_7_20261010.md](KADEMIS_I03-R03_Relatorio_Primario_Estados_Dominio_Fase_3_7_20261010.md) | Relatório histórico R03; alcance probatório posteriormente qualificado pelo adendo B | `4f05411ef4817f9c74dc8019aed1a3b4c9c4b3bbf4a0392b098340a6cadd35d3` |
| [KADEMIS_I03-R04-C_Matriz_Primaria_Objetos_Dominio_Fase_3_3_20261010.md](KADEMIS_I03-R04-C_Matriz_Primaria_Objetos_Dominio_Fase_3_3_20261010.md) | 50 chaves documentais; não 50 definições aprovadas | `3b8814f3c191601ddaec4b6909faf5e4cfb2b1114c95d6eaa6dc59111a240042` |
| [Matriz_Primaria_I03-R04_Glossario.md](Matriz_Primaria_I03-R04_Glossario.md) | 127 linhas documentais; 21 parciais e questão 127 em descoberta | `9c69e0df3ec8f286efe867dca1f257657bd91bb609b3c5cd1763c6885e94da1a` |


**Proveniência física comum:** pacote `KADEMIS_DOC-AUTOSUF-01_D2-REC-04_Pacote_Preparatorio_20261012.zip`, Library ID `libfile_897d555c7a108191b7d99e802ef2cdbf` → `D2-REC-03_Pacote_Validado.zip` → `Fontes_Recuperadas_Copias/`. Esses bytes já estavam disponíveis na missão e foram extraídos para preservação. Não foi realizada nova coleta no chat original. CRC dos contêineres conferido; as cinco cópias são byte a byte idênticas aos membros.

Os três hashes de estados/transições/relatório coincidem com o D1 da cópia candidata I03-R05 examinada na auditoria; o relatório R03 também é identificado no inventário histórico D1 publicado. O hash do glossário coincide com a referência já presente no candidato publicado. Isso identifica arquivos, não autentica mensagens nativas nem a originalidade histórica do ZIP I03-R05 aceito.

## Leitura temporal e alcance decisório

“Primária” nos títulos descreve a recuperação reportada pelo autor no chat de origem. Nesta custódia, são ARQUIVOS DE RECUPERAÇÃO, não exportações autenticadas dos turnos. Presença no repositório não constitui nova aprovação de cada texto.

Afirmações de “não publicado”, “Gate 3 não avaliado”, “aguardando reconciliação” e estados antigos do README representam o momento das fontes. Para o estado posterior, usar os controles abaixo. Não corrigir nem apagar fotografias históricas silenciosamente.

### Ressalva B já conhecida — EVT-EXEC-10

O relatório R03 contém a formulação histórica “EVT-EXEC-10, aprovado na 3.7”. Essa afirmação deve ser lida com o [adendo documental posterior aprovado, PR #17](../../../domain/candidates/Kademis_D2_Adendo_Proveniencia_EVT-EXEC-10_v0.1.md).

O adendo qualifica a prova: transição aprovada em 3.7 e declaração humana nominal na abertura de 3.8; a cadeia originária exata de aprovação nominal em 3.7 continua NÃO COMPROVADA. O arquivo histórico é preservado, sem utilizá-lo para reabrir/encerrar B ou certificar a cadeia ausente. Para EVT-PROT-04 mantém-se a aprovação em bloco documentada. Não equiparar encerramento de acompanhamento ao fim do risco.

### Limitações conhecidas preservadas

- Glossário: 127 linhas não são 127 verbetes canônicos aprovados. Há 21 parciais; a linha 127 permanece EM DESCOBERTA quanto à relação Mantenedora/Instituição/pessoa jurídica.
- Objetos: OD-* são chaves documentais; OD-47 permanece retirado do inventário fundamental e historicamente preservado; autonomias OD-13/32/44/45 não são decididas pela publicação.
- Estados: 34 IDs concretos; 12 APROVADOS e 22 VALIDADOS conforme relato da fonte, sem nova autenticação nesta preservação. EST-PERAV mantém distinção entre existência validada e nomenclatura canônica posterior aprovada.
- Transições: 25 registros e 22 pares únicos são medidas diferentes; estados/eventos não são inferidos pela ordem dos IDs. Condições jurídicas/regimentais e localizadores S/H permanecem limitados ao que as fontes reportam.
- Fontes auxiliares citadas nesses arquivos não são presumidas disponíveis só pelo nome. Este lote contém as cinco fontes da tabela, não todos os seus antecedentes.

Essas ressalvas são anteriores; não constituem novas pendências e não se somam ao PSD-I02. O [controle estável e compromisso aceito](../lote-02-invariantes/README.md) determina que nova recuperação só seja proposta com peça faltante, fonte/fato novo e critério verificável. Não repetir auditorias de origem apenas por encontrar novamente as mesmas limitações.

## Controles posteriores e continuidade

- [README do projeto](../../../../README.md).
- [Playbook v1.0](../../../playbook/Kademis_Master_Development_Playbook_v1.0.md), [Governança v1.0](../../Kademis_Governanca_v1.0.md) e [GOV-CONT-01](../../Kademis_Politica_Continuidade_Documental_v0.1.md).
- [PSD-I02](../../Kademis_Indice_Proveniencia_Pre_Gate_3_v0.1.md): 14 ABERTOS + dois encerramentos deliberados.
- [Gate 3 / BF-R02](../../Kademis_Registro_Sincronizacao_Gate_3_BF-R02_v0.1.md): Gate 3 APROVADO COM RESSALVAS NÃO BLOQUEANTES; 12 oportunidades PROPOSTAS.
- [Candidata 488×15](../../../domain/candidates/Kademis_I03-R05_Matriz_Candidata_488x15_v0.1.csv), sem alteração ou promoção a baseline.
- [Consolidação A/B/C](../../d2-suf-01/README.md), [evidências lote 01](../lote-01/README.md) e [fontes/controle lote 02](../lote-02-invariantes/README.md).

D2 PARCIAL; C vínculo histórico NÃO COMPROVADO; D3–D5/Fase 4 NÃO INICIADOS. Este lote melhora a recuperação das fontes pelo repositório; não constitui backup independente, teste D5 ou conclusão do espelho. Não cria arquitetura, banco, stack, tenancy, roles, serviços ou interfaces.
