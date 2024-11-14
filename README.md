# Discovering features

Use of GitHub Copilot in Java

## Requirements

Java 17, Maven

## Build and run the tests

```shell
mvn clean test
```

## Exercices

Open the provided Java project and generate suggestion from Copilot with

### 1. a comment

```java
// method to compute a bubble sort
```

### 2. a function signature

```java
public static int sum(int[] arr)
```

### 3. the in-line prompt in code

Select the previous method, open in-line prompt, and ask: _"refactor to use the stream API"_

### 4. multiple suggestions

Open the suggestions pane, and then prompt for:

```java
// memoized fibonacci function
```

### 5. chat

Open the chat, and ask: _"write parameterized tests with five examples for a generic sorting function"_

### 6. contextual menu

Select the bubble sort and in the contextual menu, click _"Simplify This"_ and then _"Generate Docs"_ or _“/docs”_ directly in prompt