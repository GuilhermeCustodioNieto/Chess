### **Projeto de Xadrez**

---

# **Projeto de Xadrez**

Este projeto é um jogo de xadrez usando java para testar minhas habilidades com Java e POO. Ele é um projeto vindo do curso de Java do professor Nélio Alves.

---

## **Arquitetura do Projeto**

A arquitetura segue o padrão **MVC (Model-View-Controller)** para o backend. 

### **Estrutura Geral**
```
Chess/
  ├── Chess/
  │   ├── src/
  │     ├── application/
  │     ├── boardgame/
  │     ├── chess/
  │       ├── pieces/
  ├── Project Resources/
  └── README.md
```

### **Chess: Detalhes**
- **Arquivos Base (`application/`)**: Define os detalhes da interface e o código principal do jogo
- **Tabuleiro (`boardgame/`)**: Representa o tabuleiro e suas regras de negócio
- **Chess (`chess/`)**: Representa as entidades do jogo de xadrez e seu funcionamento.

### **Project Resouces: Detalhes**
- **Project Resources (`Project Resources/`)**: Arquivos que representam os diagramas de classe do projeto.

#### Imagens dos Diagramas
- Diagrama de Classes

<img src="Project%20Resources/class%20diagram/chess-system-design.png" alt="Diagrama de Classes">

---

## **Funcionalidades**
### **Backend**
- Jogabilidade entre mais de um usuário: Dois usuários podem jogar uma partida PvP localmente.
- Movimentação de peças: Movimentação de peças de jogo através de seus nomes no tabuleiro.

---

## **Instalação**

### **Clonar o Repositório**
```bash
git clone https://github.com/GuilhermeCustodioNieto/Chess.git
cd Chess
```

1. Execute o arquivo `Program.java`

---

## **Tecnologias Utilizadas**
- Java
- Diagrama de Classes

---

## **Contribuição**
Contribuições são bem-vindas! Para contribuir:
1. Faça um fork do projeto.
2. Crie uma branch para a feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça suas alterações e envie um pull request.

---

## **Autor**
Desenvolvido por [Guilherme Custódio Nieto](https://www.linkedin.com/in/guilherme-cust%C3%B3dio-nieto/). 🚀
