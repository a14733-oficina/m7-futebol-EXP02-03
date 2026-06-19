# ⚽ Gestão de Jogadores de Futebol - Base de Dados com Supabase

Este projeto foi desenvolvido em contexto de sala de aula, com o objetivo de melhorar as capacidades de pesquisa e alimentação da base de dados através da utilização do **Supabase**. A aplicação permite visualizar, adicionar e remover jogadores de futebol de forma simples e intuitiva.

---

## 📋 Índice

* [Objetivos](#-objetivos)
* [Estrutura da Base de Dados](#-estrutura-da-base-de-dados)
* [Funcionalidades](#-funcionalidades)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Instalação e Configuração](#-instalação-e-configuração)

---

## 🎯 Objetivos

* Desenvolver uma aplicação web para gestão de jogadores de futebol.
* Utilizar o **Supabase** como sistema de base de dados na cloud.
* Melhorar competências de pesquisa, organização e inserção de dados.
* Implementar operações CRUD básicas para gestão de informação.
* Criar uma interface simples e acessível para consulta dos registos.

---

## 🗄️ Estrutura da Base de Dados

A base de dados foi desenvolvida no **Supabase** e contém uma tabela principal para armazenamento dos jogadores.

### Tabela `Jogadores`

| Coluna    | Tipo     | Descrição                      |
| :-------- | :------- | :----------------------------- |
| `id`      | INT (PK) | Identificador único do jogador |
| `nome`    | VARCHAR  | Nome do jogador                |
| `idade`   | INT      | Idade do jogador               |
| `posicao` | VARCHAR  | Posição em campo               |
| `clube`   | VARCHAR  | Clube atual do jogador         |

---

## 🚀 Funcionalidades

* **Visualização de Jogadores**

  * Consulta da lista completa de jogadores registados.

* **Adicionar Jogadores**

  * Inserção de novos jogadores na base de dados.

* **Remover Jogadores**

  * Eliminação de jogadores existentes.

* **Pesquisa de Dados**

  * Consulta rápida da informação armazenada.

* **Integração com Supabase**

  * Comunicação direta com a base de dados online.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend:** HTML5, CSS3 e JavaScript.
* **Backend:** Supabase.
* **Base de Dados:** PostgreSQL (Supabase).
* **Ferramentas:** GitHub, VS Code.

---

## ⚙️ Instalação e Configuração

1. Clonar o repositório:

   ```bash
   git clone https://github.com/seu-utilizador/seu-repositorio.git
   ```

2. Aceder à pasta do projeto:

   ```bash
   cd seu-repositorio
   ```

3. Configurar as credenciais do Supabase:

   ```javascript
   const supabaseUrl = 'https://seu-projeto.supabase.co';
   const supabaseKey = 'sua-chave-publica';
   ```

4. Executar a aplicação através de um servidor local ou hospedagem web.

---

## 📚 Aprendizagens

Durante o desenvolvimento deste projeto foram consolidados conhecimentos em:

* Gestão de bases de dados relacionais.
* Utilização do Supabase.
* Operações CRUD.
* Pesquisa e organização de informação.
* Desenvolvimento de aplicações web.

---

*Trabalho realizado no âmbito do módulo de Redes e Bases de Dados.*
