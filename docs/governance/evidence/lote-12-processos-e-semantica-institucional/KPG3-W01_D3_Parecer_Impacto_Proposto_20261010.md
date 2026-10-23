# KPG3-W01 — D3. Parecer proposto de impacto Pré-Gate 3

**Data:** 10/10/2026  
**Estado:** proposta técnica-documental para auditoria; não é decisão formal, avaliação do Gate, nem alteração de pendência.

## Critério aplicado

O Playbook v1.0 estabelece como critério literal de Gate 3 que o domínio possa ser explicado sem depender do desenho do banco. Este parecer apenas considera se lacunas documentais podem afetar essa explicabilidade. As classes abaixo são **propostas** e não mudam qualquer estado formal. Nenhuma conclusão de bloqueio é automática.

| Lacuna material | Evidência e conclusão documental | Gravidade / risco conceitual | Classificação proposta | Fundamentação e condição | Autoridade/decisão necessária | Confiança |
|---|---|---|---|---|---|---|
| Mapeamento entre Instituição e Instituição Educacional; entre Unidade Educacional e Unidade Escolar | A matriz de 3.1 fornece literais validados para Instituição Educacional e Unidade Escolar. A matriz de objetos 3.3 registra Instituição como VALIDADO e Unidade Educacional como VALIDADO COM RESSALVA, sem literais. A reconciliação R04 diz que a diferença de nomenclatura pode refletir refinamento/contexto, não prova contradição e não autoriza fusão. | **Moderada e condicional.** Risco de vocabulário integrado inconsistente, fronteira institucional interpretada de modo divergente ou falsa equivalência. Não há demonstração de que um fluxo essencial específico falhe sem o mapeamento. | **NÃO BLOQUEANTE PARA GATE 3 — CONDICIONAL** | Pode permanecer como termos separados, atribuídos a cada origem e com mapeamento explicitamente não decidido, se a explicação dos fluxos essenciais não depender de equivalência entre eles. Passa a potencialmente bloqueante se uma explicação essencial exigir a mesma fronteira institucional/unidade e não puder ser expressa sem essa relação. | Responsável pelo Kademis, após auditoria independente; o auditor pode recomendar prova focal adicional. | Média: diferença e estado estão em fontes; relevância para fluxo é condicional. |
| Relação Mantenedora ↔ Instituição ↔ pessoa jurídica | Registro 127 confirma que a questão existe e permanece EM DESCOBERTA; a definição final é explicitamente não definida na recuperação acessível. A nota 3.1 exclui identidade necessária entre Instituição Educacional, Mantenedora e pessoa jurídica, sem resolver casos concretos. | **Moderada, potencialmente alta conforme escopo do fluxo.** Risco de não saber qual entidade representa ou responde pelo contexto institucional; risco de converter hipótese em determinação jurídica. | **POTENCIALMENTE BLOQUEANTE PARA GATE 3** | Apenas potencialmente bloqueante se a explicação de uma fronteira ou fluxo essencial do domínio depender de distinguir quem mantém, quem é atendido e qual entidade jurídica responde. A evidência atual não demonstra que essa condição se verifica em todos os fluxos nem autoriza afirmar que o Gate esteja bloqueado. | Responsável pelo Kademis, com fonte/autoridade institucional ou jurídica competente quando a decisão envolver personalidade, representação ou obrigação legal. Auditoria independente deve testar se há fluxo essencial dependente da relação. | Média-baixa quanto ao impacto; alta quanto ao estado aberto documentado. |
| Literais 3.3 de Instituição (OD-01) e Unidade Educacional (OD-02) não acessíveis nesta execução | I03-R04-C comprova inventário e estado; não transcreve literais. A origem original “Fase 3.2 Processos”, segmento 3.3, não está acessível. A reconciliação identifica a divergência de nomes sem provar contradição. | **Baixa a moderada, probatória/editorial.** Impede comparar refinamentos literalmente. Há risco de tratar status validado como se provasse conteúdo semântico completo. | **NÃO BLOQUEANTE PARA GATE 3 — CONDICIONAL** | A lacuna pode permanecer registrada se a suficiência for julgada pela explicação separada e explícita das origens, sem depender de identidade entre termos. Se a conclusão do auditor exigir o teor literal de OD-01/02 para testar fronteiras essenciais, uma recuperação focal da origem é justificada. | Auditor independente determina materialidade probatória; responsável decide eventual recuperação/fornecimento da fonte. | Alta sobre a indisponibilidade local e falta de literal na matriz; baixa sobre o conteúdo original ausente. |

## Distinção entre publicação e prontidão conceitual

- A divergência editorial do README sobre “16 abertos” versus PSD-I02 com 14 abertos e duas baixas deliberadas é registrada como contexto de publicação. Não é objeto de correção nesta ordem e não foi alterada.
- O fato de D2 v0.2 ser candidata e de catálogos D3 não estarem publicados não se converte aqui em nova pendência nem em impacto adicional.
- Esta análise não considera se o acervo completo satisfaz requisitos de publicação, aprovação de catálogo ou encerramento formal. O escopo deste parecer é a possível relevância conceitual das lacunas focais.

## Riscos residuais

1. Leitores podem interpretar termos semelhantes como sinônimos e apagar a proveniência por fase.
2. Um status VALIDADO pode ser entendido incorretamente como semântica completa ou APROVADO.
3. A questão sobre Mantenedora pode ser resolvida informalmente por uma presunção jurídica não autorizada.
4. A ressalva de OD-02 pode ser indevidamente generalizada para toda unidade escolar ou convertida em regra técnica.
5. A ausência de literal recuperado pode ser confundida com prova de que a fonte original não o contém.

**Resultado D3:** classificações são propostas condicionais para revisão. Nenhum Gate foi avaliado; nenhum identificador formal teve estado alterado.
