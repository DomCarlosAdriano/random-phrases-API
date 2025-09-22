# 🎬 API ScreenMatch Frases  

API REST simples desenvolvida com **Java** e **Spring Boot** para fornecer **frases aleatórias de filmes e séries**.  

Este projeto, chamado **ScreenMatch Frases**, é uma API backend que possui um único propósito:  
📌 Servir uma frase de efeito de um personagem de filme ou série de forma **aleatória** a cada requisição.  

A API foi projetada para ser **leve** e **eficiente**, consultando um banco de dados **PostgreSQL** para buscar e retornar os dados em **formato JSON**, pronta para ser consumida por qualquer aplicação frontend.  

---

## ✨ Funcionalidade Principal  

- **Endpoint de Frase Aleatória**  
  - Retorna um objeto JSON contendo:  
    - 🎭 **Frase**  
    - 👤 **Personagem**  
    - 🎥 **Título da Obra**  
    - 🖼️ **URL de um Pôster**  
  - A frase é selecionada **aleatoriamente** do banco de dados a cada chamada.  

---

## 🛠️ Tecnologias Utilizadas  

- ☕ **Java 17**  
- 🚀 **Spring Boot** → Framework principal para a criação da API  
- 🌐 **Spring Web** → Construção do endpoint REST  
- 🗄️ **Spring Data JPA** → Persistência e consultas no banco  
- 🐘 **PostgreSQL** → Banco de dados relacional para armazenar as frases  
- 📦 **Maven** → Gerenciador de dependências e build do projeto  

---

## 📌 Endpoint da API  

Para obter uma **frase aleatória**, faça uma requisição **GET** para o seguinte endpoint:  


---

### 📋 Exemplo de Resposta  

```json
{
  "titulo": "Breaking Bad",
  "frase": "I am the one who knocks.",
  "personagem": "Walter White",
  "poster": "https://m.media-amazon.com/images/M/MV5BYmQ4YWMxYjUtNjZmYi00MDQ1LWFjMjMtNjA5ZDdiYjdiODU5XkEyXkFqcGdeQXVyMTMzNDExODE5._V1_QL75_UX380_CR0,1,380,562_.jpg"
}
```
---

📌 **Feito por DomCarlosAdriano** 🚀  
