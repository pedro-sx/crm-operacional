# CRM Operacional - Sistema de Gestão para Vendedores

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

Sistema CRM simples e operacional desenvolvido para vendedores de loja física, com foco em rapidez e usabilidade.

## 🚀 Características Principais

- **Interface limpa e intuitiva**: Pensada para usuários com pouca familiaridade com tecnologia
- **Rápido e eficiente**: Poucos cliques para realizar ações principais
- **Cálculos automáticos**: Métricas atualizadas automaticamente baseadas nas vendas
- **Modais para ações**: Não é necessário navegar entre páginas para ações comuns
- **Responsivo**: Funciona bem em tablets e computadores

## 📋 Funcionalidades Implementadas

### Clientes
- Cadastro de clientes (nome, telefone, email, observações)
- Edição de clientes
- Exclusão de clientes (apenas sem vendas registradas)
- Listagem com métricas automáticas
- Busca por nome

### Vendas
- Registro de vendas associadas a clientes
- Venda rápida (busca rápida do cliente)
- Status da venda (concluída, orçamento, cancelada)
- Cálculos automáticos das métricas

### Dashboard
- Estatísticas gerais do sistema
- Últimos clientes cadastrados
- Métricas de desempenho

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript puro (Vanilla JS)
- **Backend**: PHP 7.4+
- **Banco de Dados**: MySQL 5.7+
- **Servidor**: Compatível com servidor compartilhado (Localweb)

## 📦 Instalação

### 1. Requisitos do Sistema
- PHP 7.4 ou superior
- MySQL 5.7 ou superior
- Servidor web (Apache recomendado)

### 2. Configuração do Banco de Dados

1. Crie um banco de dados MySQL:
   ```sql
   CREATE DATABASE crm_operacional;
