# D2-REC-04 — Relatório de reconciliação focal

**Data:** 12/10/2026  
**Estado:** artefatos candidatos locais, aguardando auditoria independente; não publicados.  
**Contrato:** DOC-AUTOSUF-01 / D2-REC-04.  
**Escopo executado:** F01–F05.

## Síntese

A matriz candidata I03-R05 foi reconciliada nos 177 registros delimitados. Foram transcritas 105 definições literais da matriz R04-A para `enunciado_final` da cópia candidata. Vinte e uma linhas parciais e uma linha explicitamente mantida em descoberta não foram promovidas. Para os 50 objetos, nomes, origem, situação e observações foram registrados no inventário auxiliar; nenhuma observação foi convertida em definição.

A fonte R04-A registra autoria/validação em linhas e se identifica como matriz primária do glossário, mas o turno nativo não está materializado no pacote. Logo, a transcrição é demonstrável em R04-A e a autenticidade primária/autoria não é reatestada por esta execução. A situação decisória da matriz candidata foi preservada; preencher texto não equivale a nova aprovação item a item.

## F01 — 177 chaves de glossário e objetos

- R04-A: 127/127 cotejadas. Nomes correspondentes: 127; definições literais com status COMPROVADO transcritas: 105; parciais mantidas sem promoção: 21; linha 127 mantida `EM DESCOBERTA` sem definição final: 1.
- R04-C: 50/50 cotejadas. Observações, origens e situações preservadas no inventário; definições formais transcritas: 0.
- `enunciado_original`: não alterado. Situação documental, decisão, abrangência, evolução e elegibilidade editorial: não alteradas.
- Delta campo a campo: 315 alterações (3 campos × 105 chaves): `enunciado_final`, `fonte_de_prova`, `nivel_de_prova`. Nenhuma alteração fora desses campos/linhas.

## F02 — EVT-EXEC-10 e EVT-PROT-04

A D2-REC-03 descreve transição/estado aprovado, sem prova do ato individual. I03-R05 apresenta “APROVADO, em complemento posterior”, ao mesmo tempo que indica abrangência de ato de aprovação da Fase 3.7 distinto das validações da Fase 3.6. I03-R03 documenta as transições associadas como aprovadas na 3.7. Sem a mensagem primária que discrimine o escopo, a divergência probatória permanece aberta. Nenhuma fonte substitui a outra.

## F03 — Lotes 3–6 da Fase 3.9

Foi recuperada no relatório de continuidade uma citação de aprovação prospectiva do Lote 3 em 09/10, mas não a mensagem nativa nem seus metadados. L4/L5 aparecem como pistas no contrato; o trecho “Validado, dê andamento” é contextual e não foi tratado como aprovação isolada. L6 aparece reservado no relatório; não foi atribuído ato. A proveniência registra estado histórico, prospectivo e grau de prova em colunas separadas. Não houve retroatividade.

## F04 — identidade do I03-R05

O SHA-256 do CSV identifica os bytes da versão candidata recebida. D1 e termo de aceite foram inspecionados, porém o ZIP original de entrega/manifesto de saída que vincule o CSV ao conjunto aceito não foi localizado. Conclusão: **VÍNCULO CRIPTOGRÁFICO NÃO COMPROVADO**; isso não invalida nem revoga o aceite registrado.

## F05 — grafias das 88 regras

Foram cotejadas 88 grafias de D2-REC-03 com as 88 chaves `REGRA` de I03-R05 por chave auxiliar casefold, mantendo os valores originais. Pareamentos: 88; colisões auxiliares: 0; grafias literalmente idênticas: 39; diferenças somente de caixa: 49. O exemplo do contrato se confirma em pares como `RD-Aval-01` / `RD-AVAL-01`; não foi escolhida grafia canônica nem alterado identificador.

## Preservação e decisões humanas

- Matriz I03-R05: 488 registros/15 campos, mesmo conjunto de chaves e ordem.
- 311 registros fora do alvo e todos os campos decisórios/documentais fora do escopo ficaram inalterados.
- D2-REC-03 permanece 334×19 e preservado; D2-REC-01 332×19 e D2-REC-02 334×19 preservados nos pacotes anexos.
- Nenhuma pendência formal foi encerrada, nenhuma decisão anterior foi revogada, e nenhum Gate foi reavaliado. Não houve alteração em GitHub, Figma, código, banco ou infraestrutura.

## Limites / decisões humanas necessárias

Consultar `D2-REC-04_Lacunas_Dependencias_Acoes_Humanas.csv`. Prioridades: fornecer atos primários e seus contextos para L3–L6 e eventos; localizar pacote/manifesto de entrega I03-R05; apresentar evidência formal de definições de OD se existir. Até então, os registros permanecem candidatos ou pendentes no limite descrito.

**Parada:** pacote documental entregue para auditoria independente. Não há prosseguimento automático.
