# SINapse_ONS

## Descrição

Este repositório contém um código simples em Python para automatizar o download das planilhas de históricos do SINapse ONS. Devido à necessidade de realizar este processo manualmente, esta solução visa facilitar a obtenção dos dados e permitir outras automações relacionadas.

## Funcionalidades

- Autenticação automática no portal SINapse ONS
- Download das planilhas de histórico de limitações
- Filtragem e organização dos relatórios por subestação
- Geração de arquivos CSV organizados em diretórios adequados

## Requisitos

- Python 3.8+
- Bibliotecas:
  - `requests`
  - `pandas`
  - `python-dotenv`

## Instalação

1. Clone este repositório:
   ```sh
   git clone https://github.com/seuusuario/SINapse_ONS.git
   cd SINapse_ONS
   ```

2. Crie um ambiente virtual e instale as dependências:
```sh
   python -m venv venv
  source venv/bin/activate  # No Windows use: venv\Scripts\activate
  pip install -r requirements.txt
   ```
3. Configure as credenciais do ONS criando um arquivo .env na raiz do projeto:
```sh
   ONS_USER=seu_usuario
   ONS_PASS=sua_senha
   ```
## USO
1. Execute o script principal:
```sh
   python main.py
   ```
2. O sistema autenticará no portal do ONS, baixará os relatórios e os salvará nos diretórios correspondentes.
```bas
SINapse_ONS/
│-- main.py  # Script principal
│-- .env  # Credenciais do ONS (não incluído no repositório)
│-- requirements.txt  # Dependências
│-- README.md  # Este arquivo
   ```
## Contribuição

Sinta-se à vontade para abrir issues e pull requests para melhorias no projeto.

## Licença
Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE para mais informações.
```ngi
Se precisar de mais alguma coisa, é só avisar! 😊
```
