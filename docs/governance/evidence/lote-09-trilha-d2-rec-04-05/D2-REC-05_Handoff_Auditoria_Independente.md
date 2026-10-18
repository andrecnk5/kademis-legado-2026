# D2-REC-05 — Handoff para AUD-D2-05

## Estado

F01–F04 executados nos limites autorizados. Pacote local/candidato, sem publicação. Parada para auditoria independente.

## Arquivos do incremento

- `D2-REC-05_Relatorio_Recuperacao_Probatoria.md`
- `D2-REC-05_Ledger_Atos_Humanos.csv` (4 linhas L3–L6)
- `D2-REC-05_Eventos_Conflitos_3_7.csv` (2 eventos; três escopos distintos)
- `D2-REC-05_Cadeia_Custodia_I03-R05.md`
- `D2-REC-05_Delta_Proposto_Nao_Aplicado.csv` (0 linhas de dados)
- `D2-REC-05_Registro_Fontes_Consultas_Hashes.csv`
- `D2-REC-05_Mapa_Pendencias_Dirigidas.md`
- matrizes protegidas, fontes recebidas, D2-REC-04 e snapshots GitHub anexos
- `SHA256SUMS.txt` e ZIP validado

## Pontos de decisão para o auditor

1. Confirmar se o trecho literal L3 exibido no contexto do projeto, sem export nativo e objeto adjacente, atende a registro de mensagem parcial; o ledger não verifica timestamp/autoria nativa.
2. Confirmar a classificação dos índices L4–L6 como pistas derivadas, mantendo como não comprovados o inteiro teor, objeto antecedente e escopo.
3. Examinar as evidências R03 sobre a inclusão de EVT-PROT-04 em bloco e o vínculo derivado EVT-EXEC-10/transição; manter três escopos separados e o conflito até obter turnos originais.
4. Confirmar a conclusão de cadeia reconstituída: hash do snapshot inicial conhecido, ZIP/manifesto histórico de entrega não localizado, vínculo não comprovado.
5. Encaminhar as solicitações A/B/C aos chats originais conforme autorização operacional, sem alterar decisões; cada retorno deve declarar mensagens efetivamente examinadas e trazer objetos/contextos e metadados.

## Proteção e limites

Os bytes dos pacotes D2-REC-01 a D2-REC-04 e das matrizes protegidas foram preservados e conferidos. Nenhum delta foi aplicado. Solicitações A–C do arquivo anexo foram incluídas no pacote; não foram enviadas nesta execução. Não se avaliou o Gate 3, não se iniciou D3–D5/Fase 4, e não se alterou repositório/sistema externo.

O `SHA256SUMS.txt` cobre todos os arquivos de conteúdo do pacote de auditoria, exceto ele próprio e o ZIP final, que é identificado pelo sidecar `.sha256` e pelo hash comunicado na entrega. Nenhum manifesto novo é alegado como histórico.

**STOP:** após este handoff, aguardar a avaliação independente AUD-D2-05.
