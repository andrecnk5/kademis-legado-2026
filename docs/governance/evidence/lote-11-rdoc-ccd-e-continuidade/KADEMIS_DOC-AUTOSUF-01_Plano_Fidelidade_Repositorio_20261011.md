# KADEMIS — DOC-AUTOSUF-01 / Plano controlado de fidelidade documental do repositório

**Estado:** PROPOSTO como rota de continuidade; autorizado apenas o incremento D2-REC-03. **Não é novo Gate nem revisão do Playbook.**

## Objetivo verificável

Um colaborador autorizado que receba apenas acesso ao GitHub vigente deverá identificar: baseline metodológico, decisões de domínio aprovadas, catálogos de conceitos/enunciados em estado documental claro, histórico das versões, evidências e autorizações, pontos em descoberta, 14 pendências formais abertas e 2 encerradas, e dependências externas documentadas — **sem depender da memória de chats para saber o estado vigente**. A fonte original ausente não pode ser mascarada como evidência recuperada.

## Camadas de fidelidade

| Camada | Conteúdo | Condição de verificação |
|---|---|---|
| A — Baselines | Playbook v1.0, Governança v1.0, GOV-CONT-01 v0.1 e estado Gate 3 | Aprovado, hashes e status explícitos; preservação na main |
| B — Catálogos de domínio | Glossário, processos, objetos, regras, invariantes, eventos, estados, exceções, temporalidade, pontos em descoberta | ID/chave, texto, versão, origem, relação, estado documental e decisório separados; lacunas não apagadas |
| C — Evidências e decisões | Mensagens/autoria/contexto/handoffs, proveniência, bytes/hash de anexos | Localizador e categoria de prova; arquivo ausente com dependência definida |
| D — Pendências | 14 formais abertas, 2 encerramentos deliberados, limitações documentais separadas, propostas BF-R02 | Controle por ID, motivo, responsável por decisão e dependência; nenhum fechamento inferido |
| E — Navegação e recuperação | README, trilhas entre índice e dossiês, teste de reconstrução sem chats | Auditoria independente D5 reproduz estado a partir de GitHub sem informação oral |

## Sequência de controle, sem início automático

1. **D2-REC-03 AUTORIZADO:** corrigir F01/F02/F03/F07 e buscar fontes F04/F05/F06; entregar diagnóstico e bloqueios individuais.
2. **AUD-D2-03 A AGUARDAR:** conferir bytes, deltas e o que foi/ não foi recuperado; decisão de suficiência para candidatos.
3. **Publicação focal D2 FUTURA:** apenas após autorização humana delimitada: preparar PR em Draft com catálogos suportados, status explícitos e links/índices; revisar diff e auditar separadamente antes de merge. Um catálogo parcial **pode** ser fiel se sua incompletude estiver documentada e aprovada para publicação; não afirmar que é integral.
4. **D3 NÃO INICIADO:** preservar e indexar histórico, cadeia de decisões e fontes anexas, sem novos atos ou retroatividade.
5. **D4 NÃO INICIADO:** atualizar navegação do README e índice para fontes canônicas aprovadas e links estáveis.
6. **D5 NÃO INICIADO:** ensaio independente de continuidade sem acesso a chats; relatório de divergências, lacunas e recomendações. Não concluir a iniciativa apenas pelo merge de documentos.

## Distinção normativa inegociável

**Pendências de recuperação** são entraves para a evidência documental. **Pendências formais PSD-I02** são decisões de domínio/instituição/legislação/roadmap — não desaparecem com cópia de arquivos. Uma pendência formal pode permanecer ABERTA e ainda assim o GitHub ser fiel ao estado atual, desde que o motivo, as decisões em vigor e a próxima autoridade necessária estejam explícitos.

## Critérios para decidir futuras publicações

- A fonte da decisão e a legitimidade de aprovação estão demonstradas; exceções são marcadas como PENDENTES e jamais promovidas por inferência.
- Nenhum documento histórico vira baseline vigente só porque foi encontrado.
- É possível comparar o documento candidato com a matriz original e reproduzir um delta auditável por ID.
- Os códigos/IDs originais, absorções, refinamentos e versões anteriores continuam rastreáveis.
- Diferenças entre 488 e 334 são explicadas pela natureza das famílias, não por aritmética ad hoc.
- O caminho de navegação e recuperação não depende de “acesse o chat de origem” para entender a decisão atual; o chat, quando disponível, serve como prova adicional.
- A integração remota é conduzida exclusivamente no chat Work sob contrato próprio, com PR em Draft, auditoria independente e autorização expressa de merge.
