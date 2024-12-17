"# ETLProjectApiExtract" 

# Projeto ETL com Python - Extração de Dados via API

## 📋 Descrição
Este projeto implementa um processo ETL (Extract, Transform, Load) utilizando Python para extrair dados via API, realizar transformações necessárias e carregar em um destino específico.

## 🚀 Funcionalidades
- Extração de dados via API utilizando a biblioteca requests
- Transformação dos dados extraídos
- Carregamento dos dados processados
- Logs de execução do processo

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Requests
- Pandas
- Python-dotenv (para variáveis de ambiente)

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/ETLProjectApiExtract.git
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

## ⚙️ Configuração
1. Crie um arquivo `.env` na raiz do projeto
2. Configure as variáveis de ambiente necessárias:
```
API_KEY=sua_chave_api
API_URL=url_da_api
```

## 🔧 Como usar
1. Configure as variáveis de ambiente
2. Execute o script principal:
```bash
python src/main.py
```

## 📁 Estrutura do Projeto
```
ETLProjectApiExtract/
├── src/
│   ├── extract/
│   ├── transform/
│   ├── load/
│   └── main.py
├── tests/
├── .env
├── requirements.txt
└── README.md
```

## 📄 Licença
Este projeto está sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.

## ✒️ Autor
* **Vitor Justiniano** - [VitorJustiniano](https://github.com/VitorJustiniano)

