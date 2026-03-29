# 🚀 Backend API (Ambiente de Testes)

Este projeto consiste em uma aplicação **Back-end** já implementada, pronta para ser executada localmente e disponibilizar seus endpoints para consumo.

O objetivo é facilitar a execução em ambiente de testes, com o mínimo de configuração possível.

---

## 📋 Pré-requisitos

Antes de iniciar a aplicação, certifique-se de ter instalado:

* **Java 21 ou superior**

Faça o download através do site oficial da Oracle:
👉 [Download Java 21](https://www.oracle.com/java/technologies/javase/jdk21-archive-downloads.html?utm_source=chatgpt.com)

---

## 🧠 Banco de Dados

Este projeto utiliza o **H2 Database**.

O **H2** é um banco de dados relacional leve, escrito em Java, que pode rodar em memória ou embarcado na aplicação ([Wikipedia][1]).

### 🔹 Características do H2:

* Banco **em memória (in-memory)**
* Não requer instalação externa
* Inicialização rápida
* Ideal para testes e desenvolvimento
* Os dados são apagados ao encerrar a aplicação

💡 Ou seja: sempre que o servidor for reiniciado, os dados serão resetados automaticamente.

Caso queira saber mais:
👉 [Documentação oficial do H2](https://github.com/h2database/h2database?utm_source=chatgpt.com)

---

## ▶️ Como executar o projeto

Siga os passos abaixo:

### 1. Clone o repositório

```bash
git clone https://github.com/CassioLinhares/BackEnd_dbH2_recipes.git
```
---

### 2. Descompacte a pasta do projeto, abra ela no terminal e execute:

```bash
java -jar recipes_new.jar
```
---

### 3. Execute a aplicação

```bash
java -jar recipes_new.jar
```
---

## 🌐 Acesso à aplicação

Após iniciar o servidor, a API estará disponível em:

```
http://localhost:8080/h2
```

### Configurações padrão:

* **JDBC URL:** `jdbc:h2:mem:recipe_db`
* **Usuário:** `sa`
* **Senha:** 123

---

## ⚠️ Observações importantes

* Este projeto está configurado para **ambiente de testes**
* Os dados **não são persistidos**
* Não é recomendado para produção sem ajustes (ex: banco real, segurança, variáveis de ambiente)

---

## 🧪 Uso recomendado

Este backend é ideal para:

* Testes de integração
* Desenvolvimento frontend
* Prototipação de APIs
* Estudos com Java + Spring (ou stack utilizada)

---
