# E-Shop Brasil

Sistema simples de gerenciamento de clientes e produtos usando **MongoDB**, **Streamlit** e **Docker**.  
Ideal para demonstração de habilidades com **NoSQL**, **Python** e deploy de aplicações com container.

---

# Tecnologias Utilizadas

- Python 3.12
- MongoDB 4.4
- Streamlit
- Docker e Docker Compose
- Faker (geração de dados falsos)
- Pymongo (conexão com o banco)

---

# Estrutura de Pastas

e-shop-brasil/
├── app/
│ ├── main.py # Interface Streamlit
│ ├── db.py # Conexão com MongoDB
│ ├── Dockerfile # Docker do app
│ └── requirements.txt # Dependências Python
├── data/
│ ├── seed_clientes.py # Inserção de dados fake de clientes
│ └── seed_produtos.py # Inserção de dados fake de produtos
├── docker-compose.yml # Orquestração com MongoDB
└── README.md # Este arquivo

---

# Como Rodar o Projeto

# 1. Clone o repositório:
```bash
git clone https://github.com/Vanessa731-ca/e-shopbrasil-.git
cd e-shopbrasil-

#suba os containers:
docker-compose up --build

# acesse o navegador e va para:
http://localhost:8501

#popular banco de dados (opicional)

# Para clientes
python data/seed_clientes.py

# Para produtos
python data/seed_produtos.py
