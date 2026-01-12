# Projeto Smart TV em Java

Este projeto é um exercício prático em Java com o objetivo de aplicar conceitos básicos de programação orientada a objetos (POO), como criação de classes, atributos, métodos e interação entre objetos.

O sistema simula o funcionamento básico de uma Smart TV, permitindo ligar/desligar, alterar o volume e mudar de canal através de um usuário.

## Tecnologias Utilizadas

- Java (JDK 8 ou superior)
- IDE de sua preferência (IntelliJ, Eclipse, VS Code, etc.)

## Estrutura do Projeto

src
├── SmartTv.java
└── Usuario.java

## Descrição das Classes

### SmartTv

Classe responsável por representar uma televisão, contendo seus estados e comportamentos.

Atributos:
- ligada: indica se a TV está ligada ou desligada
- canal: canal atual da TV
- volume: volume atual da TV

Métodos:
- ligar(): liga a TV
- desligar(): desliga a TV
- aumentarVolume(): aumenta o volume
- diminuirVolume(): diminui o volume
- mudarCanal(int novoCanal): altera o canal da TV

### Usuario

Classe que contém o método main e simula a interação de um usuário com a Smart TV.

Responsabilidades:
- Criar um objeto SmartTv
- Exibir o estado inicial da TV
- Realizar alterações de volume e canal
- Exibir o estado final da TV

## Como Executar

1. Clone o repositório
2. Abra o projeto em uma IDE Java
3. Execute a classe Usuario.java
4. Observe a saída no console

## Exemplo de Saída

Tv ligada? false
Canal atual: 1
Volume atual: 25
Tv ligada? true
Volume atual: 26
Volume atual: 25
Canal atual: 15
Tv ligada? true
Canal atual: 15
Volume atual: 25

## Possíveis Melhorias

- Encapsular os atributos usando private
- Criar getters e setters
- Validar limites de volume e canal
- Criar um menu interativo com entrada do usuário

## Autor

Guilherme Pasqualetti
