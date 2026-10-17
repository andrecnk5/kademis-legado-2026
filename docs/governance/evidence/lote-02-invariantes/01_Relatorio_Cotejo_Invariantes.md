# Kademis — Auditoria focal de paridade dos invariantes com prova insuficiente

Data: 16/10/2026. Natureza: incremento documental de AUD-PAR-01/D2; não novo catálogo, fase ou ID canônico. Estado: EXECUTADO NO ESCOPO DE COTEJO; SEM NOVA PROVA NATIVA. Autor: assistente desta execução.

## 1. Escopo, autorização e base

André determinou “Siga para o próximo passo, que já esta aprovado”, após a integração validada do PR #19. Foi executada a ordem seguinte do plano incremental aprovado: confronto por família, priorizando os 47 invariantes parciais/não comprovados. A execução é leitura e produção local, sem publicação remota automática. A autorização não foi ampliada para corrigir baselines ou iniciar D3–D5/Fase 4.

Main reconferida: `b7ac4950c178cf44f9d36335f7825d08f6732fbd`. Método regido por Playbook v1.0, Governança v1.0 e GOV-CONT-01 já consultados na missão. O CSV remoto neste commit conserva o blob `003f383cd13d5a445fe9e5c24fe253ce9f9e2f2d` e SHA-256 `223c9ac144c16b4edf99a3fffc20ec1b77e4c4732ed6e3f922c597405466843e`.

## 2. Recuperação da fonte e suficiência do acesso

I03-R01 recuperado em bytes: SHA-256 `e9dddfb69ec3c7293ed3263a35eb56af4ed4114daf2e2f24da974b20be7065a6`, igual ao D1 histórico. Texto e matriz de 110 IDs foram lidos; a reconciliação posterior também foi recuperada em bytes e lida. Nomes e hashes em 04_Registro_Fontes.csv. As duas cópias-fonte deste pacote estão intactas em fontes_preservadas/ para revisão.

O relatório afirma recuperação no chat Fase 3.1 Glossário. Esta auditoria acessou o ARQUIVO do relatório, não os turnos nativos desse chat. Portanto, as classificações COMPROVADO/PARCIAL/NÃO COMPROVADO permanecem atestadas pela auditoria de origem, sem nova autenticação primária. Não foi repetida pesquisa derivada para tentar preencher textos ausentes.

## 3. Resultado do cotejo

| Verificação | Resultado |
|---|---:|
| IDs da série INV-01..110, únicos e na sequência | 110 |
| Situação documental idêntica entre fonte e candidato | 110/110 |
| Situação decisória idêntica entre fonte e candidato | 110/110 |
| Manifestação/alcance humano reportado preservado | 110/110 |
| Proposição/localizador reportado preservado, com referência de linha acrescentada | 110/110 |
| Referência da linha do relatório no candidato correta | 110/110 |
| Enunciado literal disponível no relatório e igual no candidato | 68 |
| Marcador de ausência padronizado no candidato | 42 |
| Nova mensagem nativa ou enunciado primário obtido | 0 |
| Lacuna fechada ou estado decisório alterado | 0 |

Os 68 textos disponíveis são os 63 COMPROVADOS mais cinco PARCIAIS cujo texto foi reportado, mas a prova humana está incompleta. Os 42 marcadores não são enunciados inventados: o candidato substitui fórmulas de ausência do relatório por “NÃO RECUPERADO COMO ENUNCIADO LITERAL FINAL NA AUDITORIA R01”. Não foi identificada divergência material nos campos comparados; essa conclusão é de fidelidade ao relatório, não de verdade ou suficiência primária dos invariantes.

INV-111..115 são posteriores, da Fase 3.5, e ficam fora deste cotejo. Não misturar os 68 textos disponíveis na série 01–110 com as 68 classificações COMPROVADO entre os 115 candidatos; são medidas distintas.

## 4. As 47 lacunas, separadas por peça faltante

| Grupo operacional local | IDs | Quantidade | Peça a recuperar somente quando houver acesso eficaz |
|---|---|---:|---|
| Literal individual ausente, ato/bloco reportado | INV-02..06; 18..22; 30..35; 41..44; 49..60; 62..68 | 39 | Proposição individual literal e vínculo com o bloco indicado |
| Texto reportado, validação primária vinculada ausente/incompleta | INV-08..11; INV-37 | 5 | Manifestação humana integral e objeto antecedente do bloco |
| Texto e cadeia humana insuficientes | INV-38; INV-23; INV-69 | 3 | Proposição literal, manifestação humana vinculada e contexto |
| **Total** | **45 parciais + dois não comprovados** | **47** | Sem reclassificação automática |

Esse agrupamento é uma taxonomia de trabalho desta auditoria, não novo estado canônico. Cada linha conserva a situação decisória original, inclusive VALIDADO EM BLOCO, VALIDADO HISTORICAMENTE e NÃO COMPROVADO quanto à validação primária. Os grupos não substituem as ressalvas por ID.

**INV-38 exige cautela:** a seção 5 do relatório o inclui num grupo descrito como texto primário recuperado, mas a própria linha individual explicita “NÃO PROMOVIDO A LITERAL PRIMÁRIO” e falta de fonte integral. A candidata conserva marcador de ausência. Registramos a diferença de granularidade interna sem atribuir literalidade não certificada nem corrigir o relatório aprovado. Para este cotejo, a linha individual mais restritiva orienta o agrupamento operacional; a decisão original não muda.

**Metadados:** INV-30..35 preservam os dois horários alternativos de validação; INV-62..68 não têm horário exato da proposição. Não se escolheu uma cronologia forense. INV-12 e INV-24 têm ressalvas temporais conhecidas, mas não integram as 47 linhas; não foram reabertos.

## 5. Resultado de paridade e ganho concreto

A fonte completa foi recuperada com identidade criptográfica já conhecida e sua transposição para o candidato foi conferida por ID, linha, texto/ausência, proposição, manifestação reportada e dois eixos de estado. A matriz focal permite localizar exatamente o que falta e evita pedir recuperação indiscriminada dos 110 invariantes.

Não há fundamento nesta execução para corrigir a matriz candidata publicada, promover os 47 IDs a COMPROVADO ou solicitar nova aprovação conceitual. O gargalo é prova de origem, não descompasso entre este relatório e o candidato. Uma fonte DERIVADA adicional não elimina ausência de turno nativo.

## 6. Preparação de continuidade e publicabilidade

Próximo pacote documental recomendável: preservar o relatório I03-R01 e a reconciliação como fontes derivadas, acompanhados de índice temporal e matriz focal de lacunas. Isso reduziria a dependência externa da fonte hoje citada pelo CSV. A publicação específica não foi executada; requer escopo e destino revisados, com autorização operacional delimitada e merge separado.

As fontes contêm conceitos e exemplos educacionais, temas de saúde/proteção e citações de atos do responsável; não foram identificados casos escolares individualizados neste recorte. A triagem não é liberação pública nem parecer jurídico. Manter acesso restrito e bytes originais. Não usar as regras do documento como nova orientação jurídica ou médica: são evidências históricas de domínio.

A recuperação nativa futura deve ocorrer somente se surgir acesso efetivo ao chat Fase 3.1 Glossário/exportação correspondente. O roteiro 06 define quais blocos e peças buscar. Não reenviar automaticamente solicitações aos chats nem repetir consultas a relatórios sem fato novo.

## 7. Checklists, riscos e parada

Técnico: [x] HEAD/CSV reconferidos; [x] fonte R01 com hash histórico coincidente; [x] duas fontes preservadas em bytes; [x] 110 IDs verificados; [x] 47 lacunas individualizadas; [x] situações documental/decisória separadas; [x] marcadores de ausência identificados; [x] nenhum conteúdo reconstruído; [x] manifesto/ZIP testados.

Humano: [ ] revisar o cotejo e a distinção de 39/5/3; [ ] decidir eventual publicação das fontes com proposta operacional própria; [ ] demonstrar fonte nativa nova antes de solicitar recuperação adicional; [ ] manter identidade C e outras ressalvas independentes.

Riscos residuais: confundir relatório de recuperação com exportação nativa; tratar 110 correspondências como 110 aprovações; usar normalização de marcadores para ocultar ausência; interpretar 47 lacunas como revogação de decisões. Impacto: ganho de rastreabilidade documental, sem mudança de domínio.

Gate 3 APROVADO COM RESSALVAS NÃO BLOQUEANTES; PSD-I02 14 ABERTOS + dois encerramentos deliberados; BF-R02 12 PROPOSTAS; D2 PARCIAL; C VÍNCULO HISTÓRICO NÃO COMPROVADO; D3–D5/Fase 4 NÃO INICIADOS. A auditoria focal termina no cotejo e na preparação de continuidade, sem publicação remota ou declaração de espelho concluído.
