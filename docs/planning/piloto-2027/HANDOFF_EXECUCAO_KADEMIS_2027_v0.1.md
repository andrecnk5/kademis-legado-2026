# Kademis — Handoff Operacional para o Projeto de Execução 2027
**ID:** KAD-RET-2027-03 | **Versão:** v0.1 | **Data:** 28/10/2026
**Origem:** planejamento delegado pelo responsável no Projeto LES-LLM. **Destino:** Projeto Kademis no ChatGPT/Work e executores de engenharia a serem instanciados.
**Natureza:** transferência de contexto e plano para **início da retomada**. Não comprova que o software, o ambiente, a migração, o teste ou o piloto já começaram.
**Documentos desta entrega:** PLANO_DIRETOR_RETOMADA_2027_2028_v0.1.md e BACKLOG_DIARIO_DIGITAL_E_CRITERIOS_v0.1.md (mesma pasta desta branch).

## 1. Mensagem de inicialização pronta para o outro projeto
> Retome o projeto Kademis com objetivo prioritário de colocar seu primeiro módulo funcional, o Diário de Classe Digital, em operação no Colégio Victorino no início do ano letivo de 2027, substituindo o papel nas rotinas cobertas e formalmente liberadas. Em 2027 o módulo será estabilizado e aperfeiçoado; a consolidação do Kademis é meta condicionada a resultados para 2028. Use como referência os três documentos em docs/planning/piloto-2027 da branch plan/retomada-diario-digital-2027 e verifique a main vigente. Reconstrua primeiro as decisões e limitações a partir dos baselines oficiais; execute imediatamente R0/B00–B01 dentro das permissões deste projeto, sem reabrir a descoberta geral. Identifique a data T0, campos e obrigações do Diário físico, regimento, usuários, autoridades, disponibilidade e dados-fonte. Defina backlog executável em fatias verticais e mantenha testes, proteção de dados e rastreabilidade proporcionais. Não trate proposta BF-R02 nem matriz 488×15 como requisitos aprovados, nem alegue Gate 4 aprovado, stack escolhida ou software existente. A autorização excepcional de planejamento do LES-LLM foi encerrada com a entrega; futuras escritas, custos, dados reais e deploy devem observar as autorizações deste projeto e suas autoridades.

## 2. Onde está o estado e qual sua autoridade
- **GitHub canônico:** https://github.com/andrecnk5/kademis
- **Branch de planejamento:** plan/retomada-diario-digital-2027, iniciada no commit eeddf76e388c4c72594a4771805720b899ed5bcb de main. Comparar com main real antes de incorporar; nunca presumir sincronização automática entre projetos.
- **Baselines Kademis** (mais importantes que este handoff): docs/playbook/Kademis_Master_Development_Playbook_v1.0.md; docs/governance/Kademis_Governanca_v1.0.md; docs/product/Kademis_Product_Charter_v0.1.md; docs/product/Kademis_Stakeholders_v0.1.md; README.md; docs/governance/continuity/README.md; docs/governance/phase-04/Instrucao_Novo_Chat_Fase_4.md.
- **Outras fontes só quando necessárias:** docs/product/Kademis_Estrategia_MultiInstituicao_v0.1.md; índice PSD-I02; relatório primário P01–P06; registros de domínio candidatos; BF-R02; dossiê Drive como evidência complementar com limites.
- **LES-LLM:** Carta de Pesquisa 02 / Base Técnica 03 / Protocolo 04 v2.0, situados no laboratório, não automaticamente copiados para o Kademis. Se não houver acesso a essas fontes no destino, o plano contém os princípios operacionais essenciais, sem prometer memória compartilhada.

### Estado que não pode ser falsificado
Gates 0–2 aprovados; Gate 3 aprovado com ressalvas não bloqueantes; Fase 4 iniciada em 24/10/2026 com estratégia proposta/em elaboração e Gate 4 **não avaliado** no corte consultado. PSD-I02 tem 14 IDs abertos e dois formalmente encerrados. BF-R02: 12 oportunidades propostas. Matriz 488×15: fonte candidata, não aprovações individuais. Não existe nova aplicação implementada/stack congelada nesse corte. SGSA-Old/Figma antigo são históricos. Não supor acesso a todos os chats ou auditoria independente concluída.

## 3. Primeiro ciclo operacional: R0/B00–B01
**Objetivo:** transformar o planejamento em uma definição real, auditável e pequena do Diário de Papel do Victorino e da equipe disponível. Não iniciar implementação às cegas.

A sequência mínima de execução:
1. Verificar repositório, HEAD, direitos e possíveis mudanças posteriores ao corte. Ler documentos-pai e fontes necessárias, sem recitar histórico inteiro.
2. Obter o **calendário oficial da escola** e fixar T0; registrar feriados/férias, janelas de docentes e responsáveis, horas efetivas disponíveis para código e testes.
3. Examinar **exemplares sanitizados** do Diário físico (campos, frequência, conteúdo, avaliações/notas, assinatura, aprovação, arquivo, emissão, alterações). Entrevistar docentes, coordenação e secretaria com exemplos concretos e mínimo de reuniões.
4. Identificar a **autoridade escolar e jurídico-regimental** capaz de declarar quando o diário digital pode substituir o papel; distinguir normas da rede estadual de regras efetivamente aplicáveis à escola particular. Não tratar "eletrônico" como dispensa automática de obrigação formal.
5. Verificar sistemas/cadastros que fornecem estudantes, docentes, turmas, calendário, ofertas e horários; definir importação única mínima, autoria e reconciliação.
6. Separar P0 fixo, P0 condicionado e P1 de acordo com B01; criar **uma jornada completa** de exemplo e seus critérios de aceite; conferir pendências e decisão vigente.
7. Recalcular datas de entrega com capacidade real e caminho crítico; se for inexequível, declarar limites e priorizar a redução de escopo não essencial, sem cortar integridade/segurança. Entregar parecer de prontidão R0.

**Saída mínima de R0:** data T0; lista da atividade que o papel hoje executa; decisão preliminar de quais campos são obrigatórios; participantes e responsabilidades; requisitos de privacidade/arquivo; mapa fonte dos dados; backlog ordenado com restrições e capacidade; primeiro incremento demonstrável. Não produzir novo dossiê se um issue ou arquivo simples bastar.

## 4. Organizar a execução pelo LES-LLM sem reestruturar tudo
- Usar uma instância coordenadora ChatGPT/Work para priorizar e verificar; manter a regra atual de um chat por fase do Kademis até decisão explícita de mudança. Responsabilidades de segurança e UX podem ser tratadas pela instância existente ou especializadas sob necessidade.
- Codex + GitHub/VS Code para implementação e testes; commits e PRs com diff/testes; Figma para fluxos quando necessário. Nunca alegar execução por ferramenta não acessada.
- O método é: **entender → recortar → implementar fatia vertical autorizada → testar → revisar risco → registrar/continuar**. Preferir P0 ponta a ponta e documentação proporcional.
- Handoff funcional só se responsabilidade mudar; continuidade só se sessão mudar. Fonte canônica = arquivos/revisões reais, não memória implícita. Um issue/PR com aceites e links pode ser suficiente.
- Verificação LES-EVAL Nível 1 por entrega (evidência, fonte, aceite, risco, esforço); Nível 2 comparativo somente se houver pergunta relevante sobre método/ferramenta.
- Não utilizar dados escolares pessoais em prompts ou PRs; para análise inicial usar amostras saneadas ou sintéticas.

## 5. Limites e permissões da transferência
Esta entrega documenta o exercício da autorização especial de **planejamento** e sua conclusão. **Não carrega autorização ilimitada para execução no projeto de destino.** O próximo executor deverá verificar permissões efetivas, aprovações e competências institucionais, e prosseguir com o que estiver autorizado no Kademis. Não alterar main, fechar pendências, aprovar Gate 4, enviar mensagens a terceiros, criar despesas ou implantar sistema apenas em nome deste handoff.

O fato de o plano estar versionado em uma branch separada não altera sozinho o status das decisões anteriores. Para torná-lo baseline no projeto de destino, seguir política de GitHub, PR/merge e controle de autoridade aplicável.

## 6. Critério de sucesso da retomada
O próximo projeto consegue responder, com fonte e evidência: **qual diário substituir, em quais turmas, por quais pessoas, até qual T0, com quais atos/registros obrigatórios, quais riscos de segurança/jurídicos, como testar, quando retirar o papel e qual incremento será implementado primeiro**. Sem essas respostas, iniciar código de forma extensa eleva risco de refazer trabalho.

## 7. Pontos que ainda não são fatos
- **Não confirmados:** calendário exato de início de aulas 2027; disponibilidade de colaboradores; custos/orçamento; modelo/regimento e conteúdo integral do diário físico; fontes e permissões sobre dados reais; infraestrutura; stack; arquitetura; detalhamento de normas aplicáveis; suficiência do prazo.
- **Ainda não executados:** qualquer etapa B00–B12 deste backlog, código, implantação, teste do produto, validação com usuários escolares, substituição do papel ou avaliação de resultados.
- **Não inferir:** que órgãos da rede estadual definem automaticamente os atos da escola privada, que portal familiar é escopo P0 ou que o caráter multi-instituição exige bancos separados por instituição.

## 8. Fechamento e retorno
Concluída esta preparação, o resultado deve ser entregue no Projeto Kademis com o link da branch, os três caminhos, HEAD verificado e a primeira tarefa R0. No fim de R0, o executor deverá devolver: escopo confirmado, obstáculos materiais, linha do tempo T0, primeiro incremento e evidências, sem solicitar reconfirmação de fatos já verificáveis. Esta transferência é suficiente para iniciar, mas não pretende substituir os documentos canônicos.
