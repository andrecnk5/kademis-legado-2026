# Triagem técnica dos 314 arquivos — 22/10/2026

Referência: main `a9a59d7b19f16ec2084fa3e7c5f910b787e486c3`, 129 arquivos. Execução pelo próprio assistente, sob autorização operacional contínua. Complementa o inventário de19/10 sem modificar sua fotografia.

## Resultado

Foram obtidos os bytes dos314arquivos inventariados, totalizando24.223.973bytes. Todos os tamanhos corresponderam aos metadados consultados. A comparação usa SHA-256 para agrupamento e Git blob para identidade exata com a árvore remota. O [CSV](Triagem_Acervo_314_20261022.csv) fornece uma linha por identidade externa, hash, classe, caminho publicado ou exemplar do grupo e ação.

| Classe operacional exclusiva | Identidades |
|---|---:|
| Bytes idênticos a arquivo da main | 59 |
| Duplicata externa exata de outro exemplar, sem correspondência direta na main | 13 |
| Pacote representativo com algum membro idêntico à main | 35 |
| Pacote representativo sem membro idêntico à main | 37 |
| Arquivo externo representativo sem bytes idênticos na main | 170 |
| Total | 314 |

Os314arquivos têm289hashes distintos:25identidades além do primeiro exemplar são duplicações exatas. Essa contagem atravessa as classes; não somar25às13duplicatas externas da tabela. Os59exemplares idênticos correspondem a47caminhos distintos da main, por causa de duplicações e caminhos com mesmo conteúdo.

Foram inspecionados75ZIPs, incluindo duplicatas de pacote. CRC de todos os pacotes acessados sem erro. A inspeção recursiva registrou3.835ocorrências de membros, incluindo membros aninhados e ZIPs internos; são518hashes distintos nesse conjunto. Há1.279ocorrências idênticas a arquivos remotos, com repetição entre pacotes. Nenhuma dessas contagens é quantidade de decisões, aprovações ou lacunas.

Dos170arquivos externos representativos,120também aparecem com os mesmos bytes em pacotes acessados. Restam50sem essa correspondência adicional neste recorte; isso define uma fila de exame, não50lacunas novas. O CSV identifica os contêineres pelo ID de custódia quando houve correspondência, limitado a três exemplos por linha.

## Consequência operacional

- Para os59exemplares idênticos, usar o caminho existente; nenhuma nova publicação é necessária para preservar esses mesmos bytes.
- Para duplicatas, manter a rastreabilidade das identidades e escolher exemplar de guarda; nada foi excluído.
- Para pacotes e arquivos externos, o acesso do executor está comprovado nesta data. A identidade criptográfica permite planejar depósito externo controlado sem duplicação desnecessária.
- A revisão de conteúdo deve priorizar os50arquivos representativos sem identidade na main ou em outro pacote, seguida dos membros exclusivos dos pacotes. Semelhança semântica e materialidade ainda precisam de exame; hash diferente não prova conhecimento novo.
- A classificação técnica não atribui aprovação humana, versão vigente ou permissão de publicação bruta. A preservação de evidência histórica deve conservar estados e atos posteriores, sem executar contratos antigos automaticamente.

## Método, rastreabilidade e fronteiras

A listagem recursiva da pasta Kademis retornou200+114itens, com cursor final vazio, correspondentes às314identidades do inventário anterior. Foram usados os resultados completos para obtenção dos arquivos. Nenhum arquivo inventariado ficou apenas em metadados nesta rodada. O [resumo técnico](Resumo_Verificacao_314_20261022.json) discrimina contagens e ausência de erros de ZIP.

A inspeção de ZIPs foi feita em memória, sem executar conteúdo ou extrair caminhos arbitrários. Houve limite de profundidade6 e100MBpor membro; nenhum erro/limite foi registrado. Verificar bytes e CRC não é auditoria semântica integral dos textos, autenticação das mensagens nativas ou demonstração de independência.

A identidade foi confrontada com a árvore da main, não com todas as versões históricas do Git. A cópia externa snapshot112 já registrada continua com seu escopo próprio; os314arquivos não foram enviados ao Drive nesta rodada. Acesso futuro de outro responsável e backup do histórico Git ainda não foram demonstrados por esta triagem.

O universo permanece a pasta inventariada e seus pacotes, não todos os chats ou todo conhecimento material desde o início do Projeto. A/B/C e demais limitações continuam nos controles existentes; não há novo pedido genérico de recuperação. Gate3 aprovado com ressalvas não bloqueantes;14pendências abertas+2encerramentos deliberados;BF-R02 com12propostas;Fase4nãoiniciada. Missão de espelhamento EM EXECUÇÃO/INCOMPLETA.

