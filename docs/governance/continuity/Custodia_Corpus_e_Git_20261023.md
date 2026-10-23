# Custódia do corpus inventariado e histórico Git — 23/10/2026

Custodiante: André. Destino previamente escolhido: Google Drive pessoal, Kademis/Backups_Documentais. Arquivo confirmado não compartilhado; nenhuma permissão foi ampliada.

[Pacote de recuperação verificado](https://drive.google.com/file/d/15Xt-XoTPLnQttltFlo-xZ0hBy8jNPwwD/view?usp=drivesdk)

| Controle | Resultado |
|---|---|
| Nome | KADEMIS_Custodia_Corpus_314_e_Historico_Git_20261023.zip |
| Drive file ID | 15Xt-XoTPLnQttltFlo-xZ0hBy8jNPwwD |
| Tamanho | 22.064.005 bytes |
| SHA-256 | e475a12541205a42adb63ad536b8e3cfb60322f0042bd6927c799c0cd9d7c999 |
| Fonte externa | 314 identidades, originais com nomes preservados por Library ID |
| Histórico Git | 69 referências anunciadas: 35 heads e 34 PR heads; nenhuma tag retornada |
| Objetos Git | 90 commits, 193 árvores e 171 blobs; hashes originais reconstruídos e conferidos |
| Commit principal congelado | 9819cac1c45df4f78cdaad9255de21b0a0d3c3cf |
| Metadados | 34 PRs e 102 coleções de comentários/revisões, todas vazias na consulta |
| Teste da cópia do Drive | SHA-256 idêntico, CRC íntegro, 324 entradas do manifesto conferidas |
| Restauração do bundle baixado do Drive | Clone mirror em diretório separado, 69 refs iguais, git fsck --full sem erro |

## Procedimento de recuperação

1. André acessa o pacote na conta pessoal. Quando necessário, concede o acesso restrito adequado ao responsável autorizado; acesso de terceiro não foi presumido.
2. Baixa o ZIP e compara SHA-256 ao valor acima. Confere MANIFESTO_SHA256.txt após a extração.
3. Abre Indice_Fontes_314.csv: cada Library ID aponta para fontes/ID/nome-original e hash. O índice de conteúdos/membros registra os pacotes aninhados. Não executar scripts, diffs ou contratos históricos automaticamente.
4. Restaura o Git: `git clone --mirror git/kademis.bundle kademis.git`; depois `git --git-dir=kademis.git fsck --full`. O bundle conserva também refs/pull. O teste anterior ao depósito restaurou 132 arquivos da main e verificou 233 links relativos de READMEs com destinos existentes.
5. Para saber o estado vigente, consulta primeiro a main e o índice de continuidade; datas/status dos documentos de evidência são históricos. Não trocar candidato por aprovado, validação em bloco por individual ou relato por turno nativo.

## Escopo e limitações

O pacote é uma fotografia imutável anterior ao registro deste depósito. Este documento e a publicação que o integra não estão nele. A cópia112 anterior foi mantida. Não há promessa de captura contínua automática, periodicidade ou retenção futura que não tenham sido definidas pelo custodiante.

Preserva todas as 314 identidades inventariadas e os objetos alcançáveis das referências anunciadas. Não inclui chats integrais, objetos Git já removidos/não anunciados, configurações e segredos do serviço GitHub ou fontes externas não inventariadas. O Figma segue histórico para consulta, sem exportação ou baseline vigente inferido.

A revisão de exposição combinou exame documental focal e varredura de conteúdos UTF-8 em busca de chaves privadas, tokens, cabeçalhos bearer, CPF formatado e campos de estudante identificado. Não houve ocorrência nos padrões; isso não é certificação universal de ausência de informação sensível. O destino é privado, sob custódia escolhida. Não houve upload a destino público.

[Teste Git](Teste_Restauracao_Git_20261023.json), [verificação do retorno](Verificacao_Retorno_Drive_20261023.json), [saldo por identidade](Saldo_Paridade_Corpus_314_20261023.csv).
