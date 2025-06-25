# E-Shop Brasil - CRUD MongoDB com Streamlit e Docker

# Descrição
Projeto de aplicação para gerenciamento de dados de uma loja virtual (E-Shop Brasil), permitindo operações CRUD (Criar, Ler, Atualizar e Deletar) para clientes e produtos.  
Utiliza MongoDB como banco NoSQL, Streamlit para interface web e Docker para containerização.

# Estrutura
- `docker-compose.yml`: Configuração dos containers MongoDB e Streamlit.
- `app/`: Código do aplicativo Streamlit, incluindo arquivos `main.py`, `db.py`, `Dockerfile` e `requirements.txt`.
- `data/`: Scripts para gerar dados fake para clientes e produtos usando Faker.
- `data/seed_clientes.py`: Script para popular a coleção `clientes`.
- `data/seed_produtos.py`: Script para popular a coleção `produtos`.

# Como executar

1. Clone o repositório:

```bash
git clone https://github.com/Vanessa731-ca/e-shopbrasil-.git
cd e-shopbrasil-
