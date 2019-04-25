## Shell Script

Exercicíos sobre Shell Script.

 Problema 1
 
 ```shell
 vi problema1.sh
 i
 #!/usr/bash
 echo Digite seu nome:
 read nome
 echo Bom dia $nome
 esc
 :wq
 chmod +x problema1.sh
 sh problema1.sh
 ```
 
 Problema 2
 ```shell
 vi problema2.sh
 i
 #!/usr/bash
 echo Digite o primeiro Numero:
 read x
 echo Digite o segundo Numero:
 read y
 r=$(($x*$y))
 echo Resultado: $r  
 esc
 :wq
 chmod +x problema2.sh
 sh problema2.sh 
 ```
 
 Problema 3
 ```shell
 vi problema3.sh
 i
 #!/usr/bash
 echo Numero:
 read x
 if [ $x -gt 0 ]; then
    echo Positivo
 elif [ $x -lt 0 ]; then
    echo Negativo
 else
    echo Zero
 fi  
 esc
 :wq
 chmod +x problema3.sh
 sh problema3.sh 
 ```
 
 Problema 4
 ```shell
 vi problema4.sh
 i
 #!/usr/bash
 echo Numero
 read x
 contador=0
 while [ $contador -le 10 ]; do
    echo $x x $contador = $(($x*$contador))
    contador=$(($contador+1))
 esc
 :wq
 chmod +x problema4.sh
 sh problema4.sh 
 ```
 
 Problema 5
 ```shell
 vi problema4.sh
 i
 #!/usr/bash
 echo Opcoes:
 echo -------
 echo 1: Calendario
 echo 2: Lista de arquivos do diretório
 echo -------
 echo Informe sua opcao:
 read opcao
 echo -------
 if [ $opcao == 1 ]; then
    echo Mostrar calendario
    echo 
    cal
 elif [ $opcao == 2 ]; then
    echo Mostrar arquivos do diretorio
    ls
 else
    echo Essa opcao nao existe
 fi
 esc
 :wq
 chmod +x problema4.sh
 sh problema4.sh 
 ```
