# Prevendo o Valor de uma Pizza

Este é um projeto simples em **Python** utilizando **Streamlit** e **Scikit-Learn** para prever o preço de uma pizza com base em seu diâmetro. Ele demonstra de forma prática o uso de **regressão linear** para aprendizado de máquina.

---

## Tecnologias Utilizadas
- [Python 3.8+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-Learn](https://scikit-learn.org/)

---

## Instalação

1. Clone este repositório ou baixe os arquivos:
   ```bash
   git clone https://github.com/jgafarias/Machine-Learning.git
   cd Machine-Learning
   ```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/macOS
   .venv\Scripts\activate     # Windows
   ```

3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

---

## Estrutura do Projeto
```
machine-learning
├── pizzas.csv              # Base de dados com diâmetro e preço
├── app.py                  # Código principal do Streamlit
├── requirements.txt        # Lista de dependências do projeto
└── README.md               # Este arquivo
```

---

## Como Executar o Projeto

Após instalar as dependências, execute o comando abaixo:

```bash
streamlit run app.py
```

O Streamlit abrirá automaticamente no navegador (geralmente em `http://localhost:8501`).

---

## 📈 Exemplo de Uso

Digite o diâmetro da pizza e o modelo exibirá o **preço previsto** com base na regressão linear treinada a partir dos dados do arquivo `pizzas.csv`.

---

## Exemplo de Dataset (`pizzas.csv`)
```csv
diametro,preco
20,50
22,55
24,60
26,65
28,70
30,75
32,80
34,85
36,90
38,95
40,100

```

---

## Conceito Envolvido
Este projeto usa **Regressão Linear Simples** — uma técnica de aprendizado de máquina supervisionado que busca modelar a relação entre uma variável independente (`diametro`) e uma dependente (`preco`).

A equação do modelo é:
```
preco = a * diametro + b
```

## Autor
Desenvolvido por **João Gabriel**
Com base no video: [Seu primeiro projeto de Inteligência Artificial com Python (usando Machine Learning)](https://www.youtube.com/watch?v=bGwdwF1vlvQ&t=1239s)

📸 Instagram: [@personal.raffaelaraujo](https://instagram.com/personal.raffaelaraujo)

