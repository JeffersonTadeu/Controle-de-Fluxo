# 🧮 Contador com Validação de Parâmetros

Este é um projeto simples em Java, guiado pelo bootcamp da DIO - Backend Java Santander, que solicita dois números inteiros ao usuário, valida se o segundo é maior que o primeiro e então realiza uma contagem entre eles. Caso a validação falhe, uma exceção personalizada é lançada e tratada de forma amigável.

---

## 🚀 Funcionalidades

- Leitura de entrada pelo terminal
- Validação de parâmetros de forma robusta
- Lançamento de exceção customizada (`ParametrosInvalidosException`)
- Mensagens claras para o usuário

---

## 📂 Estrutura do Projeto

```
src/
├── contador/
│   └── Contador.java
└── exception/
    └── ParametrosInvalidosException.java
```

---

## 📦 Requisitos

- Java JDK 8 ou superior
- IntelliJ IDEA (opcional, mas recomendado)

---

## 🛠 Exceção Personalizada

A classe `ParametrosInvalidosException` herda de `Exception` e permite personalizar a mensagem exibida ao usuário quando os parâmetros são inválidos.

```java
public class ParametrosInvalidosException extends Exception {
    public ParametrosInvalidosException(String message) {
        super(message);
    }
}
```

---

## 📌 Autor

Jefferson Andrade  
[GitHub @JeffersonTadeu](https://github.com/JeffersonTadeu)

---
