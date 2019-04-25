## Exercícios do Terminal Linux

Exercicíos sobre os comandos do terminal Linux.

 - Problema 01
 > echo Carlos Mondo
 
 - Problema 02
 > echo Carlos Mondo > cliente01.txt
 > less cliente01.txt
 
 - Problema 03
 > echo Joinville >> cliente01.txt
 
 - Problema 04
 > mkdir clientes
 > ls
 
 - Problema 05
 > mv cliente01.txt clientes
 > ls
 > cd clientes
 > ls
 
 - Problema 06
 > cp cliente01.txt cliente02.txt.bkp
 
 - Problema 07
 > rm cliente01.txt
 > ls
 
 - Problema 08
 > vi cliente.script
 > i
 > echo Carlos Mondo
 > echo Carlos Mondo > cliente01.txt
 > less cliente01.txt
 > echo Joinville >> cliente01.txt
 > mkdir clientes
 > ls
 > mv cliente01.txt clientes
 > ls
 > cd clientes
 > ls
 > cp cliente01.txt cliente02.txt.bkp
 > rm cliente01.txt
 > ls
 
   esc
   
 > :wq
 
 - Problema 09
 > rm -r clientes
 > chmod +x cliente.script
 > ./cliente.script
 
 - Problema 10
 > call
 
 Serve para imprimir o calendario
 
 > echo| cal > hoje.txt
 
 Escreve a saida do comando no arquivo hoje.txt e o pipe filtra a saída do terminal, utilizado para combinar comandos.
 
 - Problema 11
 > wget  https://gist.githubusercontent.com/leandersonandre/c8cba982f42262591be628e5397d1c3f/
 raw/bd13a3e13823708e477f99f9285f845b292714c6/cidades_sc.txt.
 
 - Problema 12
 > grep Balneario cidades_sc.txt
 
 Resultado foi trazer do arquivos todas as cidades que continham "Balneario" no nome.
 
 - Problema 13
 > grep balneario cidades_sc.txt
 
 Não traz resultado pois ele é caseSensitive, ou seja, a escrita deve ser igual, sendo sensivel a qualquer tipo de diferença
 
 - Problema 14
 > grep "do Sul" cidades_sc.txt
 
 Resultado foi trazer do arquivos todas as cidades que continham "do Sul" no nome
 
 - Problema 15
 > cat cidades_sc.txt | grep "Balneario *"
 
 - Problema 16
 > echo | cat cidades_sc.txt | grep "Balneario *" > balneario.txt
 
 - Problema 17
 > tar -cf compactado.tar balneario.txt
 
 - Problema 18
 > tar -xf compactado.tar
