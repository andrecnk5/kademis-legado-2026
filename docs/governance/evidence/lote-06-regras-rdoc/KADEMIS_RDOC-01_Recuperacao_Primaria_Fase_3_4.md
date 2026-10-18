# KADEMIS — RDOC-01
## Recuperação Primária das Regras de Domínio da Fase 3.4

**Arquivo:** `KADEMIS_RDOC-01_Recuperacao_Primaria_Fase_3_4.md`  
**Atividade:** Auditoria documental histórica em modo somente leitura  
**Origem:** Reconciliação Documental Pré-Gate 3  
**Escopo:** Conversa original que contém a Fase 3.4 — Regras de Domínio  
**Natureza:** Recuperação de evidências históricas; não constitui nova descoberta, nova aprovação ou alteração de baseline  

---

# 1. Escopo e fontes examinadas

Esta auditoria examinou exclusivamente o histórico disponível da conversa em que a Fase 3.4 — Regras de Domínio foi executada.

Foram considerados como fontes primárias, quando disponíveis:

1. mensagens do assistente nas quais regras foram originalmente propostas;
2. mensagens do responsável pelo projeto contendo validação, aprovação, rejeição ou instrução de continuidade;
3. mensagens posteriores da mesma conversa que formalizaram identificadores previamente propostos;
4. mensagens posteriores da mesma conversa que classificaram regras como refinadas, preservadas ou não recuperadas literalmente.

Não foram utilizados como fonte primária:

- SGSA - Old;
- GitHub;
- relatórios externos;
- resumos de outros chats;
- memória reconstruída de fases anteriores;
- inferências produzidas a partir de regras posteriores.

Quando uma família de regras anterior à Fase 3.4 foi apenas mencionada ou resumida na Fase 3.4, esta auditoria não a considera integralmente comprovada apenas por essa referência secundária.

---

# 2. Metodologia de recuperação

Para cada regra ou identificador localizado foram avaliados separadamente:

- identificador;
- redação literal disponível;
- posição relativa na conversa;
- contexto da proposta;
- autoria;
- evidência de validação;
- ajustes posteriores;
- relação comprovada com outros identificadores;
- ressalvas e dependências;
- situação documental;
- status histórico de aprovação.

Classificações documentais utilizadas:

- **COMPROVADO:** enunciado e evidências necessárias foram recuperados diretamente na conversa.
- **PARCIALMENTE COMPROVADO:** existe evidência relevante na conversa, mas a fonte apresentada no próprio chat já era uma recuperação/resumo ou faltam elementos primários.
- **NÃO COMPROVADO:** não foi recuperada evidência suficiente para comprovar o enunciado literal original.

Importante:

> A situação documental é distinta do status histórico de validação/aprovação.

Uma regra pode ter sido descrita na Fase 3.4 como "VALIDADA anteriormente" e, mesmo assim, permanecer documentalmente NÃO COMPROVADA nesta auditoria caso sua fonte primária e redação literal original não estejam disponíveis nesta conversa.

---

# 3. Resultado executivo

A auditoria localizou dois grandes conjuntos:

## 3.1 Regras novas efetivamente propostas e validadas na Fase 3.4

Foram recuperadas **36 regras novas**, com enunciado integral no histórico da conversa e evidência expressa de validação:

- `RD-CICLO-01..06` — 6 regras;
- `RD-TRAJ-01..07` — 7 regras;
- `RD-EXEC-01..07` — 7 regras;
- `RD-DOC-01..07` — 7 regras;
- `RD-CTX-01..02` — 2 regras;
- `RD-PROT-01..04` — 4 regras;
- `RD-RESP-01..03` — 3 regras.

**Situação documental:** COMPROVADO.

## 3.2 Famílias anteriores referenciadas durante a Fase 3.4

Também foram localizados **52 identificadores pertencentes a famílias anteriores**, descritas pelo próprio histórico da Fase 3.4 como já validadas anteriormente:

- `RD-Aval-01..05`;
- `RD-FREQ-01`;
- `RD-CONS-01..02`;
- `RD-Aula-01..08`;
- `RD-Com-01..08`;
- `RD-Oco-01..05`;
- `RD-Psi-01..23`.

Entretanto, a própria Fase 3.4 registrou que a redação literal integral dessas famílias não estava disponível e criou a pendência:

`P3.4-PEN-DOC-01 — PENDENTE — NÃO BLOQUEANTE`

Portanto:

- alguns desses identificadores possuem conteúdo secundário parcialmente recuperado;
- outros aparecem somente como intervalos/famílias;
- nenhum deles deve ser tratado como tendo redação literal original primária integralmente recuperada nesta auditoria, salvo futura apresentação de fonte primária.

---

# 4. Linha do tempo documental da Fase 3.4

## 4.1 Abertura da Fase 3.4

Após autorização explícita do responsável, o assistente declarou o início da:

**Fase 3.4 — Regras de Domínio**

Na abertura foi registrada uma limitação documental essencial:

> "o histórico confirma que a 3.1 já criou várias famílias `RD-*`, mas a redação literal de todas elas não está integralmente recuperável no contexto atual. Portanto, não vou recriar esses textos por memória nem reutilizar seus identificadores para regras novas."

Também foi registrada:

`P3.4-PEN-DOC-01 — PENDENTE — NÃO BLOQUEANTE`

com a decisão metodológica:

> "não renumerar, substituir nem reconstruir silenciosamente essas regras."

Essa mensagem é a principal evidência histórica da lacuna documental referente às famílias anteriores.

---

## 4.2 Primeiro lote de novas regras

Na primeira etapa foram propostas quatro famílias com identificadores provisórios:

- `CICLO-A..F`;
- `TRAJ-A..G`;
- `EXEC-A..G`;
- `DOC-A..G`.

O responsável respondeu:

> **"Validados."**

Na mensagem seguinte, o assistente formalizou:

- `RD-CICLO-01..06`;
- `RD-TRAJ-01..07`;
- `RD-EXEC-01..07`;
- `RD-DOC-01..07`.

Não foi registrada alteração semântica entre os enunciados provisórios e os identificadores definitivos.

---

## 4.3 Segundo lote de novas regras

Na etapa seguinte foram propostas diretamente com identificadores:

- `RD-CTX-01..02`;
- `RD-PROT-01..04`;
- `RD-RESP-01..03`.

O responsável respondeu:

> **"validado siga"**

Na sequência, o assistente registrou essas regras como validadas e executou a auditoria final da Fase 3.4.

---

## 4.4 Fechamento da Fase 3.4

Na auditoria final, o assistente declarou:

> **"Fase 3.4 — Regras de Domínio: CONCLUÍDA E VALIDADA EM CONTEÚDO."**

Foram contabilizadas:

> **"36 novas regras de domínio validadas nesta fase."**

Posteriormente, o responsável respondeu:

> **"Validado. Siga autorizado."**

autorizando a Fase 3.5.

Essa manifestação confirma o fechamento da Fase 3.4, mas não deve ser interpretada como recuperação retroativa da redação literal ausente das famílias antigas.

---

# 5. Inventário integral dos identificadores localizados

## 5.1 Identificadores COMPROVADOS — novas regras da Fase 3.4

| Família | IDs | Quantidade | Situação documental | Status histórico |
|---|---|---:|---|---|
| Ciclo Acadêmico | `RD-CICLO-01..06` | 6 | COMPROVADO | VALIDADO |
| Trajetória | `RD-TRAJ-01..07` | 7 | COMPROVADO | VALIDADO |
| Execução | `RD-EXEC-01..07` | 7 | COMPROVADO | VALIDADO |
| Documentação | `RD-DOC-01..07` | 7 | COMPROVADO | VALIDADO |
| Contexto | `RD-CTX-01..02` | 2 | COMPROVADO | VALIDADO |
| Proteção | `RD-PROT-01..04` | 4 | COMPROVADO | VALIDADO |
| Responsáveis | `RD-RESP-01..03` | 3 | COMPROVADO | VALIDADO |

Total: **36**

## 5.2 Identificadores anteriores referenciados na Fase 3.4

| Família | IDs | Quantidade | Situação documental nesta auditoria | Status histórico declarado na Fase 3.4 |
|---|---|---:|---|---|
| Avaliação | `RD-Aval-01..05` | 5 | PARCIALMENTE COMPROVADO | VALIDADA anteriormente |
| Frequência | `RD-FREQ-01` | 1 | PARCIALMENTE COMPROVADO | VALIDADA anteriormente |
| Conselho | `RD-CONS-01..02` | 2 | PARCIALMENTE COMPROVADO | VALIDADA anteriormente |
| Aula | `RD-Aula-01..08` | 8 | NÃO COMPROVADO quanto ao enunciado literal individual | VALIDADA anteriormente |
| Comunicação | `RD-Com-01..08` | 8 | PARCIAL para `04..08`; NÃO COMPROVADO para `01..03` | VALIDADA anteriormente |
| Ocorrências | `RD-Oco-01..05` | 5 | NÃO COMPROVADO quanto ao enunciado literal individual | VALIDADA anteriormente |
| Psicopedagogia | `RD-Psi-01..23` | 23 | NÃO COMPROVADO quanto ao enunciado literal individual | VALIDADA anteriormente |

Total de identificadores anteriores referenciados: **52**

Total geral de identificadores `RD-*` localizados na conversa da Fase 3.4: **88**.

---

# 6. Transcrição literal das regras COMPROVADAS

## 6.1 `RD-CICLO-01..06`

### RD-CICLO-01

Enunciado originalmente proposto como `CICLO-A`:

> "Um Ano Letivo deve possuir contexto institucional definido antes de servir de referência para ofertas, turmas, matrículas e execução pedagógica."

**Fonte:** mensagem da Etapa 1 da Fase 3.4, seção "Novas regras emergentes de P01 — Preparação do Ciclo Acadêmico".  
**Autoria:** assistente, como proposta de formalização baseada em decisões anteriormente validadas.  
**Validação:** usuário respondeu "Validados." ao lote.  
**Formalização posterior:** `RD-CICLO-01`.  
**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-CICLO-02

Enunciado originalmente proposto como `CICLO-B`:

> "A organização avaliativa de uma instituição pode ser bimestral, trimestral ou outra admitida pela regra aplicável; não deve ser presumida universalmente pelo Kademis."

**Fonte:** mesma etapa/lote.  
**Validação:** "Validados."  
**Formalização posterior:** `RD-CICLO-02`.  
**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-CICLO-03

Enunciado originalmente proposto como `CICLO-C`:

> "Semestre e Unidade Avaliativa são conceitos independentes e podem coexistir no mesmo Ano Letivo."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-CICLO-04

Enunciado originalmente proposto como `CICLO-D`:

> "Uma Oferta de Componente Curricular deve estar contextualizada no ciclo acadêmico correspondente; o Componente Curricular isolado não determina sua oferta concreta."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-CICLO-05

Enunciado originalmente proposto como `CICLO-E`:

> "Alterações relevantes de calendário, oferta, turma ou organização acadêmica durante o ciclo devem respeitar sua autoridade institucional aplicável e preservar efeitos históricos."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-CICLO-06

Enunciado originalmente proposto como `CICLO-F`:

> "O Kademis pode utilizar horários definidos externamente; a capacidade de construir ou otimizar o quadro de horários permanece EM DESCOBERTA e não constitui regra atual."

O próprio texto da Fase 3.4 registrou:

> "`CICLO-F` é deliberadamente uma regra de fronteira de escopo, não uma decisão de produto."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.  
**Ressalva:** capacidade do Kademis construir/otimizar horários permanece EM DESCOBERTA.

---

## 6.2 `RD-TRAJ-01..07`

### RD-TRAJ-01

Enunciado originalmente proposto como `TRAJ-A`:

> "Antes de tratar um ingresso como nova relação institucional, deve-se verificar se já existe identidade institucional daquele estudante."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-TRAJ-02

Enunciado originalmente proposto como `TRAJ-B`:

> "Retorno de estudante anteriormente vinculado à instituição não deve criar silenciosamente uma nova identidade institucional."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-TRAJ-03

Enunciado originalmente proposto como `TRAJ-C`:

> "Uma nova Matrícula Acadêmica pode ser necessária sem que isso implique nova Matrícula Institucional."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-TRAJ-04

Enunciado originalmente proposto como `TRAJ-D`:

> "Mudança de turma dentro do mesmo contexto acadêmico não implica, por si só, nova Matrícula Acadêmica."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-TRAJ-05

Enunciado originalmente proposto como `TRAJ-E`:

> "Transferência recebida deve preservar a procedência das informações acadêmicas externas incorporadas à trajetória."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-TRAJ-06

Enunciado originalmente proposto como `TRAJ-F`:

> "Classificação, reclassificação, reconhecimento de estudos anteriores e transferência devem obedecer às regras e autoridades aplicáveis; não são operações equivalentes."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-TRAJ-07

Enunciado originalmente proposto como `TRAJ-G`:

> "Conclusão, interrupção, transferência ou outra mudança de situação acadêmica não pode eliminar a trajetória anterior do estudante."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

Ressalva registrada na mesma etapa:

> "A nomenclatura formal dos estados de interrupção continua reservada à 3.7."

---

## 6.3 `RD-EXEC-01..07`

### RD-EXEC-01

Enunciado originalmente proposto como `EXEC-A`:

> "Uma aula prevista somente pode produzir fatos de execução pedagógica como aula efetivamente realizada quando houver registro de sua realização."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-EXEC-02

Enunciado originalmente proposto como `EXEC-B`:

> "O conteúdo ministrado deve se referir ao que efetivamente ocorreu, e não simplesmente ao planejamento anterior."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-EXEC-03

Enunciado originalmente proposto como `EXEC-C`:

> "O profissional que efetivamente ministrou a aula deve permanecer identificável, inclusive em substituições."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-EXEC-04

Enunciado originalmente proposto como `EXEC-D`:

> "Registro posterior de aula ou frequência pode ser admitido conforme política aplicável, preservando diferença entre momento do fato e momento do registro."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-EXEC-05

Enunciado originalmente proposto como `EXEC-E`:

> "Justificativa ou documento comprobatório pode produzir efeitos conforme regra institucional, mas não determina automaticamente esses efeitos por sua mera existência."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-EXEC-06

Enunciado originalmente proposto como `EXEC-F`:

> "Reposição, compensação ou regularização de frequência depende de autoridade e política aplicáveis."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-EXEC-07

Enunciado originalmente proposto como `EXEC-G`:

> "Atividade externa ou não convencional pode produzir efeitos acadêmicos e de frequência quando reconhecida pela regra institucional correspondente."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

---

## 6.4 `RD-DOC-01..07`

### RD-DOC-01

Enunciado originalmente proposto como `DOC-A`:

> "Um documento escolar deve representar fatos e decisões reconhecidos pela instituição; não deve criar uma trajetória paralela independente das fontes que o fundamentam."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-DOC-02

Enunciado originalmente proposto como `DOC-B`:

> "A autoridade necessária para preparar, conferir, validar e assinar documento pode variar conforme o tipo documental e a regra institucional aplicável."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-DOC-03

Enunciado originalmente proposto como `DOC-C`:

> "Segunda via e retificação são operações distintas."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-DOC-04

Enunciado originalmente proposto como `DOC-D`:

> "Documento proveniente de outra instituição deve preservar sua origem mesmo quando seus efeitos forem incorporados à vida escolar atual."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-DOC-05

Enunciado originalmente proposto como `DOC-E`:

> "Emissão documental deve estar vinculada à versão e ao contexto institucional vigentes naquele momento."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-DOC-06

Enunciado originalmente proposto como `DOC-F`:

> "A situação financeira do estudante ou responsável não pode ser tratada pelo domínio como fundamento genérico para impedir documentação cuja entrega seja juridicamente obrigatória."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-DOC-07

Enunciado originalmente proposto como `DOC-G`:

> "Documento digital que exija validade institucional deve possuir meio adequado de comprovação de autenticidade; o mecanismo técnico permanece para fase posterior."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

---

## 6.5 `RD-CTX-01..02`

Estas regras já foram propostas diretamente com identificadores definitivos.

### RD-CTX-01

> "Uma informação produzida por uma pessoa no exercício de determinada função institucional deve preservar o contexto dessa atuação e não deve ser automaticamente atribuída às demais funções exercidas pela mesma pessoa."

Contexto apresentado na própria mensagem:

> "Um registro produzido em contexto socioemocional não se torna automaticamente um registro docente comum apenas porque a pessoa também é professora."

**Fonte:** Fase 3.4 — Etapa 2, seção "Função institucional e autoria".  
**Validação:** usuário respondeu "validado siga".  
**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-CTX-02

> "Autoria do fato ou conteúdo, responsabilidade institucional por sua validação e operação material de registro podem pertencer a participantes diferentes e devem permanecer distinguíveis quando essa diferença for relevante ao domínio."

Exemplos apresentados:

- professor produz a nota;
- Conselho discute;
- Secretaria da Coordenação realiza lançamento;
- professor ministra a aula;
- outra operação pode registrar posteriormente;
- alguém produz conteúdo de comunicação;
- outra autoridade pode aprová-lo ou emiti-lo.

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

---

## 6.6 `RD-PROT-01..04`

### RD-PROT-01

> "Situação potencialmente protetiva deve ser tratada segundo sua natureza e gravidade, não automaticamente como ocorrência disciplinar cotidiana."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-PROT-02

> "Diante de situação protetiva, as providências e comunicações devem observar a autoridade institucional e os deveres aplicáveis ao contexto."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-PROT-03

> "O tratamento da situação deve limitar a coleta, circulação e reprodução de informações ao necessário para a finalidade legítima de proteção e atuação institucional."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-PROT-04

> "O processo deve preservar a origem das informações, o contexto em que foram conhecidas e as providências adotadas, sem converter o registro institucional em investigação clínica, policial ou diagnóstica."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

Ressalva registrada:

> "Essas regras não definem Conselho Tutelar, fluxos técnicos ou permissões automaticamente."

---

## 6.7 `RD-RESP-01..03`

### RD-RESP-01

> "A existência de múltiplos responsáveis pelo estudante deve ser preservada sem reduzir automaticamente todos os vínculos a um único responsável principal."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-RESP-02

> "A participação, comunicação ou autoridade de determinado responsável pode variar conforme finalidade, vínculo e regra aplicável."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

### RD-RESP-03

> "Um responsável legítimo não adquire automaticamente acesso irrestrito a toda informação registrada sobre o estudante apenas pela existência do vínculo de responsabilidade."

Ressalva registrada:

> "A terceira regra mantém aberta a definição jurídica e técnica de acesso. Ela não cria RBAC."

**Classificação documental:** COMPROVADO.  
**Status histórico:** VALIDADO.

---

# 7. Famílias anteriores — evidência documental recuperada apenas parcialmente

## 7.1 `RD-Aval-01..05`

A Fase 3.4 declarou que essas regras eram anteriores e já validadas.

### RD-Aval-01

Na abertura da 3.4 foi apresentada a redação:

> "Critérios de avaliação, recuperação, síntese, promoção e retenção obedecem à hierarquia:
>
> legislação → normas do sistema de ensino → Regimento/Projeto Pedagógico → regras institucionais aplicáveis."

A mensagem chamou essa redação de:

> "Redações recuperadas com segurança"

Entretanto, ela não foi apresentada como fonte primária original da criação da regra.

**Situação documental:** PARCIALMENTE COMPROVADO.  
**Status histórico declarado:** VALIDADA anteriormente.  
**Limitação:** ausência da mensagem primária de origem e aprovação original nesta conversa.

### RD-Aval-02

Posteriormente a Fase 3.4 apresentou conteúdo consolidado:

> "política avaliativa é contextual e não deve ser presumida universalmente"

**Situação documental:** PARCIALMENTE COMPROVADO.  
**Limitação:** conteúdo secundário consolidado; redação original não comprovada.

### RD-Aval-03

Conteúdo consolidado:

> "recuperação deve preservar a trajetória avaliativa e obedecer às regras aplicáveis"

**Situação documental:** PARCIALMENTE COMPROVADO.

### RD-Aval-04

Conteúdo consolidado:

> "resultado final decorre das regras e evidências pertinentes ao contexto acadêmico"

**Situação documental:** PARCIALMENTE COMPROVADO.

### RD-Aval-05

Conteúdo consolidado:

> "revisão de resultados deve permanecer rastreável"

**Situação documental:** PARCIALMENTE COMPROVADO.

---

## 7.2 `RD-FREQ-01`

Na abertura da 3.4 foi apresentada a redação:

> "O tratamento da frequência deve respeitar a hierarquia normativa aplicável; uma regra local não pode contrariar obrigação superior."

**Situação documental:** PARCIALMENTE COMPROVADO.  
**Status histórico declarado:** VALIDADA anteriormente.  
**Limitação:** fonte primária original da regra não recuperada nesta conversa.

---

## 7.3 `RD-CONS-01..02`

### RD-CONS-01

Na abertura da 3.4 foi apresentada:

> "Composição, natureza, competência e autoridade do Conselho de Classe dependem da legislação, das normas do sistema de ensino e do Regimento aplicáveis."

**Situação documental:** PARCIALMENTE COMPROVADO.

### RD-CONS-02

Na abertura da 3.4 foi apresentada:

> "Decisões do Conselho de Classe com efeitos acadêmicos devem considerar percurso, evidências pertinentes e regras aplicáveis, não somente um valor numérico."

**Situação documental:** PARCIALMENTE COMPROVADO.

Para ambas:

**Status histórico declarado:** VALIDADA anteriormente.  
**Limitação:** origem primária e aprovação original não recuperadas nesta conversa.

---

## 7.4 `RD-Aula-01..08`

A Fase 3.4 confirmou a existência da família:

`RD-Aula-01` a `RD-Aula-08`

e afirmou que o conteúdo consolidado cobria:

- distinção entre planejamento e execução;
- registro do que efetivamente ocorreu;
- autoria;
- substituição;
- reposição;
- fechamento;
- reabertura;
- retificação;
- rastreabilidade das alterações.

Entretanto, não apresentou associação individual comprovável entre cada enunciado e cada identificador.

**Situação documental individual:** NÃO COMPROVADO quanto ao enunciado literal.  
**Status histórico declarado:** VALIDADA anteriormente.  
**Limitação:** não é possível reconstruir legitimamente `RD-Aula-01`, `02`, etc. a partir da lista de temas.

---

## 7.5 `RD-Com-01..08`

A Fase 3.4 declarou a família `RD-Com-01..08` como previamente validada.

Foram recuperados com maior especificidade os seguintes conteúdos:

### RD-Com-04

> "distinguir autoria do conteúdo, emissão institucional e aprovação"

### RD-Com-05

> "entrega, leitura, ciência e manifestação pertencem ao destinatário efetivo"

### RD-Com-06

> "preservar destinatários e relações historicamente"

### RD-Com-07

> "retificação material preserva versão anterior e a correção/retratação"

### RD-Com-08

> "todo estudante possui ao menos um responsável; uma finalidade pode envolver um ou vários responsáveis sem destruir vínculos legítimos"

Esses textos foram apresentados na 3.4 como "regras recuperadas com maior segurança", não como transcrição da fonte primária original.

**Situação documental de `RD-Com-04..08`:** PARCIALMENTE COMPROVADO.  
**Situação documental de `RD-Com-01..03`:** NÃO COMPROVADO quanto ao enunciado literal.  
**Status histórico declarado da família:** VALIDADA anteriormente.

A 3.4 acrescentou um refinamento:

> "o conteúdo comunicado não precisa reproduzir integralmente o registro interno que originou a comunicação."

E determinou que esse conteúdo fosse tratado como:

> "refinamento da família `RD-Com-*`, e não nova família."

Não foi comprovado nesta conversa qual identificador histórico individual absorveu formalmente esse refinamento.

---

## 7.6 `RD-Oco-01..05`

A Fase 3.4 confirmou a família e resumiu que cobria:

- ocorrência é distinta de comunicação;
- ocorrência preserva contexto e autoria;
- ocorrência não produz consequência automática simplesmente por existir;
- seu tratamento deve ser compatível com a proteção do estudante;
- eventual comunicação/notificação externa é distinta do fato original.

Não houve mapeamento individual desses cinco conteúdos para `RD-Oco-01`, `02`, `03`, `04`, `05`.

**Situação documental individual:** NÃO COMPROVADO quanto ao enunciado literal.  
**Status histórico declarado:** VALIDADA anteriormente.

---

## 7.7 `RD-Psi-01..23`

A Fase 3.4 declarou `RD-Psi-01..23` como previamente validadas e afirmou que essa família cobria conceitualmente:

- separação entre diferentes naturezas de acompanhamento;
- não produção automática de diagnóstico;
- apoio sem diagnóstico;
- encaminhamento;
- finalidade e restrição do registro;
- proteção;
- plano/evolução/intervenção quando aplicável;
- participação familiar;
- documentos externos;
- adaptações;
- prevalência da proteção;
- relação com responsáveis;
- informação comunicada ≠ registro integral;
- minimização;
- procedência de eventual diagnóstico;
- limites funcionais;
- participação do estudante.

Não foi possível recuperar, nesta conversa, qual redação corresponde a cada um dos 23 identificadores.

**Situação documental individual:** NÃO COMPROVADO quanto ao enunciado literal.  
**Status histórico declarado:** VALIDADA anteriormente.

---

# 8. Matriz de rastreabilidade documental

## 8.1 Novas regras da Fase 3.4

| IDs | Proposta original | Validação humana | Formalização | Situação |
|---|---|---|---|---|
| `RD-CICLO-01..06` | `CICLO-A..F` na Etapa 1 | "Validados." | mensagem seguinte | COMPROVADO |
| `RD-TRAJ-01..07` | `TRAJ-A..G` na Etapa 1 | "Validados." | mensagem seguinte | COMPROVADO |
| `RD-EXEC-01..07` | `EXEC-A..G` na Etapa 1 | "Validados." | mensagem seguinte | COMPROVADO |
| `RD-DOC-01..07` | `DOC-A..G` na Etapa 1 | "Validados." | mensagem seguinte | COMPROVADO |
| `RD-CTX-01..02` | IDs definitivos na Etapa 2 | "validado siga" | mantidos | COMPROVADO |
| `RD-PROT-01..04` | IDs definitivos na Etapa 2 | "validado siga" | mantidos | COMPROVADO |
| `RD-RESP-01..03` | IDs definitivos na Etapa 2 | "validado siga" | mantidos | COMPROVADO |

## 8.2 Famílias anteriores

| IDs | Evidência encontrada na Fase 3.4 | Validação primária original nesta conversa | Situação |
|---|---|---|---|
| `RD-Aval-01..05` | conteúdo recuperado/secundário | não localizada | PARCIALMENTE COMPROVADO |
| `RD-FREQ-01` | redação recuperada/secundária | não localizada | PARCIALMENTE COMPROVADO |
| `RD-CONS-01..02` | redação recuperada/secundária | não localizada | PARCIALMENTE COMPROVADO |
| `RD-Aula-01..08` | apenas cobertura temática | não localizada | NÃO COMPROVADO literal |
| `RD-Com-01..03` | somente existência da família | não localizada | NÃO COMPROVADO literal |
| `RD-Com-04..08` | conteúdo secundário individual | não localizada | PARCIALMENTE COMPROVADO |
| `RD-Oco-01..05` | apenas cobertura temática coletiva | não localizada | NÃO COMPROVADO literal |
| `RD-Psi-01..23` | apenas cobertura temática coletiva | não localizada | NÃO COMPROVADO literal |

---

# 9. Regras alteradas, substituídas, refinadas ou absorvidas

## 9.1 Formalização de identificadores provisórios

As seguintes regras foram propostas com identificadores provisórios e depois formalizadas sem alteração semântica registrada:

- `CICLO-A..F` → `RD-CICLO-01..06`;
- `TRAJ-A..G` → `RD-TRAJ-01..07`;
- `EXEC-A..G` → `RD-EXEC-01..07`;
- `DOC-A..G` → `RD-DOC-01..07`.

**Classificação:** formalização de ID, não substituição de conteúdo.

## 9.2 Refinamentos das famílias anteriores

A Fase 3.4 determinou que descobertas posteriores sobre:

- Avaliação;
- Comunicação;
- Ocorrências;
- Psicopedagogia/Socioemocional

fossem tratadas como:

> "refinamentos das famílias `RD-*` já existentes, sem criar IDs concorrentes."

Não foi documentado nesta conversa um patch literal, por identificador, para todas essas famílias.

Portanto:

- o fato de que houve refinamento conceitual é COMPROVADO;
- o texto integral resultante por regra histórica individual NÃO é comprovável nesta conversa.

## 9.3 Regras absorvidas

Não foi localizada, na Fase 3.4, evidência de uma regra `RD-*` nova ter sido formalmente absorvida por outra e seu ID aposentado.

Absorções de identificadores encontradas em fases posteriores referem-se a eventos `EVT-*`, não pertencem ao escopo desta auditoria e não foram incorporadas como alterações de `RD-*`.

---

# 10. Ressalvas e dependências registradas na Fase 3.4

## 10.1 `P3.4-PEN-DOC-01`

**PENDENTE DOCUMENTAL — NÃO BLOQUEANTE**

Objeto:

Recuperação da redação literal completa das famílias históricas anteriores:

- `RD-Aval-*`;
- `RD-Aula-*`;
- `RD-Com-*`;
- `RD-Oco-*`;
- `RD-Psi-*`;
- e demais identificadores históricos cuja fonte primária não estava disponível.

Decisão metodológica associada:

> não renumerar, substituir nem reconstruir silenciosamente essas regras.

Esta auditoria confirma que a pendência era material e permanece relevante para as famílias anteriores que não foram recuperadas em fonte primária.

---

## 10.2 `P04-PEN-01`

**PENDENTE JURÍDICO/REGIMENTAL — NÃO BLOQUEANTE**

Objeto:

Prática local relatada de cobrança para nova realização de avaliação em determinadas situações.

A Fase 3.4 registrou expressamente:

> "A prática local de pagamento para determinada nova realização de avaliação não será transformada em regra do Kademis até análise jurídica/regimental apropriada."

Nenhuma `RD-*` universal foi criada para legitimar essa prática.

---

## 10.3 `P06-PEN-JUR-01`

**PENDENTE JURÍDICA — NÃO BLOQUEANTE PARA A FASE 3**

Objeto:

Compartilhamento, confidencialidade, acesso e comunicação de informações psicopedagógicas ou sensíveis envolvendo crianças e adolescentes.

A Fase 3.4 preservou essa pendência e não a resolveu por meio de RBAC ou regra técnica.

Ela afeta principalmente:

- `RD-PROT-*`;
- `RD-RESP-*`;
- refinamentos de `RD-Psi-*`;
- refinamentos de comunicação.

---

## 10.4 Horários

`RD-CICLO-06` preserva:

**EM DESCOBERTA**

a capacidade futura de o próprio Kademis construir ou otimizar quadro de horários.

A regra validada permite que o Kademis utilize horários definidos externamente, mas não decide ainda se o produto construirá esses horários.

---

## 10.5 Acesso de responsáveis

`RD-RESP-03` foi validada com ressalva expressa:

> a definição jurídica e técnica de acesso permanece aberta.

A regra não cria RBAC e não determina permissões técnicas.

---

# 11. Divergências e lacunas documentais

## 11.1 Principal lacuna

A maior lacuna é a ausência, nesta conversa da Fase 3.4, das fontes primárias originais de várias famílias `RD-*` criadas em momento anterior.

A própria Fase 3.4 reconheceu essa limitação.

Consequência:

> não é documentalmente correto reconstruir o texto integral de `RD-Aula-*`, `RD-Oco-*`, `RD-Psi-*` ou demais IDs ausentes a partir dos resumos encontrados.

## 11.2 Conteúdo consolidado não equivale a transcrição literal

Tabelas e bullets usados na Fase 3.4 para descrever `RD-Aval-*`, `RD-Com-*`, etc. devem ser tratados como evidência secundária de significado, não como prova automática da redação literal original.

## 11.3 Aprovação histórica declarada não equivale a evidência primária de aprovação

A Fase 3.4 afirmou que famílias anteriores estavam "VALIDADAS anteriormente".

Essa afirmação documenta a compreensão histórica mantida naquele momento, mas não substitui a mensagem primária de validação original para fins de recuperação documental estrita.

## 11.4 Novas regras da 3.4 possuem cadeia primária suficiente

Em contraste, as 36 regras novas possuem:

proposta textual → manifestação expressa de validação → formalização/fechamento.

Para essas regras, a cadeia documental é suficiente.

---

# 12. Conclusão de suficiência documental — limitada à Fase 3.4

## 12.1 Conclusão sobre as regras criadas na própria Fase 3.4

A recuperação é **SUFICIENTE** para comprovar integralmente as 36 regras novas:

- `RD-CICLO-01..06`;
- `RD-TRAJ-01..07`;
- `RD-EXEC-01..07`;
- `RD-DOC-01..07`;
- `RD-CTX-01..02`;
- `RD-PROT-01..04`;
- `RD-RESP-01..03`.

Para elas, foram recuperados:

- enunciados;
- contexto;
- proposta;
- validação humana;
- formalização;
- ressalvas aplicáveis.

## 12.2 Conclusão sobre as famílias anteriores

A recuperação **NÃO É INTEGRAL** para:

- `RD-Aval-01..05`;
- `RD-FREQ-01`;
- `RD-CONS-01..02`;
- `RD-Aula-01..08`;
- `RD-Com-01..08`;
- `RD-Oco-01..05`;
- `RD-Psi-01..23`.

Há evidência suficiente para comprovar que essas famílias foram consideradas existentes e previamente validadas durante a Fase 3.4.

Não há, nesta conversa, fonte primária suficiente para comprovar integralmente a redação original de todos os identificadores nem a manifestação original de validação individual de cada regra.

Portanto, a pendência documental histórica deve ser preservada.

## 12.3 Situação final do RDOC-01

**Recuperação primária das regras novas da Fase 3.4:** SUFICIENTE.  
**Recuperação integral de todas as famílias `RD-*` referenciadas na Fase 3.4:** INSUFICIENTE.  
**Lacuna:** explicitamente preservada.  
**Novas regras criadas nesta auditoria:** nenhuma.  
**Novas aprovações concedidas:** nenhuma.  
**GitHub alterado:** não.  
**Gate 3 avaliado:** não.  
**Fase 4 iniciada:** não.

---

# 13. Checklist de encerramento RDOC-01

- [x] Todas as regras novas da Fase 3.4 localizadas.
- [x] Identificadores provisórios e definitivos reconciliados.
- [x] Enunciados literais das 36 regras novas preservados.
- [x] Evidências de validação localizadas.
- [x] Famílias anteriores inventariadas.
- [x] Evidência secundária separada de fonte primária.
- [x] Lacunas documentais preservadas.
- [x] Pendências jurídicas/regimentais preservadas.
- [x] Nenhuma nova regra criada.
- [x] Nenhuma aprovação retroativa atribuída.
- [x] Nenhuma alteração no GitHub.
- [x] Gate 3 não avaliado.
- [x] Nenhuma atividade de Fase 4 executada.

---

# 14. Encerramento

O RDOC-01 recupera com suficiência documental as regras efetivamente criadas e validadas durante a Fase 3.4.

As famílias anteriores mencionadas na Fase 3.4 permanecem com graus distintos de comprovação documental e não devem ser promovidas a "integralmente recuperadas" sem confronto com suas mensagens primárias de origem.

Esta conclusão é estritamente documental e não altera o status conceitual, metodológico ou histórico do Projeto Kademis.
