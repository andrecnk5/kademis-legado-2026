# KADEMIS — I03-R03
## Matriz de Transições Documentadas — Fase 3.7

**Regra:** cada linha representa uma transição estado→estado efetivamente documentada na Fase 3.7.  
Não são adicionadas arestas pela ordem numérica dos IDs, nem estados implícitos de “não existente”.  
Eventos de constituição (`EVT-*` que fazem um objeto passar a existir já em determinado estado) são citados no relatório, mas não viram arestas artificiais com origem inexistente.


| Entidade | Estado de origem | Estado de destino | Condição/ato documentado | Evento relacionado | Evidência primária | Situação decisória | Ressalva |
|---|---|---|---|---|---|---|---|
| Matrícula Acadêmica | `EST-MATAC-03` | `EST-MATAC-01` | Início válido do respectivo Ano Letivo/período acadêmico. | NÃO COMPROVADO evento próprio | S01 / H01 | APROVADO | Não depende da primeira presença do estudante. |
| Matrícula Acadêmica | `EST-MATAC-01` | `EST-MATAC-02` | Encerramento ordinário do vínculo anual ao término do Ano Letivo. | NÃO COMPROVADO evento próprio | S01 / H01 | APROVADO | Resultado acadêmico/DP não define o estado. |
| Matrícula Acadêmica | `EST-MATAC-01` | `EST-MATAC-02` | Transferência de saída efetivada. | EVT-TRAJ-06 — Transferência de Saída Efetivada | S02 / H02 | APROVADO | Pedido/agendamento/documentação não bastam; motivo/desfecho Transferência permanece separado. |
| Matrícula Acadêmica | `EST-MATAC-01` | `EST-MATAC-02` | Cancelamento efetivado, quando legitimamente aplicável. | NÃO HÁ EVT-* específico comprovado | S09 / H09 | APROVADO | Cancelamento tratado como ato/motivo de encerramento, não estado. |
| Matrícula Acadêmica | `EST-MATAC-01` | `EST-MATAC-02` | Desligamento que efetivamente encerre o vínculo acadêmico. | NÃO HÁ EVT-* específico comprovado | S09 / H09 | APROVADO | Desligamento tratado como ato/desfecho com causa preservada. |
| Matrícula Acadêmica | `EST-MATAC-01` | `EST-MATAC-04` | Suspensão/trancamento válido e reversível. | NÃO HÁ evento universal aprovado | S09 / H09 | APROVADO — CONDICIONAL | Somente onde houver fundamento jurídico/regimental. |
| Matrícula Acadêmica | `EST-MATAC-04` | `EST-MATAC-01` | Retomada/reativação válida da mesma condição suspensa. | Vínculo obrigatório com EVT-TRAJ-07 NÃO COMPROVADO | S09 / H09 | APROVADO — CONDICIONAL | REC-3.8-01/02 preservam cautela sobre retorno/reativação e base normativa. |
| Matrícula Acadêmica | `EST-MATAC-04` | `EST-MATAC-02` | Encerramento válido sem retorno à vigência. | NÃO HÁ EVT-* específico comprovado | S09 / H09 | APROVADO — CONDICIONAL | Não criar evento universal por inferência. |
| Enturmação | `EST-ENT-01` | `EST-ENT-02` | Mudança/encerramento válido da Enturmação; nova Enturmação passa a Vigente quando aplicável. | EVT-TRAJ-04 — Enturmação Alterada | S02 / H02 | APROVADO | Mudança não cria automaticamente nova Matrícula Acadêmica; histórico anterior preservado. |
| Ano Letivo | `EST-ANO-01` | `EST-ANO-02` | Início do período acadêmico do Ano Letivo. | NÃO COMPROVADO evento próprio | S03 / H03 | VALIDADO | ‘Ano Letivo Preparado’ permanece marco derivado, não estado. |
| Ano Letivo | `EST-ANO-02` | `EST-ANO-03` | Término do período acadêmico do Ano Letivo. | NÃO COMPROVADO evento próprio | S03 / H03 | VALIDADO | Correções posteriores não reabrem o Ano Letivo inteiro. |
| Oferta de Componente | `EST-OFE-01` | `EST-OFE-02` | Início do período de realização da oferta. | NÃO COMPROVADO evento próprio | S03 / H03 | VALIDADO | Oferta pode ter período próprio, inclusive semestral. |
| Oferta de Componente | `EST-OFE-02` | `EST-OFE-03` | Término do período de realização da oferta. | NÃO COMPROVADO evento próprio | S03 / H03 | VALIDADO | Preservar oferta histórica. |
| Vínculo Docente–Oferta | `EST-VDO-01` | `EST-VDO-02` | Encerramento do vínculo docente–oferta. | EVT-CICLO-10 — Vínculo Docente com Oferta Encerrado | S03 / H03 | VALIDADO | Autoria histórica permanece com o docente correspondente. |
| Vínculo Estudante–Responsável | `EST-RESP-01` | `EST-RESP-02` | Encerramento do vínculo estudante–responsável. | EVT-RESP-02 — Vínculo Estudante–Responsável Encerrado | S03 / H03 | VALIDADO | Estado do vínculo ≠ autorização de acesso. |
| Aula | `EST-AULA-01` | `EST-AULA-02` | Aula efetivamente acontece. | EVT-EXEC-01 — Aula Realizada | S04 / H04 | VALIDADO | Aula realizada ≠ registro de aula efetuado. |
| Unidade Avaliativa | `EST-PERAV-01` | `EST-PERAV-02` | Fechamento acadêmico válido da Unidade Avaliativa. | EVT-AVAL-06 — Período Avaliativo Fechado (nomenclatura histórica) | S04 / H04; termo final S08 / H08 | VALIDADO; termo canônico APROVADO | ID histórico PERAV preservado após adoção de Unidade Avaliativa como termo canônico. |
| Unidade Avaliativa | `EST-PERAV-02` | `EST-PERAV-01` | Reabertura válida da Unidade Avaliativa. | EVT-AVAL-07 — Período Avaliativo Reaberto (nomenclatura histórica) | S04 / H04; termo final S08 / H08 | VALIDADO; termo canônico APROVADO | Reaberto é transição, não estado; REC-3.8-03 preserva autoridade/temporalidade. |
| Instrumento Avaliativo | `EST-INSTAV-01` | `EST-INSTAV-02` | Aplicação efetiva do instrumento. | EVT-AVAL-01 — Instrumento Avaliativo Aplicado | S05 / H05 | VALIDADO | Cancelado/adiado/substituído não foram criados como estados. |
| Pedido de Reconsideração | `EST-RECON-01` | `EST-RECON-02` | Decisão competente sobre o pedido. | EVT-AVAL-10 — Reconsideração Decidida | S05 / H05 | VALIDADO | Deferido/indeferido são desfechos, não estados. |
| Solicitação de Documento | `EST-DOCREQ-01` | `EST-DOCREQ-02` | Encerramento/resolução válida do tratamento da solicitação. | EVT-DOC-08 — Solicitação de Documento Encerrada | S06 / H06; evento S08 / H08 | VALIDADO; evento APROVADO p/ reconciliação | Encerramento da solicitação ≠ emissão/entrega/recebimento. |
| Documento Escolar | `EST-SOLDOC-01` | `EST-SOLDOC-02` | Validação institucional aplicável ao tipo/contexto documental. | EVT-DOC-03 — Documento Escolar Validado | S06 / H06 | VALIDADO | Não é obrigatória para todo tipo documental; P3.7-PEN-DOC-02 segue aberta. |
| Situação Protetiva | `EST-PROT-01` | `EST-PROT-02` | Encerramento institucional válido do acompanhamento daquela situação específica. | EVT-PROT-04 — Situação Protetiva Encerrada | S07 / H07; evento S08 / H08 | APROVADO | Encerramento não significa risco inexistente nem encerramento de atuação externa. |
| Atuação Institucional | `EST-ATUINST-01` | `EST-ATUINST-02` | Término da atuação institucional naquela função/contexto. | NÃO HÁ EVT-* específico comprovado | S08 / H08 | APROVADO | Múltiplas atuações simultâneas podem coexistir; autoria anterior preservada. |
| Justificativa | `EST-JUST-01` | `EST-JUST-02` | Decisão formal sobre a justificativa, quando tal decisão for aplicável. | EVT-EXEC-10 — Justificativa de Ausência Decidida | S09 / H09; consolidação S10 | APROVADO | Aceita/não aceita são desfechos; ausência original não vira presença. |

## Arestas deliberadamente não criadas

- **`EST-MATAC-02 → EST-MATAC-01` não foi registrada como transição ordinária.** A Fase 3.7 validou que uma ocorrência historicamente encerrada não deve ser simplesmente reescrita como vigente; retorno posterior preserva a saída anterior. A representação temporal detalhada ficou para investigação posterior.
- **`Emitido`, `Retificado`, `Entregue`, `Reaberto`, `Reativada`, `Aprovada`, `Reprovada` e `Graduada` não foram criados como estados das entidades correspondentes.** Portanto, nenhum arco é inventado para esses rótulos.
- **Criação/constituição de objetos** (por exemplo `EVT-DOC-01`, `EVT-DOC-02`, `EVT-RESP-01`, `EVT-CICLO-09`, `EVT-AVAL-09`, `EVT-PROT-01`) não foi convertida em transição a partir de um estado fictício “inexistente”.
