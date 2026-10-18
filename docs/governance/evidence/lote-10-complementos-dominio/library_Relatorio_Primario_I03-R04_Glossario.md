# KADEMIS — I03-R04 — Relatório Primário do Glossário (R04-A)

**Frente:** PSD-I03 — Organização e Proveniência dos Catálogos de Domínio  
**Atividade:** I03-R04 — R04-A, Fase 3.1 Glossário  
**Origem auditada:** chat original `Fase 3.1 Glossário`  
**Modo:** Chat — somente leitura  
**Data da execução:** 10/10/2026  
**Mutação externa:** nenhuma  
**I03-R05:** não iniciada  
**Gate 3:** não avaliado  
**Fase 4:** não iniciada

---

## 1. Escopo efetivamente executado

Foi executado o recorte **R04-A — Glossário** dentro do que este chat efetivamente reexpõe como fonte primária.

Não foi executado R04-B nem R04-C nesta conversa, porque não foi recuperado aqui trecho primário da Fase 3.2 ou 3.3. O próprio encerramento da 3.1 determinou que a continuidade fosse realizada em outro chat (`Fase 3.2 Processos`).

**Resultado:** R04-A executado com lacunas; R04-B/R04-C registrados como dependência externa.

---

## 2. Corpus acessível

### 2.1 Fonte primária efetivamente disponível neste chat

O histórico atualmente acessível conserva integralmente, com proposta e validação humana, sobretudo:

- refinamentos de responsáveis e cardinalidade;
- Psicopedagogia + Socioemocional;
- acompanhamento/intervenção;
- proteção, adaptação e relações familiares;
- auditoria final do núcleo psicopedagógico;
- Estrutura Acadêmica;
- Matrícula e Trajetória Acadêmica;
- Vida Escolar e Documentação;
- auditoria transversal de encerramento da Fase 3.1.

### 2.2 Trechos anteriores parcialmente acessíveis

Os núcleos anteriores de:

- frequência;
- avaliação e resultados;
- Conselho de Classe;
- planejamento/aula/registro docente;
- comunicação/ocorrências iniciais;

aparecem no estado de continuidade e em auditorias posteriores, mas **as mensagens primárias integrais de todos os verbetes não estão reexpostas de maneira uniforme no corpus atual**.

Por isso, esses itens foram:

- incluídos somente quando a própria auditoria transversal desta conversa os retomou de forma explícita; ou
- classificados como **PARCIALMENTE COMPROVADOS**, sem reconstruir a definição literal.

### 2.3 Fontes secundárias usadas apenas para orientação

Foram considerados somente como apoio de localização/controle:

- I03-R01;
- RDOC-01A/RDOC-01B;
- resumos de continuidade;
- memória de projeto.

Nenhuma dessas fontes foi promovida a mensagem primária de glossário.

---

## 3. Contagem verificada deste recorte

A matriz contém **127 linhas de auditoria**.

Situação documental:

- **COMPROVADO: 106**
- **PARCIALMENTE COMPROVADO: 21**

Essas contagens representam **linhas de auditoria**, não um catálogo canônico nem o número oficial definitivo de verbetes da Fase 3.1.

A razão é metodológica:

- diversos termos não possuíam ID;
- alguns aparecem como refinamentos/nomes anteriores;
- alguns são convenções terminológicas;
- alguns verbetes anteriores só estão parcialmente reexpostos.

---

## 4. Principais cadeias de refinamento comprovadas

### 4.1 Responsável–Estudante

A cadeia primária acessível comprova:

1. correção de cardinalidade: todo estudante deve ter pelo menos um responsável;
2. cardinalidade estrutural `1..N`;
3. múltiplos responsáveis pedagógicos;
4. possibilidade de Responsável Principal contextual quando houver fundamento legítimo;
5. Responsável Principal não elimina outros vínculos válidos;
6. Responsável Pedagógico ≠ Responsável Legal ≠ Responsável Financeiro.

Isso é um **refinamento semântico comprovado**, não uma modelagem de autorização técnica.

### 4.2 Psicopedagogia + Socioemocional

A fonte primária acessível preserva distinções explícitas entre:

- fato/observação;
- sinal;
- interpretação pedagógica;
- interpretação especializada;
- acompanhamento;
- intervenção;
- avaliação psicopedagógica;
- diagnóstico externo;
- condição apenas informada;
- dados sensíveis;
- devolutiva e registro interno;
- participação da família e acesso aos registros;
- participação do estudante e autoridade jurídica.

O refinamento mais relevante foi:

`Diagnóstico/Condição Informada` → decomposição em **Diagnóstico Externo Documentado** e **Condição Informada**.

### 4.3 Adaptação Educacional × Adaptação Razoável

A auditoria do próprio núcleo restringiu o termo **Adaptação Razoável** ao sentido legal pertinente, preservando **Adaptação Educacional** como conceito mais amplo.

A versão anterior não foi apagada; foi refinada semanticamente.

### 4.4 Estrutura Acadêmica

Foram demonstradas as distinções:

- Instituição Educacional × Unidade Escolar;
- Ano Letivo × Turno;
- Ano/Série Escolar × Turma;
- Turma Regular × Turma de Eletiva;
- Componente Curricular × Oferta de Componente Curricular;
- Semestre Acadêmico × Unidade Avaliativa;
- `Período` como termo ambíguo a evitar isoladamente.

### 4.5 Matrícula e trajetória

A fonte comprova:

- Estudante × Matrícula Acadêmica × Enturmação;
- Número de Matrícula Institucional × Identificador Externo;
- Nova Matrícula × Rematrícula × Reativação;
- Transferência de Turma × Transferência Escolar;
- Reclassificação;
- Aproveitamento de Estudos;
- Movimento Acadêmico.

O termo `Reingresso` foi mantido como **DEPRECATED** quando o significado real for Reativação.

### 4.6 Vida Escolar e Documentação

As distinções recuperadas incluem:

- Vida Escolar × documento;
- Escrituração Escolar;
- Histórico Escolar como documento derivado;
- Documento Escolar Emitido × Documento Escolar Recebido;
- Acervo Escolar × Custódia Documental;
- Emissão × Reemissão × Retificação.

---

## 5. Convenções terminológicas finais comprovadas

A auditoria transversal da Fase 3.1 estabeleceu explicitamente:

- **Estudante** como termo canônico; `Aluno` como sinônimo institucional/interface;
- **Docente** como termo canônico geral; `Professor` continua válido em nomenclaturas específicas;
- **Componente Curricular** como termo canônico; `Disciplina` pode ser nomenclatura institucional;
- **Turno** para manhã/tarde/noite;
- **Período** não deve ser usado isoladamente;
- **Reingresso** é DEPRECATED quando equivaler a Reativação;
- termos amplos como `Aula`, `Ocorrência`, `Avaliação`, `Resultado`, `Acompanhamento`, `Fechamento`, `Reabertura`, `Responsável` e `Registro` devem ser qualificados quando a ambiguidade alterar o significado de domínio.

---

## 6. Lacunas documentais do R04-A

### 6.1 Núcleos anteriores não integralmente reexpostos

Não foi possível recuperar, como mensagem primária integral para cada verbete, todo o vocabulário dos primeiros núcleos da 3.1.

Itens especialmente afetados incluem, entre outros:

- Unidade Avaliativa;
- Aula Prevista;
- Ocorrência de Aula;
- Aula Realizada;
- Conteúdo Previsto;
- Conteúdo Ministrado;
- Professor de Referência;
- Professor Ministrante;
- Substituição Docente;
- Fechamento do Diário;
- Reabertura;
- Retificação;
- Avaliação da Aprendizagem;
- Instrumento Avaliativo;
- Resultado Avaliativo;
- Política Avaliativa;
- Conselho de Classe;
- Ocorrência Escolar;
- Observação Pedagógica.

Esses termos possuem forte evidência de existência e uso na continuidade da própria 3.1, mas **a literalidade primária individual não foi reexposta nesta execução**.

Classificação: **PARCIALMENTE COMPROVADO**.

### 6.2 Mantenedora × Instituição × pessoa jurídica

A própria Fase 3.1 encerrou esse ponto como **EM DESCOBERTA**.

Não há autorização documental para consolidar uma relação final ou estrutura societária.

### 6.3 Catálogos/taxonomias não congelados

Permaneceram deliberadamente abertos:

- catálogo completo de estados de matrícula;
- catálogo completo de naturezas de ocorrência;
- permissões/RBAC;
- operacionalização jurídica do compartilhamento psicopedagógico;
- autoridade final de determinadas documentações escolares.

Esses pontos não são falhas do Glossário: são **limites metodológicos preservados**.

---

## 7. Coerência transversal observável sem criar decisão nova

A fonte primária deste chat permite constatar compatibilidade entre:

- `Estudante`, `Matrícula Acadêmica`, `Enturmação` e invariantes posteriores de preservação histórica;
- `Reemissão` e a posterior distinção entre fatos escolares e emissões documentais;
- `Situação da Matrícula` e posterior tratamento de estados;
- `Responsável`, comunicação e refinamentos posteriores de acesso/participação;
- conceitos de Psicopedagogia/Socioemocional e posteriores regras/invariantes de sigilo, proteção e proveniência.

Esta seção registra apenas **correspondência documental**, não redefine RD/INV/EVT/EST.

---

## 8. R04-B e R04-C neste chat

### R04-B — Processos

**NÃO EXECUTADO AQUI.**

Não foi recuperado trecho primário da **Fase 3.2 — Processos** nesta conversa. O encerramento da 3.1 determina explicitamente continuidade em novo chat `Fase 3.2 Processos`.

**Dependência de fonte primária:** chat `Fase 3.2 Processos`.

### R04-C — Objetos de Domínio

**NÃO EXECUTADO AQUI.**

Não há fonte primária suficiente da Fase 3.3 neste chat acessível.

Conforme o contrato, a localização primária integral deve ser verificada primeiro em `Fase 3.2 Processos` e nas remissões explícitas ali existentes.

Não foi criado nome de chat, arquivo ou localização por suposição.

---

## 9. Parecer documental do recorte

**R04-A — AUDITORIA EXECUTADA COM LACUNAS.**

Há cobertura primária forte dos blocos finais e da auditoria transversal da 3.1, mas a parte mais antiga do histórico não está integralmente reexposta nesta execução.

Por isso, este relatório **não declara “catálogo integral comprovado”**.

Ele entrega:

- matriz de itens realmente recuperados;
- definições finais quando demonstradas;
- refinamentos comprovados;
- convenções finais;
- termos parcialmente comprovados;
- dependências externas.

---

## 10. Checklist do recorte

- [x] Histórico primário acessível da 3.1 revisado.
- [x] Limites explícitos registrados.
- [x] Itens sem ID receberam apenas `linha NNN` de auditoria.
- [x] Nenhum ID de domínio novo foi criado.
- [x] Proposta e validação humana separadas.
- [x] Refinamentos preservados.
- [x] Itens parcial/não comprovados listados.
- [x] R04-B não simulado.
- [x] R04-C não simulado.
- [x] RD/INV/EVT/EST não reabertos.
- [x] Nenhuma mutação externa.
- [x] I03-R05 não iniciada.
- [x] Gate 3 não avaliado.
- [x] Fase 4 não iniciada.

---

## 11. Estado de saída

**R04-A — Fase 3.1 Glossário:** AUDITORIA EXECUTADA COM LACUNAS.  
**R04-B:** DEPENDÊNCIA DE FONTE PRIMÁRIA — `Fase 3.2 Processos`.  
**R04-C:** DEPENDÊNCIA DE LOCALIZAÇÃO PRIMÁRIA — verificar em `Fase 3.2 Processos`.  
**PSD-I03:** deve receber matriz, relatório e handoff deste recorte para reconciliação posterior.  