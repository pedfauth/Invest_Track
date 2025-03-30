# 📈 InvestTrack – Plataforma Web de Monitoramento de Investimentos

## 🎯 Objetivo
Desenvolver uma aplicação web para visualizar informações do mercado financeiro (ações, indicadores, etc.), utilizando dados extraídos via Web Scraping ou APIs públicas, processados por um pipeline ETL em Python, armazenados em banco de dados MySQL, e apresentados em uma interface moderna via Angular.

---

## 🧱 Tecnologias Utilizadas

| Camada           | Tecnologia                          | Finalidade                                      |
|------------------|-------------------------------------|-------------------------------------------------|
| Front-end        | Angular, HTML, CSS                  | Interface com usuário, visualização de dados    |
| Back-end         | Java (Spring Boot)                  | API REST que entrega os dados para o front      |
| ETL              | Python (Pandas, Requests)           | Extração e transformação de dados financeiros   |
| Banco de Dados   | MySQL (via MySQL Workbench)         | Armazenamento estruturado dos dados             |
| Versionamento    | Git + GitHub Desktop                | Controle de versão do código                    |
| Dev Tools        | VS Code, IntelliJ, Postman          | Desenvolvimento e testes                        |

---

## ⚙️ Funcionalidades

### 🔄 ETL em Python
- Extração de dados financeiros (via API ou scraping)
- Transformação dos dados: limpeza, cálculos de indicadores, formatação
- Carga no banco MySQL (inserção de dados com SQLAlchemy ou PyMySQL)

### 🔧 Back-end Java (Spring Boot)
- Endpoints REST:
  - `/acoes`: lista de ações
  - `/acoes/{ticker}`: detalhes de uma ação
  - `/graficos/{ticker}`: dados de gráfico
- Integração com banco MySQL via JPA (Hibernate)

### 🖥️ Front-end Angular
- Tela inicial com lista de ações e barra de busca
- Página de detalhes com:
  - Gráficos de histórico
  - Informações como variação, média móvel etc.
- Estilização com HTML/CSS + gráficos com Chart.js

## 🗓️ Cronograma Sugerido (8 Semanas)

| Semana | Tarefa                                                               |
|--------|----------------------------------------------------------------------|
| 1      | Estudo Angular, Spring Boot, Python e MySQL                          |
| 2      | Criar projeto Spring + conexão com MySQL                             |
| 3      | Desenvolver ETL em Python + carga no MySQL                           |
| 4      | Implementar API REST no back-end                                     |
| 5      | Criar front-end básico e conectar com back-end                       |
| 6      | Exibir gráficos (Chart.js) e dados detalhados                        |
| 7      | Melhorias visuais, responsividade e refino de funcionalidades        |
| 8      | Testes finais, documentação, deploy e versionamento no GitHub        |

---

## 🔐 Requisitos Não-Funcionais

- API RESTful bem estruturada
- Código limpo, modular e documentado
- Integração eficiente entre front-end, back-end e banco
- Boa experiência do usuário (UX)
- Responsividade e compatibilidade entre navegadores

---

## 🧠 Possibilidades Futuras

- Login de usuários e favoritos
- Alertas personalizados de variação
- Dashboard com comparação entre ações
- ETL automatizado via agendamento (cronjob ou script)
- Previsões de mercado de ações com LSTM em Python

---

> Desenvolvido com 💻, ☕/🧉 e 📊 para fins educacionais e de prática em desenvolvimento fullstack.



