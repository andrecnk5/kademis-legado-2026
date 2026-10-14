# Kademis — Índice de recuperação documental D2 v0.1 (CANDIDATO)

**ESTADO: CANDIDATO / PUBLICADO NA `main` PELO PR #14 EM 13/10/2026. NÃO É BASELINE DE DOMÍNIO.**

**Fase:** 3 — descoberta de domínio, documentação posterior DOC-AUTOSUF-01/D2.  
**Autoridade superior:** Playbook v1.0 e Governança v1.0, ambos aprovados.  
**Fonte de conteúdo:** I03-R05 candidata reconciliada no D2-REC-04, preservada integralmente.  
**SHA-256 da fonte:** `223c9ac144c16b4edf99a3fffc20ec1b77e4c4732ed6e3f922c597405466843e`.  
**Snapshot histórico da `main` (anterior ao PR #14):** `61e6d8584b53f323a55908ec277b6c81d61a81c1` (13/10/2026). **Commit de integração:** `be4310a85124d8f7ecb0cd4cc5e5c70ebc4a9255`.  
**Estado editorial:** CANDIDATO PUBLICADO PARA CONSULTA E RASTREABILIDADE (NÃO HOMOLOGADO COMO CATÁLOGO CANÔNICO). A abertura do PR #14 e seu squash merge foram autorizados em atos humanos distintos; integração confirmada em 13/10/2026 no commit identificado acima. A publicação futura do CSV de 488 registros depende de revisão humana de privacidade e autorização específica.

## Significado das classificações

A coluna `situacao_documental` é **uma classificação reportada na fonte candidata**, não auditoria nativa individual nem prova da versão vigente de cada enunciado. `situacao_decisoria` reproduz o campo da mesma fonte, inclusive seus estados históricos e manifestações em bloco. Não converter registros classificados `COMPROVADO` em itens `APROVADOS`. O objeto exato, sua versão, o texto literal e a autorização humana precisam ser lidos em conjunto.

## Abrangência

| Família | Registros | Comprovado* | Parcial* | Não comprovado* |
|---|---:|---:|---:|---:|
| Glossário | 127 | 106 | 21 | 0 |
| Invariantes | 115 | 68 | 45 | 2 |
| Regras | 88 | 88 | 0 | 0 |
| Eventos | 68 | 68 | 0 | 0 |
| Objetos/conceitos | 50 | 50 | 0 | 0 |
| Estados | 34 | 34 | 0 | 0 |
| Processos | 6 | 4 | 2 | 0 |
| **Total** | **488** | **418** | **68** | **2** |

*Classificações documentais reportadas no CSV candidato. O resumo não comprova individualmente autoria, data, ato de validação ou completude literal.*

## Como recuperar informação

1. Consultar o catálogo candidato **somente quando disponibilizado de modo autorizado**. Seu arquivo proposto é `Kademis_I03-R05_Matriz_Candidata_488x15_v0.1.csv` e contém 488 chaves e 15 colunas, preservando a ordem e os bytes da candidata D2-REC-04.
2. Filtrar por `namespace` e `chave` (há chaves `linha 001` etc. no glossário que **não são IDs formais do domínio**).
3. Conferir `situacao_documental`, `situacao_decisoria`, `abrangencia_validacao`, `evolucao_identidade`, `ressalvas_condicionantes`, `fonte_de_prova`, `nivel_de_prova` e `elegibilidade_editorial`.
4. Se a fonte for derivada ou não disponibilizada aos responsáveis, classificar prova original como pendente. Não abrir links fictícios para arquivos locais.
5. Ler o documento de **Proveniência, limites e pendências** deste lote. Manter PSD-I02 e controle G3/BF-R02 vigentes na `main` como referências normativas e administrativas.

## Exceções que não podem ser apagadas

- Glossário: 105 definições literais recuperadas em D2-REC-04, 21 parciais e uma linha 127 em descoberta, embora seu registro seja considerado documentalmente existente/comprovado.
- Invariantes: INV-01..110 com 63 comprovados, 45 parciais, 2 não comprovados no recorte original; INV-111..115 dependem de RDOC-02.
- Objetos OD-*: 50 registros/observações **não são 50 definições formais automaticamente aprovadas**.
- Eventos: 65 associados a 3.6 + 3 originados em 3.7, com refinamentos e absorções históricas conservados. `EVT-EXEC-10` e `EVT-PROT-04` têm conflito de alcance probatório não encerrado.
- Fase 3.9: aprovação prospectiva dos L3–L6 não se confunde com execução histórica na fotografia M06; há provas primárias pendentes.

**A publicação autorizada deste índice, por si só, não significa conclusão D2 nem autossuficiência documental D5.**
