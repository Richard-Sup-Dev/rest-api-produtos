# 📦 REST API de Produtos

Este projeto é uma **API REST** desenvolvida com **Spring Boot**, que permite gerenciar produtos (CRUD completo).  
Ele foi criado com fins de estudo e prática de **Java + Spring Boot + JPA + Maven**.

---

## 🚀 Tecnologias Utilizadas
- **Java 21**
- **Spring Boot 3**
- **Spring Web**
- **Spring Data JPA**
- **Hibernate**
- **H2 Database** (memória)
- **Maven**

---

## ⚙️ Funcionalidades
- Criar produto
- Listar todos os produtos
- Buscar produto por ID
- Atualizar produto
- Deletar produto

---

## 📂 Estrutura do Projeto
```bash
src/main/java/br/com/dio
│── Controller
│   └── ProdutoController.java
│── entity
│   └── Produto.java
│── repository
│   └── ProdutoRepository.java
│── service
│   └── ProdutoService.java
└── rest_api_project
    └── App.java
▶️ Como Rodar o Projeto
Clone o repositório:

bash
Copiar código
git clone https://github.com/SEU_USUARIO/seu-repo.git
Entre na pasta do projeto:

bash
Copiar código
cd seu-repo
Compile e rode com Maven:

bash
Copiar código
mvn spring-boot:run
Acesse no navegador ou Postman:

bash
Copiar código
http://localhost:8080/produtos
🔗 Endpoints da API
Método	Endpoint	Descrição
GET	/produtos	Lista todos os produtos
GET	/produtos/{id}	Busca produto por ID
POST	/produtos	Cria um novo produto
PUT	/produtos/{id}	Atualiza um produto
DELETE	/produtos/{id}	Deleta um produto

👨‍💻 Autor
Richard Itsou Lima
📌 Estudante de Análise e Desenvolvimento de Sistemas (UNIP)
📌 Entusiasta em Java, Spring Boot e projetos backend.
