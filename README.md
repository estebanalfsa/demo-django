# 🚀 Demo Django + Tailwind

![Django](https://img.shields.io/badge/Django-5.1-green?style=for-the-badge\&logo=django)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=for-the-badge\&logo=tailwind-css)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge\&logo=sqlite)

Projeto desenvolvido para a disciplina de **Programação Web**, utilizando **Django**, **Tailwind CSS**, **SQLite** e **Docker**.

## 📌 Sobre

A aplicação apresenta um mural de mensagens desenvolvido com Django. Os dados são armazenados em SQLite e a interface foi construída com Tailwind CSS, executando todo o ambiente através do Docker Compose.

## ✨ Funcionalidades

* 📄 Listagem de mensagens
* 🔐 Painel administrativo (`/admin`)
* 🎨 Interface responsiva com Tailwind CSS
* 🐳 Ambiente configurado com Docker

## 🛠️ Tecnologias

* Python 3.12
* Django 5.1
* Tailwind CSS
* SQLite
* Docker & Docker Compose

## 🚀 Executando o projeto

```bash
git clone <URL_DO_REPOSITORIO>
cd demo-django
docker compose up --build
```

Acesse:

* **Aplicação:** http://localhost:8000
* **Admin:** http://localhost:8000/admin

## 📁 Estrutura

```text
demo-django/
├── core/
├── home/
├── templates/
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
└── manage.py
```

## 📸 Screenshots

### Página Inicial

<img src="imagens/home.png" width="850">

### Painel Administrativo

<img src="imagens/admin.png" width="850">

### Página Nova

<img src="imagens/mensagens.png" width="850">

### Página Mensagens

<img src="imagens/Mensagens_novo.png" width="850">


### Retorno Visual 

<img src="imagens/retorno_visual.png" width="850">
---
### Página Sobre

<img src="imagens/sobre.png" width="850">

---

Desenvolvido por **Esteban Alfaro**.
