Trabalho 1 - Disciplina Técnicas de Programação 1


117889 - Turma B

Aluno: 17/00500084 

Professor: Washington Almeida


Sistema Operacional: Ubuntu 18.04

Compilador: gcc/g++ (7.4.0)

Linguagem: C++11

Framework de teste: gtest



Para compilação é necessário a instalação do Framework de teste GTEST:

    - Instruções para instalação do gtest:

        $ sudo apt-get install libgtest-dev

        $ sudo apt-get install cmake

        $ cd /usr/src/gtest

        $ sudo cmake CMakeLists.txt

        $ sudo make

        $ sudo cp *.a /usr/lib

Instruções para compilação dos testes unitários:

    - Makefile:
    
        - Dentro do terminal, no arquivo onde está o makefile para compilar e rodar os testes basta utilizar os comandos:
        
            - $ make testeUsuario:
            
                - Realiza o teste de usuário 
                
                
            - $ make testeJogo:
            
                - Realiza o teste de jogo
                
                
            - $ make testePartida:
            
                - Realiza o teste de partida 
                
                
            - $ make testeCartao:
            
                - Realiza o teste de cartão 
                
                
            - $ make testeIngresso:
            
                - Realiza o teste de ingresso 

