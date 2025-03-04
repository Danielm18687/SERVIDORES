# 🏆 Guía para Jugar al Tic-Tac-Toe en GitHub

## 🎯 Objetivo del Juego
Tic-Tac-Toe (Tres en Raya) es un juego de dos jugadores donde el objetivo es conseguir tres marcas (X o O) en línea antes que tu oponente, ya sea en horizontal, vertical o diagonal.

---

## 📌 Cómo Jugar en GitHub
### 1️⃣ Jugar en Línea
Si quieres jugar Tic-Tac-Toe directamente en GitHub, puedes usar los siguientes métodos:

- **Usar un repositorio interactivo**: Algunos desarrolladores han creado juegos de Tic-Tac-Toe usando GitHub Pages o en la terminal.
- **Jugar a través de GitHub Copilot o en issues**: Puedes desafiar a amigos escribiendo movimientos en un issue y editándolo turno a turno.

### 2️⃣ Jugar con Código en Python
Si prefieres jugar en tu computadora, sigue estos pasos:

#### 🛠 Requisitos
- Tener instalado Python.

#### 📥 Clonar un Repositorio con el Juego
Ejemplo de clonación de un repositorio de Tic-Tac-Toe:
```bash
    git clone https://github.com/ejemplo/tictactoe.git
    cd tictactoe
    python tictactoe.py
```

#### 📝 Código Básico de Tic-Tac-Toe en Python
Si quieres escribir tu propia versión, aquí tienes un código simple:
```python
    def print_board(board):
        for row in board:
            print(" | ".join(row))
            print("-" * 9)
    
    def check_winner(board, player):
        for row in board:
            if all(cell == player for cell in row):
                return True
        for col in range(3):
            if all(board[row][col] == player for row in range(3)):
                return True
        if all(board[i][i] == player for i in range(3)) or all(board[i][2 - i] == player for i in range(3)):
            return True
        return False
    
    def tic_tac_toe():
        board = [[' ' for _ in range(3)] for _ in range(3)]
        players = ['X', 'O']
        turn = 0
    
        while True:
            print_board(board)
            row, col = map(int, input(f"Turno de {players[turn % 2]} (fila columna): ").split())
            if board[row][col] == ' ':
                board[row][col] = players[turn % 2]
                if check_winner(board, players[turn % 2]):
                    print_board(board)
                    print(f"¡{players[turn % 2]} ha ganado!")
                    break
                turn += 1
            else:
                print("Casilla ocupada. Intenta de nuevo.")
    
    tic_tac_toe()
```

### 🚀 Publicar tu Juego en GitHub
Si creaste tu propio código, puedes publicarlo en GitHub con estos pasos:
```bash
    git init
    git add .
    git commit -m "Subiendo mi juego de Tic-Tac-Toe"
    git branch -M main
    git remote add origin https://github.com/tuusuario/tictactoe.git
    git push -u origin main
```

---

## 🎮 ¡Diviértete jugando y programando!
Si tienes ideas para mejorar el juego, siéntete libre de hacer un **pull request** o compartir sugerencias en los issues. 😃

