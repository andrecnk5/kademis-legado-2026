# KADEMIS — Registro de dependências, riscos e critérios de parada (D2-SUF-01)

**Classificação:** controle de continuidade proposto para Governança, com decisões humanas de recebimento preservadas; **não** modifica o PSD-I02.

| Ref. local | Questão | Evidência já recebida | Estado probatório | Condição objetiva de reabertura ou resolução | Risco de encerramento indevido |
|---|---|---|---|---|---|
| `SUF-A1-META` | Exportação nativa de 3.10 / timestamp e contexto M06 | NAT-A-01/02/03 com ato humano completo e conteúdo decisório | PARCIAL / RESSALVA ACEITA | Novo export verificável ou metadados de mensagem; nenhum novo ciclo de pesquisa em relatório derivado | Falsa precisão cronológica ou equivalência byte a byte |
| `SUF-A2-L4` | Bloco original e ato humano de L4 | Oito rótulos em registros derivados | NÃO COMPROVADO PRIMARIAMENTE | Sequência nativa completa anterior → ato → posterior obtida no verdadeiro chat `Fase 3.10-1` | Aprovação fabricada de oito enunciados |
| `SUF-A2-L5` | Bloco original e ato humano de L5 | Dez rótulos e fragmento derivado “Validado, dê andamento” | NÃO COMPROVADO PRIMARIAMENTE | Mesma sequência L5, com objetos e ressalvas | Aprovação individual presumida dos dez objetos |
| `SUF-A2-L6` | Bloco de auditoria original e ato humano L6 | Cinco rótulos e fragmento derivado “Validado, siga” | NÃO COMPROVADO PRIMARIAMENTE | Mesma sequência L6, com natureza da validação comprovada | Confundir auditoria transversal com execução histórica L6 |
| `SUF-B-EVTEXEC10` | Origem da aprovação nominal do evento em 3.7 | Transição 3.7 + declaração humana nominal em 3.8 + adendo PR #17 | ORIGEM NÃO COMPROVADA | Surgimento de ato/proposta originários com texto e sequência verificáveis | Retroagir aprovação ou ignorar declaração humana posterior |
| `SUF-C-I03R05` | Identidade original do dossiê D1–D7 | Termo derivado e snapshots com hashes diferentes | VÍNCULO HISTÓRICO NÃO COMPROVADO | Localizar ZIP original, manifesto de saída e mensagem de entrega/aceite com identidades verificáveis | Inventar manifesto retroativo ou revogar aceite por não localização |

## Priorização proporcional

**Nenhuma repetição automática de buscas sem fonte nova.** A Governança pode utilizar a documentação disponível para avaliar riscos e continuidade dentro das decisões e Gates já aprovados, mas **não deve declarar suficiência documental plena** enquanto estes elementos essenciais seguirem sem prova ou decisão competente de tratamento.

Se houver acesso eficaz ao chat original `Fase 3.10-1`, a prioridade é **apenas recuperar as três tríades**, sem recompilar os 35 registros ou reiniciar a Fase 3.9. A2 permanece uma pendência **probatória**, e não um pedido para validar novamente o domínio. A ausência do ZIP C não bloqueia o registro das demais evidências, mas bloqueia a afirmação de cadeia histórica íntegra.

**Categoria de bloqueio:** `BLOQUEANTE para declaração de completude probatória`; `NÃO AUTORIZA avanço de fase`. Determinar se cada lacuna bloqueia *um uso futuro específico* exige avaliação vinculada a tal uso; não reinterpretar o Gate 3 já aprovado como reaberto.
