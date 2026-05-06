
## Tecnologias Utilizadas
- Python 3.x
- Django 6.0.5
- Django REST Framework 3.17.1
- Gunicorn 26.0.0
- Whitenoise 6.12.0
- SQLParse 0.5.5
- ASGIRef 3.11.1
- Packaging 26.2

## Estrutura

```plaintext
CRUD-HACKTHON/
│
├── core/                # Configurações principais do Django
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py / asgi.py
│
├── produtos/            # Aplicativo de gerenciamento de produtos
│   ├── migrations/
│   ├── __init__.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/produtos/
│       ├── produto_list.html
│       ├── produto_detail.html
│       ├── produto_form.html
│       └── produto_confirm_delete.html
│
├── manage.py            # Script de gerenciamento do Django
└── requirements.txt     # Dependências do projeto








# 📝 CRUD-HACKTHON

## Descrição do Projeto
O **CRUD-HACKTHON** é uma aplicação web desenvolvida para **criar, ler, atualizar e deletar registros** (CRUD) de maneira simples e prática.  
Foi desenvolvida como parte de um hackathon, com foco em aprendizado rápido e prática de desenvolvimento fullstack.

---

## Tecnologias Utilizadas
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express  
- **Banco de Dados:** SQLite (ou MongoDB/MySQL, ajustar conforme projeto)  
- **Outras bibliotecas:** Nodemon, Sequelize/Mongoose (ajustar conforme projeto)

---

## Funcionalidades
- ✅ Criar novos registros  
- ✅ Listar todos os registros  
- ✅ Atualizar registros existentes  
- ✅ Deletar registros  
- ✅ Validação básica de campos  
- ✅ Mensagens de sucesso ou erro

---

## Estrutura do Projeto
```plaintext
CRUD-HACKTHON/
│
├─ backend/          
│  ├─ models/        # Modelos de banco de dados
│  ├─ routes/        # Rotas da API
│  └─ server.js      # Arquivo principal do backend
│
├─ frontend/         
│  ├─ index.html     # Página principal
│  ├─ style.css      # Estilos
│  └─ script.js      # Lógica do frontend
│
├─ .gitignore
└─ README.md



---

## Instalação e Execução

### Pré-requisitos
Antes de começar, você precisa ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (v16 ou superior recomendado)  
- npm (geralmente vem junto com o Node.js)  
- SQLite (opcional, caso você use outro banco, ajuste as instruções)

### Passos de Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/Fernando-CR19/CRUD-HACKTHON.git
