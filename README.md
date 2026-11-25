# Controle de Impressora Elgin i9

Este projeto foi desenvolvido na disciplina de Construção de Algoritmos e Programação, com o objetivo de criar um sistema para controlar uma impressora térmica Elgin i9.

O programa foi desenvolvido em Linguagem C e possui 11 funcionalidades, como configurar a conexão, imprimir textos, QR Codes, códigos de barras, arquivos XML, abrir gaveta e emitir sinal sonoro. Também conta com um sistema de login com usuário e senha.

O código foi executado e testado no Dev-C++, utilizando a impressora Elgin i9.

O desenvolvimento desse projeto foi muito importante e interessante para o nosso aprendizado, pois tivemos a oportunidade de colocar em prática os conhecimentos adquiridos durante as aulas de Linguagem C. Além disso, conseguimos entender melhor como um programa pode se comunicar com um equipamento e executar diferentes funções.

## Funcionalidades do programa

O sistema possui um menu com as seguintes opções:

1. Configurar conexão
2. Abrir conexão
3. Fechar conexão
4. Imprimir texto
5. Imprimir QR Code
6. Imprimir código de barras
7. Imprimir XML SAT
8. Imprimir XML de cancelamento SAT
9. Abrir gaveta Elgin
10. Abrir gaveta
11. Emitir sinal sonoro
    
**0 - Sair do programa**

## Como executar

O programa foi desenvolvido em Linguagem C e testado no Dev-C++ com a impressora Elgin i9.

Para executar, é necessário abrir o arquivo `main.c` no Dev-C++, compilar e executar o código. Os arquivos `XMLSAT.xml`, `CANC_SAT.xml` e a biblioteca `E1_Impressora01.dll` devem estar na pasta de execução.

A DLL deve ser compatível com o compilador utilizado, seja de 32 ou 64 bits.

Também é possível compilar pelo terminal com o comando `gcc main.c -o impressora.exe` e executar o programa gerado.

## Acesso ao sistema

Usuário: `admin`

Senha: `1234`

O sistema permite até três tentativas de login. Após o acesso, o usuário pode escolher as opções do menu.

## Integrantes

- Rafaela Soares
- Júlia Dantas
- Rebecca Anjos
- Gabrielle Costa

