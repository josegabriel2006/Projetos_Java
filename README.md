# 🧮 Calculadora em Java

Calculadora de console desenvolvida em Java, com suporte às quatro operações matemáticas básicas e loop de execução contínua.

## 📋 Funcionalidades

- **Soma** entre dois números inteiros
- **Subtração** entre dois números inteiros
- **Multiplicação** entre dois números inteiros
- **Divisão** entre dois números inteiros (com tratamento de divisão por zero)
- Loop interativo: o usuário pode realizar múltiplos cálculos sem reiniciar o programa

## 🚀 Como executar

### Pré-requisitos

- [JDK 11+](https://www.oracle.com/java/technologies/downloads/) instalado

### Compilando e rodando

```bash
# Clone o repositório
git clone https://github.com/josegabriel2006/Projetos_Java.git
cd Projetos_Java

# Compile
javac src/util/Calculator.java -d out

# Execute
java -cp out util.Calculator
```

## 🖥️ Exemplo de uso

```
== CALCULADORA ==
Digite um Número: 10
Digite outro Número: 3

Qual operação deseja escolher?
[1] - SOMA
[2] - SUBTRAÇÃO
[3] - MULTIPLICAÇÃO
[4] - DIVISÃO
OPERAÇÃO: 4

RESULTADO:
DIVISÃO = 3.3333333333333335

Deseja continuar (s/n)? n
```

## 🗂️ Estrutura do projeto

```
Projetos_Java/
└── src/
    └── util/
        └── Calculator.java
```

## 🛠️ Tecnologias

- Java (JDK 21)
- `java.util.Scanner` para leitura de input
- `java.util.Locale` para formatação numérica

## 👤 Autor

**José Gabriel** — [@josegabriel2006](https://github.com/josegabriel2006)
