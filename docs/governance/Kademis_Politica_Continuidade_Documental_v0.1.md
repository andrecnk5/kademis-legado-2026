# Kademis — Política de Continuidade Autônoma e Preservação do Conhecimento v0.1

**Identificador da diretriz:** GOV-CONT-01  
**Versão do artefato:** 0.1 — proposta de formalização documental  
**Estado decisório:** PRINCÍPIO E ESTRATÉGIAS A–F APROVADOS PELO RESPONSÁVEL no chat de continuidade, em 11/10/2026  
**Estado editorial:** PROPOSTO PARA REVISÃO, MATERIALIZAÇÃO E APROVAÇÃO DO TEXTO NORMATIVO; NÃO PUBLICADO  
**Produto:** Kademis  
**Repositório:** `andrecnk5/kademis`  
**Caminho candidato:** `docs/governance/Kademis_Politica_Continuidade_Documental_v0.1.md`  
**Autoridade superior:** Master Development Playbook v1.0 e Governança v1.0 — APROVADOS  
**Data do despacho conceitual:** 11/10/2026  
**Fase 4:** NÃO INICIADA

> A aprovação humana do princípio não equivale à aprovação retroativa das fontes derivadas, a autorização irrestrita de GitHub, à atualização automática dos baselines ou ao início da Fase 4. Esta minuta traduz a diretriz aprovada para um procedimento verificável e requer revisão antes da integração.

## 1. Objetivo e regra fundamental

O GitHub deverá possibilitar que um responsável autorizado, sem acesso às conversas originais do ChatGPT, reconstrua o estado do Kademis e continue o projeto a partir das evidências publicadas, sem presumir decisões, alterar baselines ou depender de memória conversacional.

**GOV-CONT-01 — Continuidade Autônoma:** em toda fase, subfase ou incremento, o conhecimento essencial produzido, suas evidências suficientes, sua proveniência, seu estado decisório e o próximo passo permitido devem permanecer recuperáveis a partir do repositório oficial e de fontes externas identificadas e acessíveis aos responsáveis autorizados. A perda integral dos chats não poderá interromper a continuidade segura do projeto.

O repositório é a **porta de entrada documental**, não o único sistema de armazenamento físico: poderá remeter a registros controlados externos cuja identidade, versão, acesso, integridade e procedimento de recuperação estejam documentados. Ausência de acesso a uma fonte essencial deve constar como lacuna, não como evidência implicitamente suficiente.

## 2. Escopo permanente

A regra abrange, desde o momento em que forem produzidos e até sua substituição controlada: estratégia, stakeholders, conceitos e catálogos de domínio, requisitos, decisões de UX/UI, arquitetura, tecnologias, código, testes, infraestrutura, operação, riscos, exceções, pendências, autorizações, handoffs e evidências necessárias. Não cria artefatos artificiais para fases futuras.

**Não se exige copiar todos os turnos dos chats.** Exige-se preservar todo conteúdo material para reconstrução verificável e rastreável, distinguindo fonte primária, relato derivado, interpretação e decisão.

## 3. Invariantes de governança da continuidade

1. **Rastreabilidade:** cada item material deve informar ID, texto vigente ou estado de recuperação, origem, autoria comprovada, data quando comprovada, decisão humana, dependências e ressalvas.
2. **Autoridade por categoria:** baselines, decisões, históricos, fontes externas e dados técnicos preservam sua precedência no Playbook e na Governança v1.0.
3. **Existência ≠ aprovação:** a presença no repositório não homologa conteúdo. Identificar `EXISTENTE`, `HISTÓRICO`, `VALIDADO`, `APROVADO`, `PROPOSTO`, `PENDENTE`, `NÃO COMPROVADO` e estados correlatos conforme a fonte.
4. **Histórico imutável no sentido documental:** correções geram nova versão ou revisão rastreável; decisões antigas e IDs absorvidos não desaparecem nem são renumerados.
5. **Mínimo de exposição:** não publicar credenciais, segredos, dados pessoais escolares identificáveis, informações sensíveis ou arquivos externos sem permissões apropriadas; preferir sínteses verificáveis, anonimização e repositórios seguros para evidência restrita.
6. **Escopo de autorização:** aprovação conceitual, aprovação textual, autorização de branch/commit/push/PR e autorização de merge são atos distintos. O processo de publicação mantém as regras vigentes e aprovação humana aplicável.
7. **Verificabilidade:** artefatos publicados devem ser confirmados no remoto por caminho, commit, blob, conteúdo, integridade e links.
8. **Ausência declarada:** algo não localizado não pode ser preenchido por inferência nem promovido a regra aprovada.

## 4. Procedimento de sincronização por fase, subfase e incremento

**Antes do trabalho:** conferir o HEAD da `main`, README, Playbook, Governança, baselines aplicáveis, índice de decisões, pendências e autorização. Registrar snapshot de origem e escopo.

**Durante o trabalho:** manter minuta cumulativa com decisões e evidências; atualizar, à medida que surgirem, textos, IDs, autores, restrições, justificativas, riscos e impactos. Distinguir material documental provisório de material decisório aprovado. Propor sincronizações incrementais por PR após revisão.

**Ao validar uma decisão:** registrar o enunciado exato validado/aprovado, objeto e limites do ato humano; preparar artefato legível e verificar autorização operacional separada antes de escrever no GitHub.

**Na publicação:** comparar base e HEAD, aplicar somente o escopo autorizado, executar revisão independente quando relevante, obter deliberação específica de merge, conferir o diff integrado e atualizar o ponto de entrada documental ou índice de continuidade.

**No fechamento de subfase/incremento:** produzir handoff navegável, matriz de cobertura, checklist técnico/humano, pendências e risco de recuperação; executar teste de recuperação independente e registrar o resultado. Não declarar autossuficiência se houver fontes decisórias essenciais inacessíveis.

**Ao fechar uma fase:** somar aos critérios do Gate metodológico um exame de preservação documental, sem substituir ou ampliar silenciosamente o objeto decisório do Gate. A norma transversal precisa ser formalmente incorporada à governança antes de ser aplicada como critério obrigatório de bloqueio de Gate.

## 5. Modelo mínimo para registros relevantes

| Campo | Conteúdo mínimo |
|---|---|
| Identidade | ID estável, título, categoria, versão, estado documental, estado decisório |
| Conteúdo | Enunciado literal vigente ou classificação de cobertura explicitando ausências |
| Proveniência | Fonte original, autoria, contexto, momento conhecido, link ou localizador verificável |
| Ato humano | Aprovação/validação e seu alcance; não atribuir retrospectivamente |
| Consequências | Dependências, restrições, impactos, ressalvas e links a outros IDs |
| Controle | Caminho GitHub ou referência externa segura, commit/blob/hash e revisão |
| Continuidade | Próxima ação permitida, responsável por decisão, impedimentos e riscos |

Metadados impossíveis de recuperar devem ser marcados **NÃO COMPROVADOS**, nunca inventados.

## 6. Instrumentos operacionais propostos (A–F)

**A — Entrada única de reconstrução:** README para estado vigente e índice de continuidade com mapa de baselines, domínio, decisões, evidências, pendências e próximos passos. Histórico identificado como fotografia temporal.

**B — Sincronização contínua de decisões:** toda decisão material é registrada após manifestação humana, revisada e levada ao GitHub por procedimento autorizado. Uma decisão apenas no chat constitui **risco de continuidade** até sua preservação verificável.

**C — Três classes de conhecimento:** vigente; em elaboração; histórico/evidências. Separar aprovação de publicação e evitar links locais fictícios.

**D — Pacote de continuidade:** objetivos, fontes, IDs, resultados, decisões, fundamentos, riscos, pendências, impactos, testes, HEAD, documentos e próxima atividade em toda subfase/incremento relevante.

**E — Teste de Recuperação Autônoma:** avaliador sem chats verifica que pode localizar as fontes e reproduzir: objetivo, baselines, domínio pertinente, decisões, condicionantes, riscos, pendências, progresso e próxima ação; registra pontualmente lacunas e resultado SUFICIENTE / INSUFICIENTE.

**F — Backup independente:** cópia verificável do repositório (incluindo histórico, tags e metadados aplicáveis), evidências externas autorizadas e exportações de artefatos de design quando necessário; políticas de acesso, retenção e testes de restauração. **Destino, periodicidade, criptografia e responsável operacional: PENDENTES de definição**, sem assumir backup já existente.

## 7. Regras de suficiência e condições de parada

- Autossuficiência **não é** quantidade de arquivos: requer completude e acesso a informações materiais.
- Não substituir material primário ausente por resumo com status superior ao comprovado.
- Não consolidar escopo futuro, arquitetura, tenancy física, banco, roles técnicas ou MVP em fase inadequada.
- Quando o teste não permitir reconstruir decisão importante, classificar `INSUFICIENTE PARA RECUPERAÇÃO AUTÔNOMA`, abrir achado identificável, atribuir próxima ação e preservar trabalho já validado.
- Não declarar `CONCLUÍDO` um incremento apenas porque arquivos foram produzidos; validar hashes e conteúdo realmente integrado e verificado.

## 8. Aplicação ao passivo documental atual

A frente **DOC-AUTOSUF-01** deverá analisar e recuperar o conhecimento da Fase 3 sem reabrir Gate 3 e sem transformar aprovações em bloco em certificações de cada texto não recuperado. Preservar **14 pendências abertas e 2 encerramentos deliberados**, os doze candidatos BF-R02 como `PROPOSTO` e o estado `Fase 4 NÃO INICIADA`.

Incrementos propostos: D0 formalização; D1 inventário; D2 recuperação material do domínio; D3 atos e evidências; D4 navegação/continuidade; D5 teste de restauração e auditoria independente. Executar e publicar por contratos e deliberações delimitados.

## 9. Checklist editorial para deliberação

- [ ] Redação normativa da GOV-CONT-01 conferida pelo responsável.
- [ ] Compatibilidade com Governança v1.0 e Playbook v1.0 confirmada, sem substituição silenciosa.
- [ ] Destino, responsabilidades e frequência de backup externo definidos quando aplicável.
- [ ] Escopo e local de publicação autorizados explicitamente.
- [ ] Revisão independente e avaliação de dados sensíveis concluídas antes de merge.
- [ ] Rota documental capaz de permitir continuidade sem chats demonstrada no teste futuro D5.

**Decisão solicitada:** avaliar esta redação para aprovação documental e eventual publicação em PR próprio. Não há autorização de merge inferida deste arquivo.
