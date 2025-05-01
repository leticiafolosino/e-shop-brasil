# 📦 E-Shop Brasil - Projeto de Banco de Dados e Big Data

## 🧾 Introdução

A **E-Shop Brasil** é uma das maiores plataformas de comércio eletrônico do país e enfrenta desafios com o alto volume de dados, personalização de experiência do cliente, segurança da informação e otimização da logística. Este projeto simula uma solução tecnológica prática utilizando **MongoDB**, **Streamlit** e **Docker**, integrando conceitos de **bancos de dados avançados** e **Big Data**.

---

## 🎯 Objetivos do Projeto

- Armazenar e manipular grandes volumes de dados de forma segura e eficiente;
- Oferecer personalização com base em comportamento de compras;
- Otimizar a logística de pedidos e controle de estoque;
- Criar um sistema escalável com tecnologias modernas de banco de dados.

---

## 🧰 Tecnologias Utilizadas

| Tecnologia     | Finalidade                                          |
|----------------|-----------------------------------------------------|
| MongoDB        | Banco NoSQL para armazenar dados semiestruturados   |
| Streamlit      | Interface gráfica para interagir com os dados       |
| Docker         | Ambientes isolados para facilitar execução e testes |
| PyMongo        | Conexão entre o app em Python e o banco MongoDB     |
| Pandas         | Manipulação e concatenação de dados                 |

---

## ⚙️ Funcionalidades da Aplicação

- Inserção de dados no banco MongoDB
- Edição e exclusão de registros
- Consulta e visualização de dados em tempo real
- Concatenação de coleções para análise cruzada

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Docker instalado na máquina

### Passo a passo

```bash
git clone https://github.com/leticiafolosino/e-shop-brasil.git
cd e-shop-brasil
docker-compose up --build
