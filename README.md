# Calculadora em Java

Este projeto implementa uma calculadora em Java com três tipos de operações: básicas, científicas e trigonométricas. O projeto é composto por várias classes, cada uma dedicada a um tipo de cálculo, além de uma classe `Calculator_Driver` que demonstra o uso de cada funcionalidade.

## Funcionalidades

### Calculadora Básica (`CalculadoraBasica`)
Permite operações matemáticas simples:
- **Adição**
- **Subtração**
- **Multiplicação**
- **Divisão**

### Calculadora Científica (`CalculadoraCientifica`)
Inclui operações matemáticas mais avançadas:
- **Exponenciação** - calcula `e^value` usando `Math.exp`
- **Logaritmo natural** - calcula `ln(value)` usando `Math.log`
- **Memória** - permite armazenar e recuperar valores

### Calculadora Trigonométrica (`CalculadoraTrigonometrica`)
Realiza operações trigonométricas:
- **Seno** e **Arco-Seno**
- **Cosseno** e **Arco-Cosseno**
- **Tangente** e **Arco-Tangente**

## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte forma:

src/ ├── com/ │ └── javaoo/ │ └── calculadora/ │ ├── CalculadoraBasica.java // Implementa a calculadora básica │ ├── CalculadoraCientifica.java // Implementa a calculadora científica │ ├── CalculadoraTrigonometrica.java // Implementa a calculadora trigonométrica │ └── Calculator_Driver.java // Classe de execução para testes └── README.md
