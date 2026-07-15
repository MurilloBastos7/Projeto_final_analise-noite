# 🚗 Vehicle Valuation Guide

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Flask-Web%20API-black?style=for-the-badge&logo=flask">
  <img src="https://img.shields.io/badge/Deploy-Render-46E3B7?style=for-the-badge&logo=render">
  <img src="https://img.shields.io/badge/Frontend-Lovable-purple?style=for-the-badge">
</p>

---

## 📖 Sobre o Projeto

O **Vehicle Valuation Guide** é uma aplicação web desenvolvida para estimar o valor de veículos de forma simples, rápida e intuitiva.

O sistema utiliza informações fornecidas pelo usuário, como características do veículo, para realizar uma previsão do valor utilizando um modelo de Machine Learning treinado previamente.

O projeto foi desenvolvido como **Projeto Final da disciplina de Análise de Dados**, integrando conhecimentos de:

- Ciência de Dados;
- Machine Learning;
- Desenvolvimento Web;
- Backend com Python;
- Integração Frontend + API.

---

# 🌐 Demonstração

### Frontend

https://vehicle-valuation-guide.lovable.app

### Backend (API)

https://projeto-final-analise-noite.onrender.com/

### Repositório

https://github.com/MurilloBastos7/Projeto_final_analise-noite

---

# 📸 Interface

<img width="1919" height="948" alt="Captura de tela 2026-07-15 204508" src="https://github.com/user-attachments/assets/e588af69-0d83-47c1-b150-c600c34e0c47" />

<img width="1919" height="942" alt="image" src="https://github.com/user-attachments/assets/4b25bb62-8960-497a-bf68-ed6ce9d6d57c" />

# ✨ Funcionalidades

✔️ Interface moderna

✔️ Previsão do valor de veículos

✔️ Integração entre Frontend e Backend

✔️ API REST

✔️ Modelo de Machine Learning

✔️ Respostas em tempo real

✔️ Deploy em nuvem

---

# 🛠 Tecnologias Utilizadas

## Frontend

- Lovable
- HTML5
- CSS3
- JavaScript

## Backend

- Python
- Flask
- Flask-CORS

## Ciência de Dados

- Pandas
- NumPy
- Scikit-Learn
- Joblib

## Deploy

- Render
- Lovable

## Versionamento

- Git
- GitHub

---

# 🧠 Como o projeto foi desenvolvido

O desenvolvimento foi dividido em cinco etapas principais.

## 1. Coleta e preparação dos dados

Primeiramente foi utilizado um conjunto de dados contendo informações sobre veículos, como:

- Marca
- Modelo
- Ano
- Quilometragem
- Combustível
- Transmissão
- Potência
- Demais características relevantes

Após isso foram realizados:

- limpeza dos dados;
- tratamento de valores ausentes;
- remoção de inconsistências;
- transformação das variáveis;
- preparação para treinamento.

---

## 2. Treinamento do modelo

Após o pré-processamento foi treinado um modelo de Machine Learning responsável por aprender o comportamento dos preços dos veículos.

O modelo foi salvo utilizando **Joblib**, permitindo que fosse carregado posteriormente pela API sem necessidade de novo treinamento.

---

## 3. Desenvolvimento da API

Foi criada uma API em Flask responsável por:

- receber os dados enviados pelo Frontend;
- validar as informações;
- processar os dados;
- realizar a previsão utilizando o modelo treinado;
- devolver o valor previsto em formato JSON.

---

## 4. Desenvolvimento da interface

O Frontend foi desenvolvido utilizando o Lovable, proporcionando uma interface moderna, responsiva e fácil de utilizar.

O usuário apenas informa os dados do veículo e recebe instantaneamente a estimativa de preço.

---

## 5. Deploy

Após os testes, a aplicação foi publicada.

Frontend:
Lovable

Backend:
Render

Assim qualquer pessoa pode utilizar o sistema diretamente pelo navegador.

---

# ⚙ Como executar o projeto localmente

## 1. Clone o repositório

```bash
git clone https://github.com/MurilloBastos7/Projeto_final_analise-noite.git
```

Entre na pasta

```bash
cd Projeto_final_analise-noite
```

---

## 2. Crie um ambiente virtual

Windows

```bash
python -m venv venv
```

Linux/Mac

```bash
python3 -m venv venv
```

---

## 3. Ative o ambiente virtual

Windows

```bash
venv\Scripts\activate
```

Linux

```bash
source venv/bin/activate
```

---

## 4. Instale as dependências

```bash
pip install -r requirements.txt
```

---

## 5. Execute a aplicação

```bash
python app.py
```

ou

```bash
flask run
```

A aplicação ficará disponível em:

```
http://localhost:5000
```

---

# 🔄 Fluxo da aplicação

```text
Usuário

↓

Frontend (Lovable)

↓

API Flask

↓

Modelo Machine Learning

↓

Predição

↓

Resposta JSON

↓

Frontend

↓

Resultado na tela
```

---

# 📦 Estrutura do Projeto

```text
Projeto_final_analise-noite/

│

├── model/
│   └── modelo.joblib
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│
├── static/
│
├── data/
│
└── notebooks/
```

*A estrutura pode variar conforme a organização do projeto.*

---

# 📡 API

## Endpoint

```
POST /predict
```

### Exemplo de requisição

```json
{
    "brand": "Toyota",
    "year": 2020,
    "km": 45000,
    "fuel": "Gasolina"
}
```

### Exemplo de resposta

```json
{
    "predicted_price": 89500.75
}
```

---

# 🚀 Melhorias Futuras

- Login de usuários

- Histórico de consultas

- Dashboard

- Gráficos

- Upload de planilhas

- Comparação entre veículos

- Novos modelos de Machine Learning

- Melhor desempenho

- Docker

- Testes automatizados

---

# 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos sobre:

- Python

- Flask

- APIs REST

- Machine Learning

- Ciência de Dados

- Deploy

- Git

- GitHub

- Integração Frontend + Backend

- Versionamento

---

# 🤝 Contribuição

Contribuições são sempre bem-vindas.

Caso queira contribuir:

1. Faça um Fork

2. Crie uma Branch

```bash
git checkout -b minha-feature
```

3. Faça o Commit

```bash
git commit -m "Minha melhoria"
```

4. Faça o Push

```bash
git push origin minha-feature
```

5. Abra um Pull Request

---

# 👨‍💻 Autor

**Murillo Bastos**

GitHub:

https://github.com/MurilloBastos7

---

# 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos e de estudo.

Sinta-se livre para utilizar como referência em seus próprios projetos.

---

## ⭐ Se este projeto foi útil

Não esqueça de deixar uma ⭐ no repositório!
