# Kademis — Evidências documentais — Lote 01

**Natureza:** índice de custódia documental de dez registros históricos, sem promoção a baseline de domínio.  
**Data de preparação e verificação:** 16/10/2026.  
**Origem:** auditoria de paridade AUD-PAR-01 e incremento focal C/custódia, dentro de D2.  
**Base Git da preparação:** `b20db7b267fe4fed966a1fcf4be31786d87436e9`. Os documentos-fonte são fotografias de 09–10/10/2026, preservadas integralmente.

## Como interpretar os documentos

Os dez arquivos são relatórios, pareceres, handoffs e registros derivados de decisões humanas. Não constituem exportações autenticadas dos chats. Seus hashes demonstram identidade dos bytes recuperados e preservados, sem autenticar por si só mensagens nativas ou estender o alcance das aprovações.

Frases como “não publicado”, “Gate 3 não avaliado”, “README com 16 abertos” e “sincronização pendente” descrevem o momento de produção de cada fonte. Não devem substituir o estado posterior documentado pelos controles vinculados abaixo. Preservar histórico não equivale a manter o projeto no estado daquela fotografia.

| Fonte preservada | Uso documental | SHA-256 |
|---|---|---|
| [KADEMIS_BF-R02_Adendo_Handoff_Pos_Gate_3_20261010.md](KADEMIS_BF-R02_Adendo_Handoff_Pos_Gate_3_20261010.md) | Handoff e ressalvas | `12a96a9ba7b813427fe0e93a939f9dfb3dcf7296b06822df549f3aceb7e62da2` |
| [KADEMIS_BF-R02_Catalogo_Oportunidades_Funcionais_20261010.md](KADEMIS_BF-R02_Catalogo_Oportunidades_Funcionais_20261010.md) | Catálogo de 12 oportunidades PROPOSTAS | `60d6b118443e7e3e2eb9ef6c57d000953578785b7110a90878951ef59920b3f1` |
| [KADEMIS_BF-R02_DEC01_Registro_Aceite_Encerramento_Administrativo_20261010.md](KADEMIS_BF-R02_DEC01_Registro_Aceite_Encerramento_Administrativo_20261010.md) | Handoff/registro BF-R02 | `9ce40f396b9b62b6d485964d113c2c56c2052b64763f020e3e981524a17b9d74` |
| [KADEMIS_BF-R02_HOF01_Complemento_Handoff_Aceite_20261010.md](KADEMIS_BF-R02_HOF01_Complemento_Handoff_Aceite_20261010.md) | Handoff/registro BF-R02 | `839e9410de13d0525101fdcf381de7065ebdc4b43f833c3550b95157aefbc88a` |
| [KADEMIS_BF-R02_Matriz_Destinacao_Ressalvas_20261010.md](KADEMIS_BF-R02_Matriz_Destinacao_Ressalvas_20261010.md) | Destinação de 16 IDs | `c83b012f64dfb243e3dbcc5fb64c01034630556343b453fe8f6a242a4b10b9b0` |
| [KADEMIS_CCD-03_Registro_Deliberacao_F01_F02_20261009.md](KADEMIS_CCD-03_Registro_Deliberacao_F01_F02_20261009.md) | Duas baixas CCD-03 | `7e140f786bc1fb759a0e8f91119c21e3ebd14c9aaa0199a06ebcc6cc221cce36` |
| [KADEMIS_G3-AV01_Parecer_Tecnico_Avaliacao_Gate_3_20261010.md](KADEMIS_G3-AV01_Parecer_Tecnico_Avaliacao_Gate_3_20261010.md) | Parecer anterior ao Gate | `8f0bff39062e98ec10642df39349080f37d2d3141012fbfed20b735aea8937d0` |
| [KADEMIS_G3-DEC01_Registro_Deliberacao_Gate_3_20261010.md](KADEMIS_G3-DEC01_Registro_Deliberacao_Gate_3_20261010.md) | Registro do Gate 3 | `46b4a6cc1ea6a3d1ea7dd6d852383fcde35c8ec1c971236e108367fa0c03e952` |
| [KADEMIS_G3-HOF01_Handoff_Pos_Gate_3_20261010.md](KADEMIS_G3-HOF01_Handoff_Pos_Gate_3_20261010.md) | Handoff/registro BF-R02 | `903da703c3c5c07b2f1fde00743cab8e9986009205e93347057756742bb607a9` |
| [KADEMIS_PSD-I03_Termo_Aceite_Documental_I03-R05_20261010.md](KADEMIS_PSD-I03_Termo_Aceite_Documental_I03-R05_20261010.md) | Aceite documental I03-R05 | `d4271cd0464cbb8e8bd05e1061bdd8c98bd20cf6d89e460d60aeca973a20ef54` |

## Estado posterior e fontes de controle

- [README do projeto](../../../../README.md): ponto de entrada do estado integrado.
- [Playbook v1.0](../../../playbook/Kademis_Master_Development_Playbook_v1.0.md) e [Governança v1.0](../../Kademis_Governanca_v1.0.md): baselines aprovados.
- [GOV-CONT-01 v0.1](../../Kademis_Politica_Continuidade_Documental_v0.1.md): preservação de conhecimento material; não exige copiar todos os turnos.
- [PSD-I02](../../Kademis_Indice_Proveniencia_Pre_Gate_3_v0.1.md): 14 ABERTOS + dois encerramentos deliberados (`P3.4-PEN-DOC-01`, `REC-3.8-06`).
- [Registro G3/BF-R02](../../Kademis_Registro_Sincronizacao_Gate_3_BF-R02_v0.1.md): Gate 3 APROVADO COM RESSALVAS NÃO BLOQUEANTES; BF-R02 aceita documentalmente, com 12 oportunidades PROPOSTAS.
- [Consolidação D2-SUF-01 A/B/C](../../d2-suf-01/README.md): D2 PARCIAL; provas nativas e vínculo histórico C limitados.
- [Matriz candidata publicada](../../../domain/candidates/Kademis_I03-R05_Matriz_Candidata_488x15_v0.1.csv): 488 registros candidatos; não aprovação individual.

A sequência G3-AV01 → G3-DEC01 → G3-HOF01 distingue parecer anterior, decisão posterior e handoff. BF-R02 C1/C2/C3 → BF-R02-DEC01 → BF-R02-HOF01 distingue propostas e destinação do aceite documental posterior. CCD-03 registra os dois encerramentos que o PSD-I02 materializa. O termo I03-R05 registra aceite de execução candidata, sem homologar cada enunciado.

## Limites de recuperação e integridade

Nove arquivos coincidem com hashes históricos consultados: oito no registro G3/BF-R02 da main, e CCD-03 no D1 da cópia candidata recuperada. Para o termo de aceite, foram obtidas duas cópias com texto por linhas coincidente e terminação diferente (4806/4807 bytes); esta edição preserva a cópia direta de 4807 bytes, SHA-256 `d4271cd0464cbb8e8bd05e1061bdd8c98bd20cf6d89e460d60aeca973a20ef54`. A cópia embutida tem SHA-256 `3dee98cb09749db426beae23b7060f1654b96a686f432a54a848693ba43f8fcd`. Nenhuma foi normalizada para mascarar a diferença.

A cópia ZIP candidata I03-R05/D1–D7 recuperada na auditoria é compatível com uma versão anterior à integração R01. A identidade do ZIP original aceito e o vínculo criptográfico entre entrega e aceite continuam NÃO COMPROVADOS. O ZIP candidato e as três matrizes comparadas não integram este lote de dez fontes, e não receberam nova classificação decisória.

Este lote não fornece todos os antecedentes citados nos documentos. Referências a arquivos ausentes são pistas históricas, não links presumidamente disponíveis. Não constitui backup independente, teste D5, encerramento D2 nem início D3–D5/Fase 4. A custódia independente exige destino, acesso, responsável, retenção e procedimento de restauração deliberados.

Não inferir permissão de divulgação externa do simples acesso ao repositório. Dados escolares individualizados, informações protetivas e segredos não devem ser adicionados sem avaliação e autorização próprias.
