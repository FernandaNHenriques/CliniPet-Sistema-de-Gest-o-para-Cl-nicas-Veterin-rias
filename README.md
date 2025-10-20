# 🐶🐱 CliniPet – Sistema de Gestão para Clínicas Veterinárias

(https://github.com/FernandaHenriques/CliniPet-Sistema-de-Gest-o-para-Cl-nicas-Veterin-rias/blob/main/wwwroot/images/logo.png)

> Sistema desenvolvido para gestão de clínicas veterinárias, permitindo o controlo de clientes, pets, agendamentos, prontuários e produtos de forma simples e intuitiva.

---

## 📋 Sumário
- [✨ Sobre o Projeto](#-sobre-o-projeto)
- [⚙️ Funcionalidades Principais](#%EF%B8%8F-funcionalidades-principais)
- [🧩 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [📸 Interface da Aplicação](#-interface-da-aplicação)
- [🔐 Segurança e Acesso](#-segurança-e-acesso)
- [🧑‍💻 Como Executar o Projeto](#-como-executar-o-projeto)
- [🗃️ Base de Dados](#️-base-de-dados)
- [👩‍🏫 Autoria](#-autoria)

---

## ✨ Sobre o Projeto

**CliniPet** é um sistema de gestão desenvolvido no âmbito do curso **Programador de Informática – IEFP (NST-PROG21)**.  
Tem como objetivo modernizar a administração de clínicas veterinárias, centralizando a gestão de **clientes, animais, funcionários, serviços, produtos, agendamentos e prontuários**.

A aplicação foi projetada para ser intuitiva, responsiva e segura, com diferentes níveis de acesso (Administrador, Funcionário e Veterinário).

---

## ⚙️ Funcionalidades Principais

✅ Gestão de **clientes** e respetivos pets  
✅ Registo e acompanhamento de **agendamentos**  
✅ Criação e consulta de **prontuários veterinários** com upload de ficheiros PDF  
✅ Gestão de **produtos e serviços**  
✅ Sistema de **login com código de verificação por e-mail**  
✅ Área separada para **Administrador** e **Funcionário/Veterinário**  
✅ Interface moderna, leve e responsiva  

---

## 🧩 Tecnologias Utilizadas

- **Linguagem:** C# (.NET 8 com Razor Pages)  
- **Framework:** ASP.NET Core Identity  
- **ORM:** Entity Framework Core  
- **Base de Dados:** SQL Server (LocalDB)  
- **Front-end:** HTML5, CSS3, Bootstrap e ícones do Bootstrap  
- **Servidor SMTP:** Brevo (para envio de códigos de acesso)  

---

## 🔐 Segurança e Acesso

O sistema implementa autenticação por **ASP.NET Core Identity**, com envio de **código de verificação via e-mail** (exceto para o Administrador).  
Cada perfil tem permissões específicas:

- **Administrador:** acesso total ao sistema  
- **Funcionário/Veterinário:** acesso a agendamentos, prontuários, produtos e serviços  


