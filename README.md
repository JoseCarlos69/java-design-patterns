# Java Design Patterns

[![Gradle CI](https://github.com/gazbert/java-design-patterns/actions/workflows/gradle.yml/badge.svg?branch=master)](https://github.com/gazbert/java-design-patterns/actions/workflows/gradle.yml) 
[![Maven CI](https://github.com/gazbert/java-design-patterns/actions/workflows/maven.yml/badge.svg?branch=master)](https://github.com/gazbert/java-design-patterns/actions/workflows/maven.yml)

Um livro de receitas de padrões de projeto comumente utilizados em Java, baseados em exemplos de:

* "Design Patterns: Elements of Reusable Object-Oriented Software" - Gamma et al
* "Head First Design Patterns" - Freeman et al
* "Java Design Pattern Essentials" - Tony Brevis

Cada padrão está contido em seu próprio pacote. O Javadoc fornecerá mais detalhes e os testes unitários demonstrarão como usá-lo.

## Design Patterns

### Behavioural

1. State
1. Chain of Responsibility
1. Strategy
1. Observer
1. Command
1. Template Method
1. Visitor

### Creational

1. Builder
1. Factory Method
1. Static Factory Method / Simple Factory Method
1. Abstract Factory
1. Singleton

### Structural

1. Adapter
1. Decorator
1. Facade

## Build Guide
Você precisará do JDK 17+ instalado em sua máquina de desenvolvimento.

### Gradle
Você pode usar o wrapper Gradle incluído para construir o projeto e baixar as dependências:

```bash
./gradlew build
```

O Javadoc pode ser encontrado na pasta `<project-root>/build/docs/javadoc` após você executar a construção.

### Maven
Você pode usar o wrapper Maven incluído para construir o projeto e baixar as dependências:

```bash
./mvnw clean install
```

O Javadoc pode ser encontrado na pasta `<project-root>/target/apidocs` após você executar a construção.
