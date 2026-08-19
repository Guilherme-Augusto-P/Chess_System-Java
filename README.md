# ♟️ Chess System - Java

<p align="center">
  <a href="#-english">🇺🇸 English</a> • 
  <a href="#-português">🇧🇷 Português</a>
</p>

---

## 🇺🇸 English

A terminal-based chess system developed in Java. This project was built to apply and solidify core computer science concepts, serving as a practical laboratory for advanced Java programming.

**Table of Contents:**
* [What I Learned](#-what-i-learned)
* [Key Features](#-key-features)
* [How to Run](#️-how-to-run)

### 🧠 What I Learned
Developing this system from scratch provided hands-on experience with critical software engineering concepts:
* **Object-Oriented Programming (OOP):** Deep application of Encapsulation, Inheritance, Polymorphism, and Abstract Classes to effectively model piece behaviors and game rules.
* **Data Structures:** Advanced manipulation of 2D Arrays (matrices) to control the board grid, coordinate systems, and piece positions.
* **Exception Handling:** Designing custom exceptions (`BoardException` and `ChessException`) to protect the domain logic, ensuring the program handles invalid moves safely instead of crashing.
* **Collections & Streams API:** Practical use of Lists and Streams to filter, map, and evaluate complex board states, such as detecting Check and Checkmate dynamically.
* **Terminal UI:** Managing console output and styling using ANSI escape codes for a better user experience.

### 🌟 Key Features
* **Full Movement Logic:** Movement validation for every piece type (King, Queen, Bishop, Knight, Rook, and Pawn).
* **Robust Error Prevention:** Custom exceptions block invalid source/target positions and prevent players from putting their own King in check.
* **Game States:** Automatic detection of **Check** and **Checkmate**, scanning all possible moves from the opponent's remaining pieces.
* **Terminal Colors:** ANSI escape codes visually differentiate white and black pieces, and highlight possible moves for the selected piece with a blue background.

### ⚙️ How to Run
```bash
git clone [https://github.com/SEU_USUARIO/Chess_System-Java.git](https://github.com/SEU_USUARIO/Chess_System-Java.git)
cd Chess_System-Java/src
javac application/Program.java
java application.Program
```
## 🇧🇷 Português

Um sistema de xadrez para terminal desenvolvido em Java. Este projeto foi construído para aplicar e solidificar conceitos fundamentais de ciência da computação, servindo como um laboratório prático de programação avançada.

**Índice:**
* [Conhecimentos Adquiridos](#-conhecimentos-adquiridos)
* [Principais Funcionalidades](#-principais-funcionalidades)
* [Como Executar](#️-como-executar)

### 🧠 Conhecimentos Adquiridos
Desenvolver este sistema do zero proporcionou experiência prática com conceitos críticos de engenharia de software:
* **Programação Orientada a Objetos (POO):** Aplicação profunda de Encapsulamento, Herança, Polimorfismo e Classes Abstratas para modelar o comportamento das peças e as regras do jogo.
* **Estruturas de Dados:** Manipulação avançada de matrizes (Arrays 2D) para controlar a grade do tabuleiro, sistemas de coordenadas e o alcance das peças.
* **Tratamento de Exceções:** Criação de exceções personalizadas (`BoardException` e `ChessException`) para proteger a lógica de domínio, garantindo que o programa lide com movimentos inválidos de forma segura sem quebrar.
* **Collections e Streams API:** Uso prático de Listas e Streams para filtrar, mapear e avaliar cenários complexos, como a detecção dinâmica de Xeque e Xeque-Mate.
* **Interface no Terminal:** Gerenciamento de saída e estilização no console utilizando códigos de escape ANSI.

### 🌟 Principais Funcionalidades
* **Movimentação completa:** Validação de movimentos possíveis para cada tipo de peça (Rei, Rainha, Bispo, Cavalo, Torre e Peão).
* **Prevenção de Erros:** Exceções bloqueiam posições de origem/destino inválidas e impedem que o jogador coloque o próprio Rei em xeque.
* **Estados de Jogo:** Detecção automática de **Xeque** e **Xeque-Mate**, escaneando todos os movimentos possíveis das peças restantes do oponente.
* **Cores no Terminal:** Diferenciação visual entre peças brancas e pretas, além de destaque no fundo do tabuleiro em azul para exibir os movimentos possíveis da peça selecionada.

### ⚙️ Como Executar
```bash
git clone [https://github.com/SEU_USUARIO/Chess_System-Java.git](https://github.com/SEU_USUARIO/Chess_System-Java.git)
cd Chess_System-Java/src
javac application/Program.java
java application.Program
```
