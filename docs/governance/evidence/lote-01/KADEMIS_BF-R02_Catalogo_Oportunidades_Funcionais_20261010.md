# KADEMIS — BF-R02 / C1
## Catálogo de oportunidades funcionais — benchmarking complementar pós-Gate 3

**Data-base de consulta:** 10/10/2026. **Estado:** PROPOSTO PARA REVISÃO HUMANA; **não** é aprovação de funcionalidades, implementação, escopo, MVP nem arquitetura.  
**Autorização:** manifestação expressa “Aceito a sua recomendação, aprovo e autorizo. Realize”, limitada à BF-R02 documental.  
**Fontes internas:** PROT-BF-01, MAT-BF-01, PSD-I04/RS-01, G3-DEC01, G3-HOF01, KPG3-W01, índice PSD-I02; Playbook/Governança v1.0 da `main`.  
**Método:** E1 = documentação externa oficial atual; E2 = decisão/evidência Kademis com origem; E3 = recomendação derivada. Duas ou mais referências por tema **quando pertinentes**, sem falsa equivalência entre produtos. A referência E1 não comprova execução no Kademis ou adequação à norma brasileira.  
**Política de parada:** não consultar SGSA - Old como baseline; não rever aprovações anteriores; não escolher tecnologia, RBAC ou hierarquia jurídica; não resolver 14 pendências por imitação de fornecedores.

## 1. Leituras externas verificadas

| Fonte | Produto e comportamento documentado | URL oficial | Limites da evidência |
|---|---|---|---|
| `S01` | Infinite Campus — Enrollments (histórico de matrículas) | https://kb.infinitecampus.com/help/enrollments | Documentação operacional; inclui histórico interno/externo e datas |
| `S02` | Infinite Campus — Attendance (Student Information) | https://kb.infinitecampus.com/help/attendance-student | Documentação operacional; inclui modificador do registro e detalhes por dia |
| `S03` | Infinite Campus — Section Change Tracking (Attendance) | https://kb.infinitecampus.com/help/section-change-tracking-attendance-report | Documentação de relatório; auditabilidade condicionada à configuração |
| `S04` | PowerSchool SIS — Historical Course Grades | https://ps.powerschool-docs.com/pssis-admin/25.1/historical-course-grades | Documentação operacional; distingue notas correntes/históricas e descreve trilha de alterações |
| `S05` | PowerSchool SIS — Display Options | https://ps.powerschool-docs.com/pssis-admin/latest/display-options | Documentação operacional; publicação de notas no portal é configurável |
| `S06` | Infinite Campus — Portal Display Options | https://kb.infinitecampus.com/help/portal-display-options | Documentação operacional; disponibilidade por escola/calendário/termo |
| `S07` | Arbor — Track Parental Engagement from MAT MIS | https://support.arbor-education.com/hc/en-us/articles/13443186912157-Track-your-schools-Parental-Engagement-from-MAT-MIS | Documentação operacional; leitura in-app e entrega e-mail/SMS; recurso de certos planos e acordos |
| `S08` | Arbor — Parent Portal overview | https://support.arbor-education.com/hc/en-us/articles/212097029-A-quick-introduction-to-Arbor-for-guardians-and-parents | Documentação operacional; acompanhamento familiar e múltiplos filhos, conforme habilitação escolar |
| `S09` | CPOMS — Features | https://www.cpoms.co.uk/features/ | Descrição oficial de fornecedor; cronologia de salvaguarda e colaboração; requer validação independente |
| `S10` | Infinite Campus — Forms | https://kb.infinitecampus.com/help/forms | Documentação operacional; estados de formulário, publicação controlada e solicitação de assinatura |
| `S11` | Infinite Campus — Absence Request (Campus Parent) | https://kb.infinitecampus.com/help/absence-request-campus-parent | Documentação operacional; solicitação, verificação e processamento distintos |
| `S12` | Infinite Campus — Self Service Options | https://kb.infinitecampus.com/help/self-service | Documentação operacional; solicitações de atualização revisadas antes da efetivação |
| `S13` | Infinite Campus — User Account | https://kb.infinitecampus.com/help/user-account | Documentação operacional; delimitação de acesso por escola/ano/calendário, não modelo do Kademis |
| `S14` | PowerSchool SIS — Permanently Store Grades | https://ps.powerschool-docs.com/pssis-admin/latest/permanently-store-grades | Documentação operacional; nota final historificada com efeito em registros oficiais |
| `S15` | Infinite Campus — Campus Parent Portal | https://kb.infinitecampus.com/help/campus-parent-portal | Documentação operacional; navegação por estudantes e vínculos |

**Caveat de comparabilidade:** Infinite Campus e PowerSchool são SIS amplos norte-americanos, Arbor é MIS britânico e CPOMS é solução especializada de proteção; configurações, planos e jurisdição variam. A documentação pública não comprova resultados em produção, usabilidade real, conformidade com a LGPD ou superioridade em métricas. Referências com fonte única permanecem explicitamente limitadas. A pesquisa histórica da Fase 3.9 foi registrada em relatório interno, mas suas URLs primárias não foram recuperadas nesta execução; não lhe atribuí estas buscas atuais retroativamente.

## 2. Fichas de oportunidades — apenas candidaturas funcionais

### BF-R02-01 — Organização institucional e contexto por escola

- **Núcleo e origem Kademis (E2):** N1 — Instituição, unidade e responsáveis pela operação; KPG3-W01 não reconciliou equivalências jurídicas.
- **Fontes externas (E1):** `S06`, `S07`, `S13`.
- **Prática verificada:** Infinite Campus delimita visualização/ação por escola e calendário; Arbor permite visão de grupo condicionada a plano/acordo.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: preservar contexto institucional visível e critérios de configuração por instituição; só a Fase 4 poderá classificar core/variabilidade.
- **Riscos/limites:** Não define Mantenedora, pessoa jurídica, tenant, herança de permissões nem hierarquia de entidades.
- **Destino metodológico:** Fase 4 (condicionada a autorização separada); dependência institucional/jurídica em descoberta.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-02 — Trajetória e vínculo acadêmico historificado

- **Núcleo e origem Kademis (E2):** N2/N7 — REC-3.8-01; REC-3.8-02; registros de matrícula/retorno/trancamento.
- **Fontes externas (E1):** `S01`, `S04`.
- **Prática verificada:** Infinite Campus mostra matrículas internas/externas e datas de início/fim; PowerSchool registra histórico de escolas e notas sem identificar regras brasileiras de retorno.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: distinguir vínculo atual, fatos pretéritos, regularizações e motivos; preservar proveniência.
- **Riscos/limites:** Não validar automaticamente retorno, reativação, suspensão ou trancamento; regimento prevalece.
- **Destino metodológico:** Fase 4: dependências institucionais; detalhamento de capacidades Fase 5.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-03 — Frequência com retificação atribuível

- **Núcleo e origem Kademis (E2):** N3/N7 — Justificativa ≠ abono, lançamento ≠ correção, autoria e temporalidade.
- **Fontes externas (E1):** `S02`, `S03`.
- **Prática verificada:** Infinite Campus evidencia autor de alteração e relatório condicionado à auditoria habilitada.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: exigir rastreabilidade conceitual da retificação e distinguir justificativa de efeito; revisar legibilidade UX da sequência.
- **Riscos/limites:** Não importar códigos de presença ou critérios estaduais norte-americanos; o recurso de log em fornecedor é configurável.
- **Destino metodológico:** Preservar princípio de domínio já validado; capacidade/UX à Fase 5.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-04 — Notas correntes, fechamento e correção histórica

- **Núcleo e origem Kademis (E2):** N4/N7 — REC-3.8-03; P04-PEN-01; autorização de reabertura; histórico de resultado.
- **Fontes externas (E1):** `S04`, `S14`, `S05`.
- **Prática verificada:** PowerSchool separa corrente/histórica; armazenagem final altera histórico e permite registro de mudanças sob acesso específico; controla exibição em portal.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: separar lançamento, fechamento, retificação, publicação e efeito; valorizar registros de decisão.
- **Riscos/limites:** Não adotar janela de 30 dias, regras de GPA, escolaridade dos EUA nem autoridade do fornecedor; segunda chamada/cobrança requer regimento.
- **Destino metodológico:** Regra conceitual já condicionada; parâmetros em Fase 4 e funcionalidades na Fase 5.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-05 — Portal familiar contextual e acessível

- **Núcleo e origem Kademis (E2):** N6 — PEN-205; interface de estudantes e responsáveis; sem ClassApp como baseline.
- **Fontes externas (E1):** `S08`, `S15`, `S06`.
- **Prática verificada:** Arbor mostra painel de responsáveis, tarefas e troca entre filhos; Infinite Campus restringe exibição por contexto e configurações.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: acesso claro, responsivo, com contexto da criança/instituição e apresentação mínima necessária; avaliação formal de acessibilidade.
- **Riscos/limites:** Sem decisão de construir app, substituir ClassApp, lançar MVP, nem autorização de divulgar dado sensível.
- **Destino metodológico:** Fase 5 — produto/escopo/roadmap; Fase 4 — variação institucional.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-06 — Comunicações com estados verificáveis

- **Núcleo e origem Kademis (E2):** N6/N7 — REC-3.8-04; separar produção, envio, entrega, visualização e ciência.
- **Fontes externas (E1):** `S07`, `S15`.
- **Prática verificada:** Arbor mede mensagens in-app lidas e e-mails/SMS entregues, em estatísticas distintas; Infinite Campus oferece caixa de mensagens/avisos em portal.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: distinguir estados e apresentar incertezas operacionais; registros verificáveis por canal.
- **Riscos/limites:** **NÃO ADOTAR** equivalência leitura = ciência jurídica, nem prova de entrega só por emissão; painéis não são prova individual de obrigação legal.
- **Destino metodológico:** Conceitos já validados; integração/canais UX Fase 5; ciência formal sob autoridade.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-07 — Documentos, conferência e manifestação explícita

- **Núcleo e origem Kademis (E2):** N5/N6 — P3.7-PEN-DOC-02; papel de quem confere, assina, recebe ou aceita.
- **Fontes externas (E1):** `S10`, `S12`.
- **Prática verificada:** Infinite Campus diferencia rascunho, documento travado, publicado, solicitação de assinatura e atualização revisada.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: manter natureza documental, versão, conferência por tipo, quem praticou ato e seu efeito.
- **Riscos/limites:** Assinatura digital do mercado não prova validade jurídica de documento específico nem autoridade para assiná-lo no Kademis.
- **Destino metodológico:** Regimento/autoridade documental; Fase 5 decide canais/capacidade.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-08 — Solicitações familiares sem efeito automático

- **Núcleo e origem Kademis (E2):** N2/N3/N6 — Ausência solicitada ≠ ausência registrada; justificativa ≠ abono; PEN-204.
- **Fontes externas (E1):** `S11`, `S12`.
- **Prática verificada:** Infinite Campus diferencia solicitação de ausência, verificação de responsáveis e processamento; atualizações cadastrais podem depender de revisão.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: pedido, evidência, triagem e decisão como atos separados; promover transparência de status UX.
- **Riscos/limites:** Não importar autoprocessamento de solicitação nem conceder abono automático com upload de documento.
- **Destino metodológico:** Instituição decide processo real, Fase 5 decide jornada digital.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-09 — Proteção e cronologia de acompanhamento

- **Núcleo e origem Kademis (E2):** N6/N7 — REC-3.8-05; P06-PEN-JUR-01; PEN-203; PEN-206.
- **Fontes externas (E1):** `S09`, `S07`.
- **Prática verificada:** CPOMS descreve cronologia contextual; Arbor fornece comparação indireta de comunicação, não mecanismo especializado de proteção. Só CPOMS é fonte especializada primária para cronologia protetiva neste recorte.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: preservar contexto, finalidade, intervenção humana e continuidade histórica sem score ou diagnóstico automático.
- **Riscos/limites:** Não replicar compartilhamento britânico, categorias clínicas, avaliação automática de risco ou acessos sensíveis sem LGPD/autoridade/protocolo local.
- **Destino metodológico:** Obrigatória validação jurídico-institucional e especializada antes de regra operacional.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-10 — Competências por ato sem converter perfis em RBAC

- **Núcleo e origem Kademis (E2):** N1/N6 — PEN-201; PEN-202; PEN-204; autoridade que registra, confere, decide e comunica.
- **Fontes externas (E1):** `S13`, `S10`.
- **Prática verificada:** Infinite Campus descreve acessos escolares/calendários e permissões distintas por funções de ferramenta; formulário separa solicitantes e participantes.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: evidenciar legitimidade por ato, contexto e responsabilidade separada.
- **Riscos/limites:** Não extrair roles técnicas ou relações controlador/operador da permissão de concorrente; também não homologar matrizes jurídicas.
- **Destino metodológico:** Autoridades por ato na descoberta institucional pertinente; RBAC técnico em fase própria.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-11 — Publicação escolar configurada por contexto

- **Núcleo e origem Kademis (E2):** N1/N4/N5/N6 — Visibilidade temporal e documental e separação de fatos de publicação.
- **Fontes externas (E1):** `S05`, `S06`, `S10`.
- **Prática verificada:** PowerSchool permite configurar a visibilidade de notas no portal; Infinite Campus condiciona exibição a escola/calendário/termo, e publicação de certos formulários.
- **Recomendação (E3):** **ADAPTAR (PROPOSTO)**: distinguir existência do registro, elegibilidade para publicar, disponibilização e visualização; considerar acessibilidade.
- **Riscos/limites:** Não fixar prazos ou regras de retenção/visibilidade dos fornecedores; dados sensíveis demandam salvaguardas adicionais.
- **Destino metodológico:** Fase 4 — variabilidade; Fase 5 — critérios de experiência/capacidade.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

### BF-R02-12 — Não importação de regras exógenas e automações indevidas

- **Núcleo e origem Kademis (E2):** N2/N4/N6 — REC-3.8-02; P04-PEN-01; P06-PEN-JUR-01; PEN-206.
- **Fontes externas (E1):** `S14`, `S09`.
- **Prática verificada:** PowerSchool opera janelas e transcrições próprias; CPOMS opera em marco britânico; nenhuma fonte oferece validação normativa brasileira.
- **Recomendação (E3):** **NÃO ADOTAR (PROPOSTO)**: janela fixa do fornecedor, cobrança automática, assinatura como ciência genérica, diagnóstico/ranking emocional e compartilhamento externo por simples presença no software.
- **Riscos/limites:** Controles exigem requisitos/regimento/autoridade e avaliação LGPD; não é uma rejeição de qualquer capacidade futura.
- **Destino metodológico:** Pendências continuam abertas até decisão própria e base nacional/local.
- **Validação humana da proposta:** PENDENTE. **Não** é requisito aprovado, nem plano de implementação.

## 3. Salvaguardas transversais

- **Privacidade por finalidade e proteção de menores:** nenhum benchmarking dispensa autoridade/legalidade brasileira, avaliações necessárias e restrição de visualização; separação entre contexto pedagógico e dados de saúde/socioemocionais.
- **Acessibilidade como requisito de produto:** exigir critérios verificáveis de navegação, legibilidade, uso móvel, teclado e tecnologia assistiva na fase apropriada; não presumir que os produtos consultados sejam acessíveis sem teste.
- **Multi-instituição:** núcleo comum não se confunde com política, regimento, branding, configuração de portal ou personalidade jurídica.
- **Rastreabilidade:** nunca apagar origem, autor, decisão, motivo, data do fato, data de registro ou efeitos por uma simples correção.
- **Decisões já aprovadas:** manter o núcleo semântico; recomendações complementares não o substituem e não geram novas regras universais.

**Resultado C1:** 12 fichas propostas, sem ranking de fornecedores, sem estimativa de mercado, sem definição de MVP/escopo/stack. A completude refere-se ao recorte BF-R02, não à eliminação de todas as ressalvas de domínio.
