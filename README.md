# Tela de Votação em Java

Este projeto é uma aplicação simples em Java com interface gráfica (GUI) utilizando o Swing, que determina se uma pessoa pode votar com base no ano de nascimento informado.

## Descrição

A aplicação solicita ao usuário o **ano de nascimento**, calcula sua **idade** e informa se a pessoa tem direito ao voto, com base nas seguintes condições:
- **Menor de 16 anos**: Não pode votar.
- **Entre 16 e 18 anos** ou **maior que 70 anos**: Voto opcional.
- **Entre 18 e 70 anos**: Voto obrigatório.

## Funcionalidades

- Entrada do **ano de nascimento**.
- Cálculo automático da **idade** com base no ano atual.
- Exibição do resultado do **direito ao voto**:
  - **Não Vota!**
  - **Voto Opcional**
  - **Voto Obrigatório**

## Requisitos

- Java 8 ou superior.
- IDE como NetBeans, IntelliJ IDEA ou Eclipse para compilar e executar o projeto.

## Estrutura do Projeto

- **TelaVoto.java**: Arquivo principal contendo a lógica de interface gráfica (GUI) e cálculo da idade.
- **Pacote**: O código está no pacote `cursoemvideo.voto`.

## Como Usar

1. **Baixe o projeto** ou **clone o repositório**.
2. Abra o projeto na sua IDE preferida.
3. Compile e execute o arquivo `TelaVoto.java`.
4. Digite o **ano de nascimento** na caixa de texto e clique no botão **"Posso Votar?"**.
5. A idade será exibida, e o resultado sobre o direito ao voto será mostrado logo abaixo.

## Exe
