# Analise eleitoral

Trabalho desenvolvido por <a href="https://github.com/paisdegales">Carlos Daniel</a> e <a href="https://github.com/Propato">David Propato</a> na matéria de POO na UFES sobre orientação do professor João Paulo Andrade Almeida, no 4º período (2021/2).

Este é o segundo trabalho da disciplina e consiste em implementar um sistema em C++ capaz de processar dados obtidos da Justiça Eleitoral referentes à votação de vereadores, de forma a levantar informações e gerar relatórios sobre as eleições de 2020 em um município, a fim de aplicar e desenvolver os conhecimentos adquiridos em aula. 

Através da linha de comando, quando se executo o programa são passados os endereços de arquivos de entrada que contém as informações dos candidatos e partidos de onde se extrairá e processará os dados, bem como a data da eleição.

## Ferramentas utilizadas

<table>
    <tr align="center">
        <td>
            <img alt="Icone C++" title="C++" height="60" src="https://user-images.githubusercontent.com/84464307/226507356-adf7cb38-b2d5-48ea-b708-db7c8c35d58a.svg">
        </td>
        <td>    
            <img alt="Icone GNU Makefile" title="GNU Makefile" height="60" src="https://user-images.githubusercontent.com/84464307/224509679-b957b786-f83a-403a-b088-7132a54bd024.svg">
        </td>
        <td>
            <img alt="Icone Git" title="Git" height="60" src="https://user-images.githubusercontent.com/84464307/224510001-3e60f54c-2a0a-4ae9-bee6-f5b10df9ecf1.svg">
        </td>
    </tr>
    <tr align="center">
        <td>
            C++
        </td>
        <td>    
            GNU Makefile
        </td>
        <td>
            Git
        </td>
    </tr>
</table>

## Conteúdo

- Os arquivos .cpp e .h de todas as classes e o Client.h.
- Uma pasta com testes disponibilizados pelo professor que contém um script que executa os códigos e compara com as saídas geradas com as saídas esperadas automaticamente, indicando caso haja diferenças.
- E uma arquivo Makefile para compilar e executar os códigos. 

## Comandos do build

- `make all` Compilar
- `make run` Rodar programa/build
- `make clean` Deletar arquivos-objeto e executavel do diretorio

## Bugs conhecidos:

- para as exceções de conversão de string para inteiro, a linguagem só reconhece erro na conversão quando as letras estão no inicio, ex:
>56hhg767, usando a função stoi() receberemos 56.
>er4556yt7, usando a mesma função, receberemos uma exceção.

## Nota - 9.75

![File Structure](https://user-images.githubusercontent.com/84464307/226508055-28bee83c-eea2-46ea-adc9-2e18927171c2.png)
![File Structure](https://user-images.githubusercontent.com/84464307/226508060-632cc929-820f-4a3c-aa2b-193a47170ba1.png)
![File Structure](https://user-images.githubusercontent.com/84464307/226508067-98858c3c-5fb7-4920-b180-4ef0a1270bdb.png)
![File Structure](https://user-images.githubusercontent.com/84464307/226508078-1d5f50c0-2680-4216-b63a-ea7edd0364cf.png)

<h5 align="center">by David Propato <a href="https://github.com/Propato">@Propato</a></h5>
