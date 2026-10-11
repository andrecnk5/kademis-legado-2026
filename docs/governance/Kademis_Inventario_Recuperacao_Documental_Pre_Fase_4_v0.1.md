# Kademis — Inventário Inicial de Recuperação Documental Pré-Fase 4 (DOC-AUTOSUF-01 / D1)

**Estado:** INVENTÁRIO TÉCNICO INICIAL — PRODUZIDO PARA AUDITORIA; COBERTURA COMPLETA NÃO COMPROVADA  
**Data de corte:** 11/10/2026  
**Repositório:** `andrecnk5/kademis`  
**HEAD da `main` conferido:** `888fac6f49c327261772851f364ce88275a02f57`  
**Autoridade metodológica:** Playbook v1.0 e Governança v1.0 — APROVADOS  
**Alcance de D1:** inventário de `main`, índices oficiais, arquivos recuperáveis e lacunas para saneamento subsequente, sem alterar decisões ou executar escritas remotas.

> **Distinção obrigatória:** `PRESENTE NA MAIN`, `REFERENCIADO EM DOCUMENTO OFICIAL`, `LOCALIZADO NA BIBLIOTECA` e `RECUPERADO EM BYTES` são evidências diferentes. Não inferir aprovação, cobertura integral nem integridade a partir de um nome localizado.

## 1. Repositório em 11/10/2026

A consulta remota à árvore recursiva da `main` retornou `truncated=false` e **10 arquivos**. Não há `docs/domain/` nem catálogos integrais de domínio na árvore. O README declara corretamente Gate 3 aprovado com ressalvas em 10/10/2026, 14 abertos + 2 baixas e Fase 4 não iniciada.

| Caminho na main | Blob Git (SHA-1) | Classificação de uso |
|---|---|---|
| `README.md` | `65b99c7591933e8617c5a9cdf0c19b087931e279` | Estado editorial vigente; navegação incompleta |
| `docs/brand/Kademis_Diretriz_Identidade_Visual_v0.1.md` | `db9f26d7b6d24a04ff5168a2376f0993275f12c4` | Diretriz visual inicial, com propostas pendentes |
| `docs/governance/Kademis_Governanca_v0.1.md` | `de80e3b7408b9e4ed7ef259124aff12d32ce5142` | HISTÓRICO |
| `docs/governance/Kademis_Governanca_v1.0.md` | `05fe245eb975d5aaa4529f84cb29cf1ef9fcb737` | APROVADO — baseline vigente |
| `docs/governance/Kademis_Indice_Proveniencia_Pre_Gate_3_v0.1.md` | `9426de54e8dcc8a2bfae761fabf317a4941ee14f` | Índice aprovado, não catálogo literal integral |
| `docs/governance/Kademis_Registro_Sincronizacao_Gate_3_BF-R02_v0.1.md` | `b7480e4cc5a9d8874f8f648c3109fb2b1141936f` | Registro administrativo dos atos G3-DEC01 e BF-R02-DEC01 |
| `docs/playbook/Kademis_Master_Development_Playbook_v0.1.md` | `1885a7532b27dc409e8c879b9f25c5760f611e2d` | HISTÓRICO |
| `docs/playbook/Kademis_Master_Development_Playbook_v1.0.md` | `a433d8a218190aba5cffc8a90b5502a49f11a92a` | APROVADO — baseline metodológico |
| `docs/product/Kademis_Product_Charter_v0.1.md` | `89f9b29d711041aaf3e52be913ac03015e05468b` | APROVADO — baseline estratégico |
| `docs/product/Kademis_Stakeholders_v0.1.md` | `b1eb2edd8fd1bea11e84e45d20c4bb9554c23393` | APROVADO — baseline de stakeholders |

Os 11 PRs encontrados estão encerrados/mesclados, com o PR #11 integrando a sincronização documental. A existência de PR não equivale à aprovação específica de todo material de domínio que nele não esteja presente.

## 2. Áreas da Fase 3 a materializar ou comprovar

| Subfase | Evidência documental conhecida | Limite atual / ação D2–D3 |
|---|---|---|
| 3.1 — Glossário | PSD-I02 e recuperação I03-R01 dos INV-01..110 | Catálogo canônico do glossário não está na `main`; recuperar textos e aprovação individuais quando disponíveis |
| 3.2 — Processos | PSD-I02 referencia recuperação transversal | Catálogo integral e fontes primárias não estão na `main`; localizar originais |
| 3.3 — Objetos do domínio | PSD-I02 registra lacunas de cobertura e terminologia | Catálogo integral não materializado; preservar não equivalência Mantenedora/Instituição/Unidade sem deliberação |
| 3.4 — Regras | PSD-I02 aponta 52 anteriores + 36 novas = 88 enunciados finais, nos RDOC-01/01A/01B | Recuperação secundária informada; catálogo integral não publicado e histórico preliminar incompleto |
| 3.5 — Invariantes | RDOC-02 aponta INV-111..115; I03-R01 classifica INV-01..110 | Não equivale a 115 literais plenamente comprovados; ver detalhe do I03-R01 abaixo |
| 3.6 — Eventos | RDOC-03 demonstra duas absorções e um refinamento; I03-R02 intermediário reporta impedimento | Inventário primário integral de eventos não comprovado nessa fonte; localizar eventuais resultados posteriores |
| 3.7 — Estados | RDOC-04 é recorte focal; I03-R03 recuperou 34 IDs EST-* e 25 transições documentadas | Relatório primário recuperado, aguardava reconciliação no momento da sua produção; não published na `main` |
| 3.8 — Exceções | CCD-02 refere REC-3.8-01..06, 10 refinamentos e aprovação transversal | Formular matriz de textos e decisões; ressalvas literais e jurídicas devem continuar visíveis |
| 3.9 — Histórico e temporalidade | Referências no índice a seis lotes e aprovações prospectivas na continuidade | Relatório/catálogo completo não publicado na `main` nesta verificação |
| 3.10 — Pontos em descoberta | Registro de fechamento e controle PSD-I02; decisões pós-lotes em históricos | Manter exatamente 14 pendências abertas e dois encerramentos, sem aprovações retroativas |

**Conteúdo mínimo esperado pelo Playbook Fase 3:** `docs/domain/Kademis_Glossario_Dominio_v0.1.md`, `docs/domain/Kademis_Processos_Dominio_v0.1.md` e `docs/domain/Kademis_Regras_Dominio_v0.1.md`. Esses caminhos são previstos, **não existentes** na `main` verificada.

## 3. Evidências locais examinadas em D1

Três documentos recuperados em bytes a partir dos arquivos do Projeto, com SHA-256 calculado independentemente:

| Documento recuperado | SHA-256 dos bytes | Resultado sustentado e limitação |
|---|---|---|
| `KADEMIS_I03-R01_Recuperacao_Primaria_INV-01-110.md` | `e9dddfb69ec3c7293ed3263a35eb56af4ed4114daf2e2f24da974b20be7065a6` | **110/110 IDs classificados**, dos quais **63 comprovados, 45 parcialmente comprovados, 2 não comprovados**; não há 110 enunciados literais primários confirmados |
| `KADEMIS_I03-R02_Relatorio_Intermediario_Fontes_e_Lacunas_20261009.md` | `0ed495148ef4d03e18c74692ca67c1395bbc41bad19a590ec15dbec48ada5b9f` | Relatório intermediário; inventário integral primário EVT-* não disponível naquela auditoria; não declarar ausência definitiva de trabalho posterior |
| `KADEMIS_I03-R03_Relatorio_Primario_Estados_Dominio_Fase_3_7_20261010.md` | `4f05411ef4817f9c74dc8019aed1a3b4c9c4b3bbf4a0392b098340a6cadd35d3` | **34 IDs EST-*** recuperados, **12 aprovados e 22 validados**; estado de saída do relatório: aguardando validação/reconciliação pela PSD-I03 |

Os relatórios reproduzem **fotografias de seus momentos originais** (em alguns, Gate 3 não avaliado). Não sobrescrever o estado vigente: Gate 3 aprovado posteriormente em 10/10/2026.

### 3.1 Fontes derivadas referenciadas na PSD-I02

Os nomes a seguir provêm do índice oficial e devem ser conferidos individualmente no D2. **Não foi possível obter bytes autorizados de alguns desses arquivos nesta execução**, embora alguns tenham aparecido na busca de arquivos do projeto:

- `RDOC-01` — 36 regras finais novas.
- `RDOC-01A` — 50/52 textos históricos no recorte original.
- `RDOC-01B` — recuperação dos 2 textos complementares.
- `RDOC-02` — cinco invariantes `INV-111..115`.
- `RDOC-03` — duas absorções e um refinamento de eventos.
- `RDOC-04` — quatro estados documentais e `EVT-DOC-08`.
- `RDOC-05` — reconciliação transversal dos 16 IDs.
- `CCD-01` — inventário de cobertura, 19 recortes.
- `CCD-02` — reconciliação focal 3.8.
- `CCD-03` — fichas F01/F02; a preparação das fichas não representa encerramento automático.
- `CCD-04` — conferência de artefatos Pré-Gate 3.
- `PSD-01` e `PSD-I01` — planejamento e sincronização editorial anteriores.

O PSD-I02 utiliza hashes locais **abreviados**, que identificam exemplares examinados, mas não substituem a conferência dos bytes originais ou a validação atual de status.

## 4. Controle decisório e pendências

**PSD-I02 — 16 identificadores:** 14 ABERTOS + 2 COM ENCERRAMENTO FORMAL DELIBERADO. Os encerramentos são `P3.4-PEN-DOC-01` e `REC-3.8-06`; não são reabertos. Outros 14 não sofrem baixa automática.

**G3-DEC01:** Gate 3 APROVADO COM RESSALVAS NÃO BLOQUEANTES em 10/10/2026, por decisão humana registrada no documento administrativo da `main`.

**BF-R02-DEC01:** aceito documentalmente com ressalvas e encerrado administrativamente; **12 oportunidades continuam PROPOSTAS**. O documento administrativo está publicado, mas seus entregáveis C1–C3 e pareceres de origem não estão publicados integralmente na `main` verificada.

**Fase 4:** NÃO INICIADA. **Fase 5:** NÃO INICIADA. Nenhuma seleção técnica antecipada.

## 5. Lacunas priorizadas e critérios de recuperação

| ID de trabalho D1 | Prioridade | Lacuna | Critério mínimo futuro |
|---|---|---|---|
| AUT-D1-F01 | CRÍTICA | Textos finais e proveniência do catálogo de domínio não centralizados | Catálogo publicado ou referenciado de forma segura, com IDs, estados e evidências; faltantes declarados |
| AUT-D1-F02 | ALTA | Recuperação desigual de invariantes (I03-R01: 63/45/2) | Matriz literal/comprovação por ID; não preencher os 47 insuficientes por inferência |
| AUT-D1-F03 | ALTA | Cobertura integral de eventos não comprovada na fonte intermediária | Localizar fonte posterior primária ou declarar lacuna com escopo específico |
| AUT-D1-F04 | ALTA | Fontes de Gate 3 e BF-R02 citadas por hash/nome local | Verificar bytes, status, permissão e estratégia de publicação sem dados sensíveis |
| AUT-D1-F05 | MÉDIA | README não oferece navegação completa até controle do Gate 3 e domínio | Projetar índice de continuidade, mantendo fotografias históricas |
| AUT-D1-F06 | MÉDIA | Figma e eventual evidência externa sem snapshot de recuperação documentado | Inventário de versões/URLs autorizadas, exportações adequadas e integridade, sem presumir acesso |
| AUT-D1-F07 | ALTA | Backup independente ainda não definido ou testado nesta frente | Deliberar destino seguro, retenção, responsável e rotina de teste de restauração |
| AUT-D1-F08 | ALTA | Não há teste de recuperação sem chats documentado | Executar D5 após materialização/reconciliação, com avaliador independente |

**NÃO TRANSFORMAR estes achados documentais em novos IDs de domínio ou fechamentos das 14 pendências formais.** São controles da frente DOC-AUTOSUF-01.

## 6. Estado e limites do inventário

- **D1 concluído como inventário inicial**, não como auditoria exaustiva de todas as fontes históricas.
- **Sem gravação no GitHub/Figma**, sem modificação dos documentos aprovados.
- Consulta remota: árvore recursiva da `main` e leitura dos baselines/documentos de governança.
- Consulta ao acervo do Projeto: localização de diversas referências; apenas as três fontes da seção 3 foram materializadas nesta execução para conferência de bytes.
- A descoberta de fonte posterior que contradiga uma fotografia antiga exige reconciliação explícita, não apagamento retroativo.
- D2/D3 só devem promover textos à publicação após comprovação documental individual, tratamento de privacidade e revisão.

## 7. Verificações e aprovação humana futura

- [x] HEAD e árvore recursiva da `main` conferidos.
- [x] Relação de 10 arquivos e seus blobs registrada.
- [x] Falta de `docs/domain` demonstrada.
- [x] Separados status decisórios, evidências e disponibilidade física.
- [x] Preservados Gate 3, 14 + 2, BF-R02 e Fase 4 não iniciada.
- [x] Três fontes complementares recuperadas em bytes e resumidas com limites probatórios.
- [ ] Catálogos primários 3.1–3.10 integralmente recuperados e reconciliados (D2).
- [ ] Atos e evidências integrantes verificados para publicação segura (D3).
- [ ] Navegação e teste de continuidade sem chats concluídos (D4/D5).
- [ ] Deliberação humana sobre textos e atos de publicação GitHub recebida.
