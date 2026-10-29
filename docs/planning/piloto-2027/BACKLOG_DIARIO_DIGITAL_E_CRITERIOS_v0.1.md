# Kademis — Backlog Inicial de Retomada e Critérios de Entrega do Diário Digital
**ID:** KAD-RET-2027-02 | **v0.1** | 28/10/2026 | **Estado:** PLANEJADO; não executado nem homologado como requisitos individuais.
**Documento-pai:** PLANO_DIRETOR_RETOMADA_2027_2028_v0.1.md. **Prazo:** T0 = início oficial do ano letivo Victorino 2027, ainda não confirmado.
**Instrução de uso:** trabalhar por fatias ponta a ponta, não por telas isoladas. Converter linhas abaixo em issues somente na quantidade necessária, após conferir fontes; nenhuma linha pressupõe código, teste ou recurso já existente.

## 1. Ordem de trabalho e impedimentos reais
**Caminho crítico:** B00 (T0/diário/autoridades/capacidade) → B01 (recorte e obrigações) → B02 (requisitos/UX/decisão técnica mínima) → B03 (fundação) → B04 (dados e contexto) → B05 (aula) + B06 (frequência) → B07 (retificação) + B08 (conferência/exportação) → B09 (segurança/restauração/verificação) → B10 (ensaio) → B11 (Go/No-Go) → operação assistida. Desenhar cortes paralelos apenas se os responsáveis efetivamente disponíveis permitirem.

| ID | Prioridade | Resultado que deve existir | Aceite observável e dependência |
|---|---|---|---|
| **B00 — Reconhecimento** | P0 imediato | Data T0, calendário da escola, docentes/turmas piloto, capacidade semanal real, instâncias de decisão e exemplares saneados do diário atual | Responsável consegue descrever campos, atos, horários e condições do papel; confirma T0 e riscos; **não inferir dados faltantes** |
| **B01 — Recorte obrigatório** | P0 imediato | Mapa papel→digital por atividade: conteúdo, frequência, notas/avaliações, assinatura, conferência, arquivamento, relatórios e demais campos exigidos | Nenhuma atividade necessária à substituição permanece fora do recorte sem alternativa documentada; documento com autoridade institucional/jurídica quando pertinente |
| **B02 — Jornada e solução mínima** | P0 | Critérios de aceite, cenários, fluxos, fonte de autoridade por ação; 1–3 ADRs essenciais de stack, persistência, modularização e segurança | Percurso docente e conferência testáveis; Gate 4/5 e demais checkpoints tratados sem aprovações fictícias; noções multi-instituição sem tenancy especulativa |
| **B03 — Fundação reproduzível** | P0 | Código inicial, ambiente de desenvolvimento/teste, CI, lint, testes, gestão de segredos, versionamento e rollback | Nova sessão/colaborador monta o ambiente pelas instruções; pipeline executado; nenhuma credencial em código/issues |
| **B04 — Contexto acadêmico mínimo** | P0 | Instituição, ano, calendário relevante, ofertas/turmas, vínculo docente inclusive substituto, estudantes/enturmações; importações conciliadas | Docente enxerga somente seus contextos autorizados; divergências de matrícula/grade detectáveis; dados fictícios primeiro |
| **B05 — Registro de aula** | P0 | Aula realizada, conteúdo ministrado, data do fato, horário/contexto e autoria; consulta por período | Registrar e consultar caso real simulado, inclusive lançamento tardio permitido; aula diferente de ato de registro |
| **B06 — Frequência** | P0 | Registro individual de frequência, estados e exceções do Victorino, consulta/pendências | Professor autorizado registra presença/ausência sem duplicação indevida; justificativa não produz abono automático; teste de substituto |
| **B07 — Retificações e histórico** | P0 | Correções de aula/frequência com motivo, autor, antes/depois, momentos e competência | Testes demonstram preservação histórica e vedação de mudanças não autorizadas |
| **B08 — Conferência e extração** | P0 | Consulta/coleta por coordenação/secretaria, relatório e exportação/fechamento exigidos | Autoridade institucional consegue conferir e recuperar registros completos para período definido; formatos e obrigações baseados em fonte própria |
| **B08a — Notas e avaliações** | P0 **SE NECESSÁRIO** | Lançamento, recuperação, fechamento e retificação nos limites do Diário físico/regimento | Se B01 demonstrar obrigação, integra caminho crítico e não pode ser postergado; decisão registrada quanto aos atos/autoridades |
| **B08b — Assinatura e formalidades** | P0 **SE NECESSÁRIO** | Assinaturas, conferência final, autenticação/verificador, arquivo e período de guarda exigidos | Autoridade institucional comprova adequação do fluxo digital ao regime aplicável antes da retirada do papel |
| **B09 — Confiabilidade e privacidade** | P0 transversal | Autenticação, autorização contextual, testes de isolamento, importação, logs, backup e RESTORE testado, observabilidade, acessibilidade, resposta a incidentes | Casos adversos reprovam acessos indevidos; restauração feita; finalidades e proteção de menores revisadas por competência apropriada |
| **B10 — Ensaio operacional** | P0 | Alpha/Beta com docentes e equipes usando cenários representativos, problemas e ações | Jornada diária completada em dispositivo real e em condições típicas; treinamento e suporte exercitados; sem falha crítica sem contenção |
| **B11 — Entrada em operação** | P0 | Preparação do T0, importação real autorizada, comunicação interna, contingência, decisão formal Go/No-Go | Conformidade e autoridade escolar confirmadas; se NO-GO, manter registro físico até remediação, sem denominar substituição concluída |
| **B12 — Estabilização** | P0 pós T0 | Suporte intensivo, correção com regressão, acompanhamento de lançamentos e revisões semanais | Incidentes e integridade observados; tratamento de causas; registro do que foi medido |

### Itens P1/roadmap preservados
Portal de família/estudante completo, substituição ClassApp, comunicações multicanal, vida escolar/documentos amplos, gestão financeira, matrícula ampla, psicopedagogia/socioemocional, gestão complexa de horários, outros contextos educacionais, comercialização externa. **Repriorizar apenas por dependência demonstrada**, não por proximidade no catálogo 488×15.

## 2. Contratos de jornada — candidatos iniciais
**J1 — Professor ministra e registra aula**
- Pré: professor exerce atuação institucional pertinente; há ano/oferta/turma e data coerentes; docente substituto identificado se for o caso.
- Ato: informar aula e conteúdo efetivamente ministrado; capturar data de ocorrência e momento de registro.
- Pós: registro consultável no contexto correto, sem apagar autoria, com trilha de correção.
- Falhas: oferta indisponível, professor sem vínculo, período inconsistente, duplicidade, conexão perdida.

**J2 — Professor lança frequência**
- Pré: estudantes vinculados ao contexto correto na data; exceções e informações de grade verificadas.
- Ato: lançar frequência; revisar pendências e informar justificativa no fluxo específico, quando existente.
- Pós: situação de cada estudante recuperável com origem e histórico; justificativa e eventual abono permanecem semanticamente distintos.
- Falhas: aluno transferido, mudança de turma, aula com professor substituto, registro fora do prazo, tentativa de acesso cruzado.

**J3 — Conferência e retificação**
- Pré: identidade e competência para retificar/conferir, período e motivo definido.
- Ato: solicitar/aplicar alteração segundo regra institucional, manter referência ao registro original; gerar consulta/relatório.
- Pós: antes/depois e cadeia de atos preservados, sem mudar silenciosamente instituição/ano/turma/autoria.
- Falhas: fechamento já realizado, disputa de edições, papel sem competência ou erro de importação.

**J4 — Notas/fechamento (condicional)**
- Só detalhar se B01 demonstrar que diário e obrigações reais incluem esses atos. Preservar distinções entre lançamento, resultado, síntese, decisão, fechamento, reabertura, retificação e reconsideração.

## 3. Pacote de testes de liberação
- T01 autorização docente/contexto e substituição;
- T02 registro de aula/temporalidade;
- T03 frequência e justificativa ≠ abono;
- T04 retificação com cadeia histórica;
- T05 mudança de turma/ano sem reatribuição silenciosa;
- T06 exportação/fechamento/reconciliação;
- T07 tentativa de leitura/escrita entre contextos e instituições;
- T08 backup e restauração com medição real e integridade;
- T09 queda de rede, erro humano e retomada;
- T10 responsividade, acessibilidade e tempo de tarefa com docentes;
- T11 notas/documentos/assinaturas conforme B01.
Todos têm resultados **NÃO EXECUTADOS** nesta data. Registrar evidência da execução real nos PRs/relatórios mínimos.

## 4. Política de decisão para prazo insuficiente
1. Manter o compromisso de valor: substituir o papel em processo efetivamente completo.
2. Remover P1 e reduzir variações não presentes no Victorino, mantendo núcleo conceitual reutilizável.
3. Não cortar autoria, integridade, isolamento, backup, revisão de exigências oficiais ou confirmação do usuário escolar.
4. Se uma obrigação do diário não couber: registrar hipótese de piloto parcial/assistido, **não alegar substituição integral** e avaliar nova data de corte.
5. Reavaliar semanalmente por horas reais disponíveis, defeitos e taxa de conclusão da fatia; nunca por porcentagens imaginadas.

## 5. Rastreabilidade mínima
Associações de origem a examinar, não requisitos homologados:
- B04 → P01/P02; OD-01..20, OD-48..50; distinções de matrícula institucional/acadêmica/enturmação.
- B05 → P03; OD-22..25; eventos de aula realizada/registro/retificação; invariantes de autoria e tempo.
- B06 → P03; OD-26..28; eventos de frequência e regras de justificativa.
- B07 → P03/P04; invariantes de integridade histórica, função/contexto, retificação.
- B08/B08a → P04/P05; regras de decisão acadêmica, emissão/fechamento, autoridade e temporalidade.
- B09 → Charter PP-05/PP-07/PP-08; Stakeholders; pendências PEN-202/PEN-206 e P06-PEN-JUR-01 quando aplicáveis.
**Fonte canônica de definição:** arquivos completos do repositório; esta associação é um índice de investigação, não substitui recuperação de cada enunciado relevante.

## 6. Regra de trabalho com IA (LES-LLM)
Cada incremento Bxx deve especificar objetivo, fonte/versão, arquivos envolvidos, ação permitida, critério de aceite, teste e retorno. Se uma issue e PR registrarem isso, não produzir contrato separado. Codex executa implementação autorizada; ChatGPT/Work orquestra e confere resultados; Figma é convocado quando a interação não puder ser validada de modo mais simples. **Uma ferramenta não deve declarar que outro ambiente foi atualizado sem leitura de retorno.**

**Controle final:** backlog pronto para execução futura; nada nesta lista constitui evidência de código criado, ambiente instalado, autoridades consultadas, dados importados ou testes executados.
