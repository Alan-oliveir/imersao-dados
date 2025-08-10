# 📊 Dashboard de Análise de Salários na Área de Dados

Um dashboard interativo desenvolvido com Streamlit para análise e visualização de dados salariais na área de ciência de dados. O projeto permite explorar tendências salariais, comparar diferentes níveis de senioridade, tipos de contrato e distribuições geográficas.

## 🚀 Funcionalidades

- **Filtros Interativos**: Filtragem por ano, senioridade, tipo de contrato e tamanho da empresa
- **Métricas Principais**: Visualização de KPIs como salário médio, máximo, total de registros e cargo mais frequente
- **Visualizações Avançadas**:
  - Top 10 cargos por salário médio (gráfico de barras)
  - Distribuição de salários (histograma)
  - Proporção dos tipos de trabalho (gráfico de pizza)
  - Mapa mundial com salários médios por país para Cientistas de Dados
- **Tabela Detalhada**: Visualização completa dos dados filtrados

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Streamlit** - Framework para criação de aplicações web
- **Pandas** - Manipulação e análise de dados
- **Plotly Express** - Visualizações interativas
- **NumPy** - Computação numérica

## 📋 Pré-requisitos

- Python 3.7 ou superior
- pip (gerenciador de pacotes Python)

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/imersao-dados.git
cd imersao-dados
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

## ▶️ Como Executar

1. No terminal, navegue até o diretório do projeto
2. Execute o comando:
```bash
streamlit run app.py
```
3. O dashboard será aberto automaticamente no seu navegador (geralmente em `http://localhost:8501`)

## 📊 Fonte dos Dados

Os dados utilizados são provenientes de uma pesquisa sobre salários na área de ciência de dados, contendo informações sobre:
- Ano de trabalho
- Nível de senioridade (junior, pleno, senior, executivo)
- Tipo de contrato (integral, parcial, contrato, freelancer)
- Cargo/função
- Salário em USD
- País de residência
- Regime de trabalho (presencial, remoto, híbrido)
- Tamanho da empresa (pequena, média, grande)

## 📁 Estrutura do Projeto

```
imersao-dados/
│
├── app.py                    # Aplicação principal do Streamlit
├── requirements.txt          # Dependências do projeto
├── imersao_dados.ipynb      # Notebook com análise exploratória
├── dados-imersao-final.csv  # Dataset processado
├── README.md                # Documentação do projeto
└── LICENSE.md               # Licença do projeto
```

## 🔍 Análise dos Dados

O projeto inclui um notebook Jupyter (`imersao_dados.ipynb`) com:
- Análise exploratória dos dados
- Limpeza e preparação dos dados
- Transformação de categorias
- Visualizações preliminares com Matplotlib e Seaborn

## 🎯 Principais Insights

O dashboard permite identificar:
- Tendências salariais por nível de senioridade
- Diferenças regionais nos salários
- Distribuição dos tipos de trabalho (remoto vs presencial)
- Cargos mais valorizados no mercado
- Impacto do tamanho da empresa nos salários

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.

## 👨‍💻 Autor

Desenvolvido como parte de uma imersão em análise de dados com Python.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
