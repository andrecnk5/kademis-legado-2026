# KADEMIS — D2-SUF-01/B — Relatório focal da inspeção do chat original Fase 3.8

**Objeto exclusivo:** `EVT-EXEC-10 — Justificativa de Ausência Decidida`  
**Data deste relatório:** 15/10/2026  
**Modo:** inspeção do histórico visível da presente conversa, em somente leitura  
**Status:** INSPEÇÃO FOCAL CONCLUÍDA COM RESSALVA PROBATÓRIA  
**Destino:** Governança do Projeto Kademis — D2-SUF-01/B  
**Não executado:** alterações GitHub, conteúdo canônico, PSD-I02, PR, merge, Gate, fase ou deltas.

## 1. Delimitação e força das fontes

Esta própria conversa é o chat denominado **Fase 3.8 Exceções**. Foram examinadas as mensagens efetivamente exibidas no histórico desta conversa, desde o prompt inicial da Fase 3.8 até os dois handoffs seguintes. Isso permite citar **trechos primários das mensagens aqui visíveis** (texto redigido por usuário ou assistente), mas não fornece exportação bruta da plataforma, ID interno das mensagens, timestamps individuais verificáveis ou acesso nativo integral ao chat anterior **Fase 3.7 Estados**. Assim, não será inventado um timestamp exato ou um localizador de backend.

Os dois arquivos de instrução recebidos em 15/10/2026 (`01_Nota_Verificacao_Contextual.md` e `02_Instrucao_Chat_Original_Fase_3_8.md`) e o ZIP associado **não são evidência primária das decisões de 3.7/3.8**: são apenas fonte do escopo e das ressalvas desta inspeção. Sua integridade foi conferida com os SHA-256 registrados dentro do pacote, com correspondência exata aos arquivos `.md` recebidos.

**Localizadores utilizados:** papel do autor + título/cabeçalho da mensagem + seção visível. São localizadores textuais verificáveis nesta conversa; não são IDs da plataforma. **Datas:** 08/10/2026 como contextualização do início da conversa, sem atribuição de horário individual às mensagens originais.

## 2. Achado principal

**Há evidência primária de uma afirmação humana nominal no prompt inicial da Fase 3.8:** o responsável pelo projeto enumerou o `EVT-EXEC-10 — Justificativa de Ausência Decidida` e declarou: **“Esses eventos são APROVADOS conceitualmente para reconciliação da 3.6.”** Essa declaração é um fato documental direto **desta Fase 3.8**.

**Não foi localizada, neste histórico da Fase 3.8, uma sequência de proposição original do evento nominal + aprovação humana da criação/identidade exata + resposta subsequente**. O prompt inicial **relata aprovação anterior (3.7)**; não mostra a mensagem propositiva anterior de 3.7 nem sua adjacência com o ato humano. Portanto, a confirmação explícita de status feita pelo responsável em 3.8 é **mais forte que mera citação derivada**, mas **não autentica, por si só, a cadeia originária de aprovação em 3.7**.

No Lote 2, o assistente voltou a mencionar o identificador como **evento já aprovado**, e o responsável aprovou **oito recomendações conceituais desse lote**. Como o evento não foi submetido como item novo ou alteração inequívoca do objeto de aprovação, essa aprovação **não comprova separadamente a criação/identidade exata do evento**. Não se exige votação isolada quando um evento está inequivocamente incluído em objeto aprovado; isso simplesmente não se demonstrou nesse trecho.

**Resultado probatório:**

- **Existência nominal e afirmação humana explícita de status APROVADO:** COMPROVADAS no prompt inicial desta conversa.
- **Aprovação da transição `EST-JUST-01 → EST-JUST-02`:** DECLARADA/TRANSPORTADA como aprovada na Fase 3.7; ato original da 3.7 não está nesta conversa. Mantém-se a evidência atribuída à inspeção de 3.7, sem revogá-la.
- **Aprovação primária originária do objeto específico `EVT-EXEC-10` na Fase 3.7:** **FONTE PRIMÁRIA NÃO LOCALIZADA** nesta inspeção.
- **Aprovação das oito recomendações do Lote 2 da Fase 3.8:** COMPROVADA por manifestação humana literal; **não equivale** à aprovação originária do evento.
- **Qualquer reclassificação canônica de I03-R05/PSD-I02 ou aplicação dos quatro deltas:** NÃO AUTORIZADA / NÃO EXECUTADA.

## 3. Tabela de ocorrências nominais no histórico original visível

| Ocorrência | Autor e localizador textual | Reprodução literal do trecho com a ocorrência | Classificação documental | Comprova ato originário de aprovação do evento? |
|---|---|---|---|---|
| O-01 | **Usuário**, primeira mensagem, `# 12. EVENTOS DA 3.6 — PRINCÍPIOS IMPORTANTES PARA 3.8` | “`EVT-EXEC-10 — Justificativa de Ausência Decidida`” e “Esses eventos são APROVADOS conceitualmente para reconciliação da 3.6.” | **Declaração humana explícita de status herdado da 3.7**; evidência primária da afirmação em 3.8, e não cadeia originária de 3.7 | **Não**, quanto à cadeia objeto-proposição/aprovação/resposta da 3.7 |
| O-02 | **Assistente**, resposta que analisa o **Lote 2**, seção `4. Auditoria preliminar do Lote 2` → `Eventos preservados` | “O evento aprovado `EVT-EXEC-10 — Justificativa de Ausência Decidida` permanece aplicável.” | **Premissa/recomendação envolvendo evento já assumido**, não proposta de criar/alterar | **Não** |
| O-03 | **Assistente**, relatório final de encerramento da **Fase 3.8**, seção `4.3 Os seis encaminhamentos aprovados` | “`EVT-DOC-08`, `EVT-PROT-04` e `EVT-EXEC-10`, aprovados conceitualmente na 3.7.” | **Reiteração posterior do status alegado**, sem novo ato decisório | **Não** |
| O-04 | **Assistente**, bloco `Handoff oficial de continuidade — preparação da Fase 3.9`, seção `9. Eventos de negócio` | “`EVT-EXEC-10` — Justificativa de Ausência Decidida.” | **Reprodução em handoff**, fonte derivada | **Não** |
| O-05 | **Assistente**, documento `Relatório consolidado de encerramento e transição`, seção `12.1 Eventos` | “`EVT-EXEC-10` — Justificativa de Ausência Decidida.” | **Reprodução em relatório de continuidade**, fonte derivada | **Não** |
| O-06 | **Assistente**, documento `Instrução oficial para iniciar a Fase 3.9`, seção `10.1 Eventos` | “`EVT-EXEC-10` — Justificativa de Ausência Decidida.” | **Reprodução em instrução subsequente**, fonte derivada | **Não** |

**Menção indireta correlata, sem grafia integral do ID:** a auditoria transversal apresentou, na seção `4.1 Preservação dos identificadores`, a linha `EXEC | 01–10 | 04 absorvido; 10 aprovado na 3.7`. Ela não contém o literal `EVT-EXEC-10`, mas reafirma a mesma premissa. Não fornece prova de aprovação primária originária.

As seis ocorrências nominais acima são as ocorrências **identificadas no histórico atualmente visível**. Não há garantia de exaustividade de um export técnico da conversa, ao qual esta inspeção não teve acesso.

## 4. Transcrição primária focal — O-01, declaração humana de entrada

**Autor:** usuário / responsável pelo projeto.  
**Localizador:** primeira mensagem deste chat, `# 12. EVENTOS DA 3.6 — PRINCÍPIOS IMPORTANTES PARA 3.8`.  
**Natureza:** declaração originária dentro desta conversa; relato sobre aprovação anterior (3.7).

> Complementações aprovadas durante a 3.7:
>
> - `EVT-DOC-08 — Solicitação de Documento Encerrada`;
> - `EVT-PROT-04 — Situação Protetiva Encerrada`;
> - `EVT-EXEC-10 — Justificativa de Ausência Decidida`.
>
> Esses eventos são APROVADOS conceitualmente para reconciliação da 3.6.

**Parágrafo imediatamente posterior, também visível:**

> Não existe ainda evento aprovado específico para suspensão/trancamento da Matrícula Acadêmica porque sua aplicabilidade local/regimental permanece dependente de evidência.

**Interpretação com limites:** a afirmação é nominal, humana e positiva. Não é uma proposta do assistente que espere aprovação neste ponto; é um **estado de entrada declarado pelo responsável**, referindo-se à 3.7. Não contém o texto de proposição original de `EVT-EXEC-10` na 3.7, nem o respectivo ato humano adjacente.

## 5. Transcrição primária focal — O-02 e aprovação adjacente do Lote 2

**Autor da menção:** assistente.  
**Localizador:** resposta ao usuário que aprovou o Lote 1, corpo do **Lote 2**, seção `4. Auditoria preliminar do Lote 2`.

**Bloco original com a ocorrência:**

> **Eventos preservados**
>
> Famílias `EVT-EXEC`, `EVT-AVAL` e `EVT-CONS`, sem renumeração. O evento aprovado `EVT-EXEC-10 — Justificativa de Ausência Decidida` permanece aplicável.

**Contexto:** essa resposta apresentou uma tabela com **oito recomendações sobre o Lote 2**, relativas a execução, registros, frequência, justificativas, avaliações, fechamento e reconsideração. O ID é mencionado **na seção de preservação de eventos**, não no texto da recomendação submetendo sua criação/identidade à deliberação.

**Mensagem seguinte do responsável pelo projeto (cópia literal):**

> Aprovo as oito recomendações conceituais do Lote 2 da Fase 3.8. Preserve as pendências jurídicas e regimentais e prossiga para o Lote 3 — Documentos e comunicação, com as mesmas regras.

**Resposta subsequente do assistente (trecho original):**

> As oito recomendações conceituais do **Lote 2 — Execução pedagógica, frequência e avaliação** estão formalmente aprovadas nesta continuidade da descoberta do domínio.

**Conclusão do encadeamento:** demonstrada aprovação humana das oito recomendações do **Lote 2**. Como `EVT-EXEC-10` foi **tratado como preexistente** e não proposto de modo inequívoco para criação/ratificação nominal, a cadeia não é prova autônoma da aprovação da identidade exata do evento. A existência de vínculo semântico entre recomendações sobre justificativas e o evento não resolve esse limite.

## 6. Outras menções e atos decisórios

**O-03 a O-06** são posteriores às aprovações dos lotes e à auditoria transversal; reproduzem o status transmitido pelo primeiro prompt e pela resposta do Lote 2. Têm utilidade para localização e consistência do discurso, mas não acrescentam evidência de uma aprovação original.

**Aprovações humanas observadas neste chat:**

1. “Aprovo as oito recomendações conceituais do Lote 2 da Fase 3.8. Preserve as pendências jurídicas e regimentais e prossiga para o Lote 3 — Documentos e comunicação, com as mesmas regras.”
2. “Todos aprovados” — resposta às **nove recomendações do Lote 3**.
3. “Aprovo as dez recomendações conceituais do Lote 4 da Fase 3.8. Preserve todas as pendências jurídicas, regimentais e operacionais. Prossiga para a auditoria transversal da Fase 3.8, sem avançar para a Fase 3.9 ou avaliar o Gate 3.”
4. “Aprovo a auditoria transversal da Fase 3.8, os dez refinamentos taxonômicos e os seis encaminhamentos de reconciliação, com todas as ressalvas e pendências preservadas. Autorizo o encerramento conceitual da Fase 3.8. Não inicie a Fase 3.9, a Fase 3.10, nem avalie o Gate 3. Apresente o relatório final de encerramento e o handoff, sem alterar o GitHub.”

Essas manifestações dizem respeito aos **objetos nomeados** — recomendações, refinamentos, reconciliações e encerramento da 3.8 — e não demonstram por si só o momento originário de criação/aprovação de `EVT-EXEC-10` na 3.7. A aprovação da transição `EST-JUST-01 → EST-JUST-02` pertence à Fase 3.7; sua mensagem primária não integra esta conversa.

## 7. Matriz probatória: perguntas exigidas pela inspeção

| Pergunta | Resultado estrito | Fundamento |
|---|---|---|
| (a) O usuário aprovou `EST-JUST-01 → EST-JUST-02`? | **FONTE PRIMÁRIA NÃO LOCALIZADA NESTE CHAT**; aprovação indicada por documentação da 3.7, sem reexame aqui | Ato próprio da 3.7, não recuperado diretamente na 3.8 |
| (b) O usuário aprovou a criação/identidade exata de `EVT-EXEC-10`? | **Há afirmação humana nominal de APROVADO no início da 3.8, mas a CADEIA ORIGINÁRIA NÃO FOI LOCALIZADA** | O-01 declara aprovação pretérita; O-02 a O-06 pressupõem o evento, sem submetê-lo como novo objeto |
| (c) O usuário aprovou recomendação/exceção que apenas referia o evento? | **SIM, as oito recomendações do Lote 2 foram aprovadas**, com referência do assistente ao evento na mesma resposta, mas fora do objeto nominal de criação | Bloco O-02 → ato humano literal → resposta subsequente |
| (d) O usuário aprovou outros objetos? | **SIM**: Lotes 3/4, auditoria transversal e encerramento da 3.8, cada qual dentro do respectivo escopo | Mensagens de aprovação literais nesta conversa |

Não foi encontrada neste chat uma proposição que submeta o evento nominal **para criação ou identidade** à aprovação subsequente. Por isso, não há bloco proposição-do-evento → aprovação exata → resposta a transcrever. A sequência do Lote 2 foi transcrita porque é a **mais próxima evidência de aprovação** e permite delimitar seu objeto real.

## 8. Conclusão, restrições e entrega à Governança

**Parecer:** a inspeção recuperou **texto primário do chat Fase 3.8** que comprova (i) a declaração humana nominal de aprovação herdada para `EVT-EXEC-10`, e (ii) a aprovação humana de oito recomendações do Lote 2 que **não submeteram inequivocamente a criação/identidade do evento**. Não recuperou a cadeia primária originária da Fase 3.7.

**Classificação recomendada para registro probatório (não mudança canônica):** `DECLARAÇÃO HUMANA NOMINAL DE APROVAÇÃO EM HANDOFF DE ENTRADA — COMPROVADA NA 3.8; APROVAÇÃO ORIGINÁRIA DA CRIAÇÃO/IDENTIDADE EM 3.7 — NÃO COMPROVADA PELO CHAT 3.8`.

Não declarar que o evento foi revogado ou inexistente. Não declarar, sem ressalva, que o ato original de aprovação de 3.7 foi comprovado. A Governança deverá cotejar este relatório com eventuais transcrições primárias da Fase 3.7 e com outras continuações, sem alterar retrospectivamente `I03-R05`, PSD-I02 ou os quatro deltas propostos a partir deste achado isolado.

**Ponto de parada:** inspeção focal concluída; nenhuma nova busca em outros lotes, outros chats ou sistemas é solicitada por este relatório. Não foram alterados GitHub, código, Figma, banco, Gates, fases ou decisões canônicas.

## 9. Manifesto de integridade

O arquivo de manifesto acompanhante `KADEMIS_D2_SUF_B_SHA256SUMS_20261015.txt` registra o SHA-256 **somente do relatório novo produzido nesta execução**. Os arquivos recebidos foram verificados, mas seus hashes não foram incorporados ao manifesto de artefatos criados.
