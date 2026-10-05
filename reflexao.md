# Reflexão sobre o conflito

## O que causou o conflito?

O conflito aconteceu porque os dois integrantes alteraram a mesma linha do arquivo README.md de formas diferentes. Como as alterações foram feitas a partir da mesma versão do arquivo, o Git não conseguiu decidir automaticamente qual delas deveria permanecer.

## Como decidimos qual versão manter?

Analisamos as duas versões apresentadas pelo Git e escolhemos um título que representasse melhor o trabalho da dupla. Depois removemos os marcadores de conflito e mantivemos apenas a versão escolhida.

## Como poderíamos evitar conflitos em um projeto real?

Poderíamos executar `git pull` antes de iniciar novas alterações, manter uma comunicação melhor sobre quais arquivos cada integrante está modificando e dividir melhor as tarefas para evitar alterações simultâneas na mesma parte de um arquivo.
