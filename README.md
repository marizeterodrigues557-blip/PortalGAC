# 📌 Portal GAC – Gestão de Aprovações e Controle
Portal Gac -– Sistema de Solicitação Operacional

## 📖 Descrição do Projeto

O **Portal GAC (Gestão de Aprovações e Controle)** é um sistema web desenvolvido com o objetivo de gerenciar solicitações internas, controlar processos de aprovação e gerar relatórios administrativos de forma organizada, segura e eficiente.

O sistema permite que usuários registrem solicitações, acompanhem seu andamento, consultem histórico de operações e gerem relatórios para análise e tomada de decisão.

O Portal GAC foi projetado com foco em usabilidade, organização de dados e controle de perfis de acesso.


## 🎯 Objetivos do Sistema

### 🎯 Objetivo Geral
Desenvolver uma aplicação web para gerenciamento de solicitações internas com fluxo de aprovação e controle administrativo.

### 🎯 Objetivos Específicos

- Permitir cadastro e autenticação de usuários
- Implementar controle de acesso por perfil (ADMINISTRATIVO e SUPERVISOR)
- Registrar novas solicitações
- Gerenciar solicitações pendentes de aprovação
- Consultar histórico completo de solicitações
- Gerar relatórios administrativos
- Garantir segurança e organização das informações


## 👥 Perfis do Sistema

### 🔐 ADMINISTRATIVO
- Gerencia usuários
- Acessa relatórios completos
- Possui controle total do sistema

### 👨‍💼 SUPERVISOR
- Cria solicitações
- Consulta histórico
- Gera relatórios

## 🛠 Tecnologias Propostas

### 💻 Backend
- Java 17
- Spring Boot
- Spring MVC
- Spring Security
- JPA / Hibernate
- MySQL

### 🎨 Frontend
- HTML5
- CSS3
- JavaScript
- Thymeleaf

### 🗄 Banco de Dados
- MySQL

### 🧰 Ferramentas
- Netbeans
- Git
- GitHub
- ProjectLibre (Planejamento)
- Figma (Protótipo de Interface)
- Trello
- Dbdiagram.io

## 🏗 Arquitetura do Sistema

O sistema segue o padrão arquitetural:

Controller → Service → Repository → Database

Organização em camadas:
- Controller (Requisições HTTP)
- Service (Regras de negócio)
- Repository (Acesso ao banco)
- Model (Entidades do sistema)


## 📊 Funcionalidades Principais

- ✅ Login com autenticação
- ✅ Controle de perfil (Enum Role)
- ✅ Cadastro de solicitações
- ✅ Listagem de solicitações
- ✅ Aprovação e rejeição
- ✅ Histórico completo
- ✅ Geração de relatórios
- ✅ Dashboard administrativo

## 📁 Estrutura do Projeto

src/main/java/
├── controller
├── service
├── repository
├── model
└── config

src/main/resources/
├── templates
├── static
└── application.properties


## 🔒 Segurança

O sistema utiliza:
- Spring Security
- Controle de acesso por perfil (ROLE_ADMINTRATIVO / ROLE_SUPERVISOR)
- Criptografia de senha (BCrypt)

## 🚀 Status do Projeto

✔ Interface desenvolvida  
✔ Estrutura backend implementada  
✔ Controle de perfil configurado  
✔ Integração com banco de dados  


## 👩‍🎓 Identificação do Aluno

**Nome:** Marizete Rodrigues Brito  

**Curso:** Análise e Desenvolvimento de Sistemas - ADS  

**Disciplina:** Análise e Desenvolvimento de Projetos

**Professor(a):**   Wesley Dominices 

**Instituição:** Universidade Estadual do Maranhão - UEMA  

**Ano:** 2026  


## 📌 Considerações Finais

O Portal GAC foi desenvolvido com o objetivo de aplicar conceitos de desenvolvimento web, arquitetura em camadas, controle de acesso e boas práticas de programação, proporcionando uma solução prática para gestão de solicitações e controle administrativo.






