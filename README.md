# 📌 Projeto Pontuado — Programação Web

Este projeto foi desenvolvido como parte de uma **avaliação da disciplina Programação Web**, com o objetivo de praticar conceitos fundamentais de aplicações web com Spring Boot.

## ✅ Funcionalidades

- Exibição de uma **página inicial** em: `http://localhost:8080/projeto`
- Exibição de uma **segunda página** em: `http://localhost:8080/projeto/home`
- Endpoint REST em: `http://localhost:8080/projeto/getAll`  
  Retorna um **JSON contendo 4 usuários fixos**, com os campos:  
  `id`, `nome`, `email` e `telefone`.

## 🚀 Tecnologias utilizadas

- Java 17
- Spring Boot
- Thymeleaf (para páginas HTML)
- Maven

## 🔧 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/jhugosc/ProjetoPontuado.git
   ```

2. Abra com sua IDE (recomendo IntelliJ ou VS Code com extensões Spring)

3. Rode a aplicação

4. Acesse no navegador:
   - Página inicial: `http://localhost:8080/projeto`
   - Página home: `http://localhost:8080/projeto/home`
   - JSON: `http://localhost:8080/projeto/getAll`
