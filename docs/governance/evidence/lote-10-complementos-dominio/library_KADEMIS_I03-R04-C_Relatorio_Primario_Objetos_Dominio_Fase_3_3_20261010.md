# KADEMIS — PSD-I03 / I03-R04-C
## Relatório Primário — Objetos de Domínio da Fase 3.3

**Atividade:** recuperação documental do inventário e refinamentos de objetos/conceitos da Fase 3.3  
**Origem localizada:** chat `Fase 3.2 Processos`, segmento executado em 06/10/2026  
**Modo:** somente leitura  
**Resultado:** FONTE PRIMÁRIA LOCALIZADA E AUDITORIA EXECUTADA

# 1. Localização da fonte

A hipótese de que a Fase 3.3 pudesse estar em outro chat não se confirmou.

Foram recuperadas nesta mesma conversa:

- mensagem do assistente em `2026-10-06T20:14:24Z` com o inventário inicial;
- validação humana em `2026-10-06T20:40:45Z`: **“Validado”**;
- mensagem do assistente em `2026-10-06T22:11:51Z` com seis refinamentos;
- validação humana em `2026-10-06T22:11:47Z`: **“Validado”**;
- reafirmação humana em `2026-10-06T22:52:41Z`: **“Validado”**.

Há pequena inconsistência de ordenação de segundos entre a marca do assistente `22:11:51Z` e a validação humana `22:11:47Z` retornada pelo mecanismo de histórico. Esta auditoria preserva ambas as marcas e não força uma cronologia de segundos que o material recuperado não sustenta.

# 2. Inventário inicial recuperado

O inventário inicial contemplava, por grupos:

## Estrutura acadêmica
Instituição; Unidade Educacional; Ano Letivo; Calendário; Turno; Unidade Avaliativa; Semestre; Etapa de Ensino; Ano/Série; Componente Curricular; Oferta de Componente; Turma; Horário.

## Trajetória
Estudante; Responsável; Pessoa/Profissional; Função Institucional; Matrícula Institucional; Matrícula Acadêmica; Enturmação; Trajetória Acadêmica.

## Execução pedagógica
Planejamento Pedagógico; Aula; Registro de Aula; Conteúdo Ministrado; Registro de Frequência; Justificativa de Ausência; Documento Comprobatório.

## Avaliação
Instrumento Avaliativo; Resultado Avaliativo; Síntese Avaliativa; Recuperação; Sessão de Conselho de Classe; Decisão Acadêmica; Resultado Final; Pedido de Reconsideração.

## Vida escolar/documentação
Registro/Vida Escolar; Documento Escolar; Solicitação de Documento; Emissão Documental.

## Relacionamento/proteção
Comunicação Escola–Família; Ocorrência; Observação Contextual; Orientação Psicopedagógica; Aconselhamento Socioemocional; Situação Protetiva; Providência/Encaminhamento.

O usuário validou o inventário inicial com a manifestação **“Validado”**.

# 3. Refinamentos finais recuperados

A mensagem de refinamento validou seis decisões estruturantes.

## 3.1 Turma

`Turma regular` e `Turma eletiva` não permanecem como objetos fundamentais distintos.

**Decisão:** `Turma` é o conceito principal; regular/eletiva são naturezas/contextos.

## 3.2 Atuação Institucional

Foi acrescentado o conceito:

**Atuação Institucional** — relação entre Pessoa e Função Institucional em determinado contexto.

Isso evita converter automaticamente Função Institucional em role técnica.

## 3.3 Vínculo Estudante–Responsável

Foi acrescentado como relação com significado próprio.

Preserva:

- multiplicidade;
- temporalidade;
- contexto/finalidade;
- histórico.

## 3.4 Vínculo Docente com a Oferta

Foi acrescentado para evitar a suposição de um professor único e fixo por componente/turma.

Preserva vínculos múltiplos/substituições e contexto histórico.

## 3.5 Trajetória Acadêmica e Vida Escolar

Foram refinadas como **composições históricas**, não fontes paralelas duplicadas.

Consequência:

- fatos constituintes permanecem suas fontes;
- consolidação não reescreve silenciosamente a trajetória.

## 3.6 Documento externo e Providência/Encaminhamento

- documento externo não se torna objeto fundamental separado de Documento Escolar; preserva origem/proveniência;
- `Providência/Encaminhamento` deixa de ser objeto fundamental e é reservado principalmente a ação/evento, a aprofundar em 3.6.

O usuário validou os refinamentos e posteriormente reafirmou a consolidação.

# 4. Distinções documentadas

A Fase 3.3 preserva:

- Componente Curricular ≠ Oferta;
- Matrícula Acadêmica ≠ Enturmação;
- Pessoa ≠ Função Institucional ≠ Atuação Institucional;
- Aula ≠ Registro de Aula;
- Conselho enquanto prática/corpo ≠ Sessão concreta;
- Documento Escolar ≠ Emissão Documental;
- Ocorrência ≠ Observação Contextual ≠ Situação Protetiva;
- Trajetória Acadêmica e Vida Escolar = composições históricas, não fontes duplicadas.

# 5. Conceitos deliberadamente não congelados como objetos independentes

A auditoria preserva a ausência de decisão definitiva para:

- **Horário** — conceito válido; autonomia como objeto não congelada;
- **Recuperação** — conceito válido; objeto vs processo não congelado;
- **Orientação Psicopedagógica** — conceito válido; autonomia como objeto não fechada;
- **Aconselhamento Socioemocional** — conceito válido; autonomia como objeto não fechada.

Isso não é lacuna a ser preenchida por simetria.

# 6. Providência/Encaminhamento

Situação final:

**RETIRADO DO INVENTÁRIO FUNDAMENTAL DE OBJETOS**

Não significa termo apagado.

Foi preservado para análise como ação/evento, o que efetivamente ocorreu na Fase 3.6.

# 7. Situação documental

A fonte de 3.3 foi localizada diretamente nesta conversa.

- presença do inventário: COMPROVADA;
- validação humana do inventário: COMPROVADA;
- seis refinamentos: COMPROVADOS;
- validação humana dos refinamentos: COMPROVADA;
- encerramento/reafirmação: COMPROVADO.

Ressalva:

`R04-C-RES-01` — o mecanismo de recuperação retorna uma inversão de quatro segundos entre uma mensagem de refinamento do assistente e a validação do usuário; preservar os timestamps sem inferir ordem por segundos.

# 8. Parecer

**R04-C — RECONCILIADO TECNICAMENTE COM 1 RESSALVA DE METADADO TEMPORAL.**

Não foi encontrada dependência de outro chat.

# 9. Checklist

- [x] Segmento original da Fase 3.3 localizado.
- [x] Inventário inicial recuperado.
- [x] Validação inicial recuperada.
- [x] Seis refinamentos recuperados.
- [x] Validação dos refinamentos recuperada.
- [x] Providência/Encaminhamento não tratado como objeto fundamental.
- [x] Objetos não convertidos em tabelas/classes/agregados.
- [x] Nenhuma arquitetura/banco/API definida.
- [x] Nenhuma mutação externa.
- [x] Gate 3 não avaliado.
- [x] Fase 4 não iniciada.

**Classificação recomendada:** `R04-C — RECONCILIADO TECNICAMENTE COM 1 RESSALVA DE METADADO`.