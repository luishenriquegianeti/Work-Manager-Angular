# 🚀 WorkManager (Front-end Angular)

<p align="center">
  Plataforma para intermediação de serviços entre clientes e prestadores
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
  <img src="https://img.shields.io/badge/JSON--Server-000000?style=for-the-badge&logo=json&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge"/>
</p>

---

## 📌 Sobre o Projeto
O **WorkManager** é uma aplicação front-end desenvolvida em **Angular**, utilizando **JSON Server** para simulação de API durante o desenvolvimento.

A plataforma tem como objetivo facilitar a conexão entre clientes e prestadores de serviços, oferecendo uma interface moderna, dinâmica e de fácil utilização.

---

## 🎯 Objetivo
- Criar uma interface moderna e responsiva  
- Facilitar a navegação e usabilidade  
- Simular integração com API  
- Melhorar a experiência do usuário  

---

## ⚙️ Funcionalidades
- Cadastro de clientes e prestadores  
- Listagem de dados em tempo real  
- Sistema de busca  
- Edição e exclusão de registros  
- Consumo de API simulada com JSON Server  

---

## 🧑‍💻 Tecnologias Utilizadas
- **Angular**  
- **JSON Server**  

---

## 🔄 Integração com API
O projeto utiliza o **JSON Server** para simular uma API REST, permitindo:

- Requisições GET, POST, PUT e DELETE  
- Testes de integração front-end  
- Desenvolvimento sem necessidade de back-end real  

---

## 📋 Gerenciamento

### 📊 Listagem
- Exibição dinâmica de dados  
- Atualização em tempo real  

### ✏️ Edição
- Atualização de dados via API simulada  

### ❌ Exclusão
- Remoção de registros via requisição DELETE  

---

## 🚀 Como Executar o Projeto

```bash
# Instalar dependências
npm install

# Rodar o JSON Server
npx json-server --watch db.json

# Rodar o Angular
cd WorkManager
ng serve

# Acessar no navegador
http://localhost:4200
# Porta
Publica
