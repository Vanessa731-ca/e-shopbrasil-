<<<<<<< HEAD
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
=======
# Calculadora de IMC

Este projeto calcula o Índice de Massa Corporal (IMC) a partir do peso e altura informados pelo usuário. O cálculo pode ser feito tanto pelo terminal quanto por uma interface gráfica.

## Funcionalidades

- **Cálculo do IMC**: Calcula o IMC com base no peso e altura fornecidos.
- **Classificação**: Exibe a classificação de peso: Abaixo do peso, Peso normal, Sobrepeso, Obesidade.
- **Validação**: Validação das entradas para garantir que o peso e altura sejam positivos.

## Como Rodar

### No Terminal (Python):
1. Clone o repositório: `git clone https://github.com/seu-usuario/imc.git`
2. Navegue até o diretório: `cd imc`
3. Execute o programa: `python imc.py`

### Com Interface Gráfica:
Para rodar a interface gráfica, basta executar o script como qualquer outro programa Python, e uma janela será aberta para inserir os dados.

## Licença
MIT License.
>>>>>>> e25e13035840788f882efd8d4430528422467b36
