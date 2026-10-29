# Kademis — Plano Diretor de Retomada, Diário Digital 2027 e Consolidação 2028
**ID:** KAD-RET-2027-01 | **Versão:** v0.1 | **Preparado:** 28/10/2026
**Estado:** PLANEJAMENTO ELABORADO SOB AUTORIZAÇÃO EXPRESSA DO RESPONSÁVEL; não é aprovação retroativa de Gates, requisitos individuais ou arquitetura.
**Fonte operacional:** branch de planejamento plan/retomada-diario-digital-2027, originada da main eeddf76e388c4c72594a4771805720b899ed5bcb (24/10/2026). **Projeto:** Kademis. **Instituição piloto:** Colégio Victorino.
**Prazo comprometido:** início do ano letivo de 2027, cuja data exata e calendário institucional ainda precisam ser confirmados. **Horizonte:** operação/amadurecimento em 2027; consolidação visada para 2028.

## 1. Mandato e decisões estratégicas expressas
Em 28/10/2026 o responsável autorizou elaborar e publicar, quando útil, este planejamento, sem solicitações sucessivas de validação intermediária, incluindo alterações delimitadas no GitHub. A delegação excepcional encerra-se com a entrega do planejamento; **não autoriza automaticamente implantação futura, custos, acesso a dados pessoais reais ou execução de todo o software**.
Diretrizes expressas que regem o plano:
- Kademis continua sendo um **único produto multi-instituição**, desenvolvido incrementalmente.
- **O primeiro módulo funcional entregue será o Diário de Classe Digital**; ele deve substituir o diário em papel nas rotinas efetivamente cobertas no Colégio Victorino no início do ciclo letivo de 2027.
- A plataforma **não precisa ter todas as funcionalidades propostas maduras em 2027**. Durante o piloto, evoluir segurança, UX, manutenção, aderência institucional e capacidades.
- **2028 é horizonte de consolidação**, condicionado à evidência do piloto, não uma declaração antecipada de prontidão comercial.
- Aplicar LES-LLM como mecanismo efetivo de execução, continuidade e qualidade, **sem burocracia paralela**.

**Alcance:** este documento é o plano diretor; define prioridades e condições de decisão. Não modifica Charter, Stakeholders, Gate 3, status da Fase 4 ou requisitos do domínio. Recortes funcionais e marcos adiante são **plano/proposta operacional a confrontar com evidência da escola**, não alegações de requisitos já homologados.

## 2. Baseline preservado e problemas reais
1. **Baselines:** Playbook v1.0 e Governança v1.0 aprovados; Charter e Stakeholders v0.1 aprovados; Gate 3 aprovado com ressalvas não bloqueantes em 10/10/2026. Fase 4 aberta em 24/10, estratégia multi-instituição v0.1 em elaboração, Gate 4 não avaliado.
2. **Conhecimento do domínio:** processos P01–P06; matriz candidata 488×15 (127 glossário, 6 processos, 50 objetos, 88 regras, 115 invariantes, 68 eventos, 34 estados). Seus graus de comprovação documental não homologam 488 requisitos. BF-R02: 12 oportunidades **propostas**, não MVP aprovado.
3. **Pendências:** PSD-I02 tem 14 identificadores abertos e dois encerrados por decisão; não baixar nenhum por inferência. Semântica Mantenedora–Instituição–Unidade/pessoa jurídica em descoberta. Preservar ressalvas A/B/C e limites de proveniência.
4. **Tecnologia:** até o corte, não havia implementação do novo Kademis, stack, banco, tenancy física, autorização técnica, CI ou infraestrutura decididas. Figma/SGSA-Old são legado/referências, não baselines da nova aplicação.
5. **Custódia:** dossiê Drive de 24/10 preparado para auditoria externa; não equivale a auditoria independente nem censo integral de chats. **A continuidade prática deve usar fontes canônicas, não exigir reabrir todo o passado.**
6. **Problema:** no piloto, o fluxo professor → papel → consolidação manual → ClassApp → família produz intermediações. A direção de negócio validada é reduzir retrabalho e preservar autoria; substituir o ClassApp é proposta da Fase 5, **não objetivo obrigatório deste primeiro módulo**.

### Fontes de precedência
- Repositório andrecnk5/kademis, main e seus caminhos: docs/playbook/Kademis_Master_Development_Playbook_v1.0.md; docs/governance/Kademis_Governanca_v1.0.md; docs/product/Kademis_Product_Charter_v0.1.md; docs/product/Kademis_Stakeholders_v0.1.md; docs/product/Kademis_Estrategia_MultiInstituicao_v0.1.md; docs/governance/phase-04/Instrucao_Novo_Chat_Fase_4.md; docs/governance/continuity/README.md; docs/governance/Kademis_Indice_Proveniencia_Pre_Gate_3_v0.1.md; docs/domain/candidates/Kademis_I03-R05_Matriz_Candidata_488x15_v0.1.csv.
- Recuperação dos seis processos: docs/governance/evidence/lote-10-complementos-dominio/library_KADEMIS_I03-R04-B_Relatorio_Primario_Processos_Fase_3_2_20261010.md.
- Oportunidades propostas: docs/governance/evidence/lote-01/KADEMIS_BF-R02_Catalogo_Oportunidades_Funcionais_20261010.md.
- Drive Kademis / AuditoriaExterna: índice KADEMIS_Dossie_Auditoria_Externa_Indice_Geral_v0_1_20261024.md; apenas fonte complementar com limites já declarados.
- LES-LLM: Carta 02, Base Técnica 03 e Protocolo 04 v2.0; são fontes **do laboratório**, não substitutos da governança do Kademis.

## 3. Resultado final e regra do MVP
**Resultado operacional 2027:** docentes das turmas incluídas registram, consultam e retificam as informações de diário necessárias à escola sem depender do caderno/diário físico como registro primário, com acesso e supervisão adequados, rastreabilidade, segurança, recuperação de dados e emissão de evidências/relatórios exigidos. A eliminação formal do papel só ocorre depois da verificação de conformidade aplicável e do aceite institucional.

Não confundir:
- **Módulo Diário Digital** = capacidade de produto e jornada completa;
- **P01/P02/P03/P04/P05/P06** = processos de negócio que lhe fornecem conceitos e dependências;
- **infraestrutura compartilhada** = o menor suporte horizontal para o primeiro módulo e expansão futura;
- **piloto** = operação real supervisionada, não ambiente inseguro ou simulação;
- **MVP** = conjunto mínimo suficientemente confiável para uso, não produto com todos os módulos.

**Regra de corte:** entrar no P0 somente quando (a) indispensável para eliminar papel, (b) necessário à integridade/segurança/continuidade ou (c) dependência mínima para operar o diário. Os demais itens são P1/roadmap. Não declarar automaticamente tudo que existe no domínio como funcionalidade.

## 4. Escopo preliminar orientado a jornadas
### P0 — Base operacional e integridade (hipóteses prioritárias)
- Configurar a instituição piloto, ano/períodos letivos, calendário e contexto de turmas/componentes/ofertas com o **mínimo necessário**; não modelar uma gestão acadêmica universal.
- Disponibilizar relação de estudantes e vínculos acadêmicos pertinentes, docentes e suas atribuições por turma/oferta, inclusive professor substituto, com dados de origem e atualização controlada.
- Registrar **aula ocorrida**, data/contexto, autoria, conteúdo ministrado e observações estritamente pedagógicas do registro de aula, distinguindo fato de momento de lançamento.
- Registrar **frequência por estudante e contexto**, com presença/ausência e exceções efetivamente usadas na escola; justificar/receber documentos somente quando o fluxo real exigir e sem abono automático.
- Permitir **retificação atribuível**, motivo, identidade do responsável, registro anterior e novo valor; não apagar silenciosamente histórico ou origem; contemplar lançamento posterior permitido por política.
- Consultar diário por professor, turma, período; sinalizar lançamentos faltantes sem criar automaticamente punições; permitir supervisão/conferência conforme autoridade de negócio definida.
- Emitir **relatórios/exportações e meios de preservação** compatíveis com as exigências escolares verificadas (conteúdo, frequência, autoria, periodicidade e formato a decidir).
- Administração mínima: identidade/autenticação segura, autorização por contexto, cadastro/importação controlada, recuperação de acesso, auditoria pertinente e operação de suporte.

### P0 condicionado — checagem obrigatória no Victorino
- **Avaliações, notas, recuperação e fechamento**: se constarem do diário de papel, de suas obrigações ou de seu processo oficial de substituição, são escopo **necessário** (possivelmente um segundo corte do mesmo módulo), não podem ser excluídas por preferência de planejamento. Conferir Diário físico, Regimento, calendário, orientações institucionais e autoridades.
- Assinatura, conferência e fechamento do Diário; relatórios impressos/digitais, comprovantes, retificação após fechamento, preservação e exigências de arquivamento: decidir com autoridade competente e fundamento aplicável.
- Rotinas específicas de Educação Física, atividades externas, eletivas, grade variável, substituição, reposição de aula e presença com saída antecipada: incluir apenas as efetivamente necessárias, respeitando invariantes.
- Fontes iniciais de matrícula/turmas/horários e atualizações ao longo do ano: identificar sistemas responsáveis para não duplicar autorias ou criar bases divergentes.

### Não escopo inicial, salvo comprovação de dependência material
Portal público/familiar completo; substituição integral do ClassApp; mensageria multicanal; histórico escolar completo; ERP financeiro; psicopedagogia/socioemocional; scoring/diagnóstico; central de documentos genérica; toda matrícula online; gestão avançada de horários; aplicativo nativo; integração indiscriminada; implantação comercial em várias escolas. Nenhuma exclusão revoga a visão futura.

## 5. Pré-condições técnicas e de segurança inegociáveis
Antes de tratar dados pessoais reais ou declarar a substituição oficial:
- Inventário de dados e finalidades, bases legais/competências e responsabilidades institucionais, política de acesso contextual, menor privilégio, minimização, proteção especial de menores e controle de ambientes. A avaliação deve considerar LGPD, ANPD e legislação vigente **segundo sua aplicabilidade real**.
- Identidades, credenciais e segredos geridos fora do repositório; criptografia em trânsito e armazenamento conforme análise de risco; segregação testada; logs auditáveis sem vazamento; perfis técnicos derivados das competências, sem equiparar função pedagógica a RBAC.
- Proteção de edições, autoria e histórico; migração/importação validada; conciliação de contagens e amostras; procedimento de reversão.
- Backup automático **com restauração testada** e recuperação dentro de objetivos RPO/RTO **definidos para o risco**, sem inventar números; monitoramento, alertas, suporte, resposta a incidentes e contingência operacional.
- Testes automatizados dos invariantes críticos, cenários de erro e isolamento entre instituições/contextos; validação de UX com docentes, compatibilidade com dispositivos reais e acessibilidade adequada.
- **Revisão jurídico-regimental/institucional específica** antes da aposentadoria do papel. Normas sobre a rede estadual paulista são referências de contraste, **não prova de aplicabilidade automática à escola privada**. Os documentos internos devem confirmar autoridade, formatos, assinaturas, escrituração, prazos e retenção aplicáveis.
- Go/no-go registrado com autoridade escolar competente. Se faltar condição crítica: **não eliminar o papel ainda**; realizar operação assistida delimitada e tratar a lacuna como impedimento ao objetivo de substituição, não como sucesso presumido.

## 6. Calendário de execução — da retomada ao T0
**T0** = data oficial de início das aulas do Victorino em 2027, a ser confirmada por calendário institucional. O planejamento parte de **28/10/2026**; as janelas são referenciais, **não compromissos de capacidade verificada**. Ajustar ao T0 e disponibilidade real de pessoas, feriados e férias.

| Janela indicativa | Resultado concreto | Evidência de saída |
|---|---|---|
| 28/10–06/11/2026 — R0 | Retomada verificável; responsáveis e disponibilidade; calendário T0; amostra sanitizada do Diário; autoridade escolar para validação; inventário das rotinas de conteúdo, frequência, notas, assinaturas, arquivamento | Quadro escopo P0/condicional/P1 com exemplos reais; bloqueios e dependências |
| 09–20/11 — R1 | Fechar recorte operacional e regras essenciais; concluir aspectos materiais 4.1–4.9 que impedem a solução; tratar Gate 4 e transição para Fase 5 **sem aprovações implícitas**; jornadas, critérios P0, arquitetura candidata comparada | Mapa papel→digital; aceites críticos; ADRs provisórias; sequência de entregas |
| 23/11–04/12 — R2 | UX de jornadas críticas, requisitos executáveis, escolha de stack/arquitetura com critérios, fundação de repositório, ambiente de desenvolvimento, CI e testes de segurança básicos | Jornada demonstrável com dados fictícios; pipeline funcional; decisão técnica rastreável |
| 07–18/12 — R3 | Primeira fatia vertical: acesso docente, seleção de contexto, aula/conteúdo e presença, com persistência, autoria, histórico e testes | Demonstração ponta a ponta e testes de cenários positivos/negativos |
| 21/12–03/01 — capacidade a confirmar | Correções e tarefas assíncronas **somente se houver disponibilidade**; não depender desta janela para o caminho crítico | Quadro de capacidade recalculado |
| 04–15/01/2027 — R4 | Fluxos reais pendentes, retificações, substitutos, conferência, importação e relatórios; incluir avaliações/fechamento se comprovados obrigatórios | Alpha funcional com dados fictícios e revisão de usuários |
| 18–29/01 — R5 | Ensaio com cenários reais anonimizados, treinamento, migração controlada, backup/restore, observabilidade, usabilidade, validação institucional e jurídico-regimental | Relatório de prontidão; defeitos críticos fechados ou go/no-go negativo |
| T0−10 a T0−1 dias — R6 | Congelamento seletivo, validação final de turmas/usuários, teste de contingência, suporte e decisão de entrada em operação | Aceite Go/No-Go e plano de reversão |
| T0 a T0+30 dias — R7 | Operação assistida diária, monitoramento, correções rápidas, estabilidade e revisão semanal | Indicadores por processo, incidentes e decisões documentadas |
| T0+31 dias até dez/2027 — R8 | Amadurecimento, melhoria UX, redução de retrabalho, novas capacidades por valor, manutenção, evolução do LES-LLM | Ciclos funcionais encerrados, métricas e registros |
| 4º trimestre/2027 — R9 | Avaliação formal de prontidão para 2028 | Parecer de consolidação com gaps, custos, adoção e critérios alcançados |

**Controle temporal:** os marcos R2–R5 são agressivos para uma aplicação ainda sem código; **não há estimativa validada de esforço ou equipe**. Em R0 construir caminho crítico, horas disponíveis, responsáveis e plano de contingência. Se T0 for anterior à janela ou a capacidade não suportar P0, elevar imediatamente o risco e **reduzir escopo não essencial, nunca os controles de segurança ou integridade**. A existência do plano não comprova viabilidade do prazo.

## 7. Marcos de verificação — orientados a evidência
- **M0 — Prontidão para construir:** fonte canônica verificada; diário físico inventariado; lista P0 e obrigações formais; autoridades, T0 e disponibilidade identificados; riscos impeditivos explícitos.
- **M1 — Prontidão de solução:** Gate 4/5 tratados conforme governança vigente, requisitos críticos identificados, alternativas técnicas e UX críticas revisadas, fundamento de tratamento de dados definido antes de uso real.
- **M2 — Fim a fim demonstrado:** docente autenticado → turma/oferta → aula → conteúdo → frequência → persistência → consulta; erros, duplicidades e histórico testados com dados fictícios.
- **M3 — Diário operacionalmente completo:** fluxos P0 efetivamente necessários, retificações, exportações, conferência, e itens condicionais comprovados no diário real; nenhum defeito crítico conhecido sem contenção.
- **M4 — Prontidão institucional:** docentes e secretaria/direção treinados para o recorte, dados reconciliados, segregação e restauração testadas, contingência exercitada, exigências documentais analisadas e aceite do responsável competente.
- **M5 — Substituição do papel:** somente se M4 positivo e processos cobertos não dependerem do registro físico; se houver coexistência temporária, registrar **operação assistida, objetivo ainda não concluído**.
- **M6 — Consolidação 2028:** indicadores por processos, estabilidade, integridade, custos, adequação regulatória e adesão comprovados após 2027, com decisões de escopo comercial/expansão separadas.

## 8. Testes que não podem faltar
| Cenário | Expectativa verificável |
|---|---|
| Professor titular lança aula e frequência | Autor, contexto, data do fato e lançamento persistem e são consultáveis |
| Professor substituto atua em oferta autorizada | Função/contexto corretos; sem atribuir ato ao titular |
| Registro atrasado ou retificado | Preserva valor anterior, motivo, autoria, tempos e autorização aplicável |
| Justificativa/atestado de ausência | Recepção não produz abono automático sem regra/ato competente |
| Alteração de turma/oferta e transição de ano | Não migra ou reatribui silenciosamente histórico acadêmico |
| Usuário de instituição/contexto diferente | Não lê/altera informação não autorizada, inclusive por URL/API/relatórios |
| Queda de serviço e perda operacional simulada | Restauração comprovada e continuidade controlada; evitar perda silenciosa |
| Exportação/fechamento documental | Preserva conteúdo, período, autoridade, identificação e formato requerido |
| Avaliação e notas, se parte obrigatória do diário | Lançar/fechar/corrigir com histórico e competência definidas |

## 9. Organização mínima de execução com LES-LLM
**Responsável do projeto:** mantém objetivos e aceita/releases; delegou a **preparação deste plano**, não toda operação futura. **Autoridades do Victorino:** fornecem processos, regimento, calendário, condições reais, critérios pedagógicos e aceite institucional apropriado. **Executores IA/ferramentas:** implementam tarefas autorizadas e mostram resultados; não substituem autoridade de negócio, segurança ou direito.

Configuração inicial recomendada (adaptável ao trabalho; nenhuma equipe fictícia):
1. **Orquestração de produto/entrega** — uma instância de ChatGPT/Work no projeto Kademis mantém backlog curto, dependências, riscos e estado; conversa por fase existente continua até alteração formal. Nada de dezenas de chats preventivos.
2. **Engenharia e código** — Codex + repositório GitHub + VS Code, com tarefas pequenas, branch, testes executados, diff e revisão proporcional. Nunca alegar teste ou deploy sem evidência.
3. **UX/UI sob demanda** — Figma apenas para fluxos e componentes usados no corte; referência visual legada não vira protótipo aprovado.
4. **Qualidade, segurança e operação** — responsabilidades especializadas convocadas quando o risco ou artefato exigir; avaliações independentes quando houver hipótese concreta, não duplicação ritual.
5. **Google Drive** — materiais operacionais da escola e custódia sob acesso mínimo; GitHub continua canônico para código, ADRs, backlog e aceites. Não copiar dados pessoais para prompts, issues ou PRs.
6. **LES-EVAL v2.0:** nível 1 em cada entrega (escopo, evidência, testes, continuidade, esforço de coordenação); nível 2 comparativo só para dúvida prática que justifique custo. Registrar mudanças na metodologia como observação, sem declarar ganhos causais não medidos.

Contrato mínimo por tarefa: objetivo, fonte/versão, comportamento esperado, critério de aceite, riscos, permissão e destinatário do retorno; se trivial, issue/PR serve de contrato. Handoff de sessão só quando necessário, referindo commits, caminhos e pendências. Não criar documento por conversa.

## 10. Riscos e decisões de tratamento
| Risco | Severidade para prazo/uso | Ação preventiva |
|---|---|---|
| Data T0, calendário e disponibilidade desconhecidos | Crítica de planejamento | Obter calendário real, janelas de docentes, responsáveis e capacidade em R0 |
| Diário físico contém notas/assinaturas não contempladas | Crítica de escopo | Levantamento de exemplares/atos escolares e regra de inclusão P0 condicionado |
| Substituição formal do papel não admitida nas condições atuais | Crítica de operação | Revisão institucional-regimental/normativa, aceite e contingência; não declarar substituição sem prova |
| Falta código e há poucas semanas úteis | Crítica de execução | Fatias verticais; caminho crítico; excluir P1; replanejamento semanal |
| Dados pessoais de menores, autorizações e acesso | Alta | Segregação, finalidade, segurança, revisão competente antes de uso real |
| Perda de frequência/diário, inconsistências de importação | Alta | Backup/restore, reconciliação, auditabilidade e testes de falha |
| Prematura arquitetura multi-tenant complexa | Alta de custo | Núcleo conceitual e testes de isolamento; escolha física por evidência e ADR |
| Reproduzir o fluxo de papel na interface | Alta de adoção | Testar a tarefa do docente e reduzir cliques/transcrições; não digitalizar intermediações artificiais |
| Portais, ClassApp e módulos futuros absorverem equipe | Alta de prazo | Política P0/condicionado/P1; mudança por dependência material |
| Dependência de memória de chat e relatórios antigos | Média | Fontes versionadas, handoff de estado e execução por evidência |
| Disponibilidade de escola/equipe durante férias | Alta de cronograma | Não supor disponibilidade 21/12–03/01; reservar tempo de validação |

## 11. Métricas, sem inventar resultados
- **Principal:** tempo por processo digitalizado comparado ao baseline coletado antes da substituição; Charter fixa meta estratégica de redução **≥50%**, a medir por processo/público, com método e amostra acordados.
- **Adoção:** docentes/turmas de escopo que usam o diário regularmente; lacunas e registros fora do prazo.
- **Integridade:** registros esperados x existentes, divergências, retificações por motivo, rastreabilidade e recuperabilidade.
- **Confiabilidade:** incidentes, disponibilidade observada, restaurações testadas, defeitos por severidade e tempo de recuperação.
- **Experiência:** tempo/cliques nas tarefas críticas, taxa de conclusão com assistência, tickets, satisfação e barreiras de acessibilidade.
- **Economia:** hospedagem, manutenção, suporte, treinamento, custo por instituição e esforço humano.
Instrumentar o mínimo necessário, sem usar dados pessoais identificáveis em painéis do LES-LLM. Estabelecer baseline, responsáveis, frequência e limites antes da avaliação. Sem resultados presumidos.

## 12. 2027 como laboratório operacional; 2028 como saída condicionada
Durante 2027, priorizar estabilidade do Diário, correções, UX, confiabilidade, capacitação e eficiência. Abrir novas frentes (notas avançadas, documentos, família, novos módulos) apenas conforme evidência e capacidade. Não transformar o piloto em sistema descartável: preservar contratos de domínio, migrações, versionamento e testes.

**Candidatos a critérios de consolidação em 2028 (a validar com dados reais):** um ciclo letivo representativo concluído sem dependência cotidiana do papel nas rotinas cobertas; nenhuma falha crítica de integridade/segurança em aberto; backups/restores ensaiados; capacidade de suporte demonstrada; conformidade documental; indicadores de adoção e eficiência; custos sustentáveis; preparação de segundo contexto institucional **sem presumir expansão comercial autorizada**. Não declarar pronto só porque chegou janeiro de 2028.

## 13. Próxima execução no projeto Kademis
Usar o documento HANDOFF_EXECUCAO_KADEMIS_2027_v0.1.md nesta mesma pasta, seguir ordem de fontes, executar R0 e abrir backlog de fatias com datas e responsáveis reais. Prioridade de obtenção: **(1) calendário e T0, (2) amostras sanitizadas do Diário de Papel e seus campos, (3) regimento e obrigações de escrituração, (4) pessoas/capacidade, (5) dados-fonte e ambiente autorizado**. Não exigir entrevista longa: uma sessão curta orientada a exemplos reais pode resolver a maior parte da definição.

O plano foi criado isoladamente em branch, preservando a main e as decisões históricas; qualquer merge/release deve seguir o controle operacional do projeto. Ao concluir a entrega desta documentação, a autorização excepcional de planejamento se extingue.
