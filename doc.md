
# 📝 CRUD-HACKTHON

## Descrição

CRUD-HACKTHON é um projeto Django que implementa operações CRUD (Create, Read, Update, Delete) para gerenciamento de produtos. O projeto utiliza **Django 6.0.5** e **Django REST Framework**, seguindo as melhores práticas de desenvolvimento web em Python.

##

## Tecnologias Utilizadas
- **Frontend:** HTML (templates Django)  
- **Backend:** Python 3.x, Django 6.0.5, Django REST Framework 3.17.1  
- **Banco de Dados:** SQLite (padrão do Django)  
- **Outras bibliotecas:** Gunicorn, Whitenoise, SQLParse, ASGIRef, Packaging

---

- Python 3.x
- Django 6.0.5
- Django REST Framework 3.17.1
- Gunicorn 26.0.0
- Whitenoise 6.12.0
- SQLParse 0.5.5
- ASGIRef 3.11.1
- Packaging 26.2

---


# Instalação

## Configuraçâo

git clone https://github.com/Fernando-CR19/CRUD-HACKTHON.git
cd CRUD-HACKTHON

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

pip install -r requirements.txt

python manage.py migrate

## Execuçâo

python manage.py runserver

---

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

```



### Passos de Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/Fernando-CR19/CRUD-HACKTHON.git
