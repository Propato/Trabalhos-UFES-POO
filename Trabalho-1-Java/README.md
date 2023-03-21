# Analise eleitoral

Trabalho desenvolvido por <a href="https://github.com/paisdegales">Carlos Daniel</a> e <a href="https://github.com/Propato">David Propato</a> na matéria de POO na UFES sobre orientação do professor João Paulo Andrade Almeida, no 4º período (2021/2).

Este é o primeira trabalho da matéria e consiste em implementar um sistema em Java capaz de processar dados obtidos da Justiça Eleitoral referentes à votação de vereadores de forma a levantar informações e gerar relatórios sobre as eleições de 2020 em um município, a fim de aplicar e desenvolver os conhecimentos adquiridos em aula. 

Através da linha de comando, quando se executo o programa são passados os endereços de arquivos de entrada que contém as informações dos candidatos e partidos de onde se extrairá e processará os dados, bem como a data da eleição.

## Ferramentas utilizadas

<table>
    <tr align="center">
        <td>
            <img alt="Icone Java" title="Java" height="60" src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/java/java-original.svg">
        </td>
        <td>    
            <img alt="Icone XML" title="XML" height="60" src="https://user-images.githubusercontent.com/84464307/226507055-926ee880-402d-4748-bb5a-ffda0feda9bd.svg">
        </td>
        <td>
            <img alt="Icone Git" title="Git" height="60" src="https://user-images.githubusercontent.com/84464307/224510001-3e60f54c-2a0a-4ae9-bee6-f5b10df9ecf1.svg">
        </td>
    </tr>
    <tr align="center">
        <td>
            Java
        </td>
        <td>    
            XML
        </td>
        <td>
            Git
        </td>
    </tr>
</table>

## Conteúdo

- Os arquivos .java de todas as classes.
- Uma pasta com testes disponibilizados pelo professor que contém um script que executa os códigos e compara com as saídas geradas com as saídas esperadas automaticamente, indicando caso haja diferenças.
- E uma arquivo build para compilar e executar os códigos. 

## Comandos do build:

- `ant init` cria uma pasta bin para armazenar os arquivos .class gerados
- `ant compile` gera os arquivos .class, armazenando-os na pasta bin
- `ant run` executa o código com os argumentos de entrada especificados no build
- `ant jar` gera o arquivo .jar do código
- `java -jar vereadores.jar <entrada_teste_candidato.csv> <entrada_teste_partido.csv> <data_eleição = dd/MM/yyyy>` executar o arquivo .jar

## Bugs conhecidos:

- Apesar de lidar com as possiveis exceções encontradas, o código não para de ser executado caso alguma exceção seja capturada.

## Nota - 9.5

![File Structure](https://user-images.githubusercontent.com/84464307/226507811-a4f90fb6-dc1e-4dbb-8675-8332bab8b526.png)
![File Structure](https://user-images.githubusercontent.com/84464307/226507850-a1fd7141-42b2-49c4-b487-b580b8699184.png)
![File Structure](https://user-images.githubusercontent.com/84464307/226507857-12b242c5-e3c5-4cff-a1f0-7eeb3b62c2a8.png)
![File Structure](https://user-images.githubusercontent.com/84464307/226507862-0e9ae213-2711-49b3-b056-f4737d2e49de.png)

<h5 align="center">by David Propato <a href="https://github.com/Propato">@Propato</a></h5>
