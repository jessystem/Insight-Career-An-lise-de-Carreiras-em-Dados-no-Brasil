# Insight Career: Análise de Carreiras em Dados no Brasil

##  Sobre o Projeto

Este projeto foi desenvolvido como parte do Trabalho de Graduação em **Data Science**, com o objetivo de aplicar técnicas de análise de dados, visualização interativa e arquitetura de soluções para compreender o cenário profissional da área de tecnologia no Brasil.

Utilizamos a base pública [State of Data - Brazil 2024/2025](https://www.kaggle.com/datasets/datahackers/state-of-data-brazil-20242025/data), disponibilizada pelo Data Hackers no Kaggle. A base reúne informações sobre profissionais de dados, suas habilidades, cargos, níveis de senioridade, localização e salários.

A partir dessa base, criamos o dashboard **Insight Career**, que oferece uma visão estratégica sobre:

- Distribuição de profissionais por cargo e nível  
- Salário médio por região e função  
- Habilidades mais comuns no mercado  
- Paridade de gênero e diversidade  
- Média de habilidades por profissional  

---

##  Arquitetura de Solução

Além da análise exploratória e visualização, desenvolvemos uma arquitetura de dados simulada com foco em escalabilidade e automação:

- **Camada de ingestão e transformação (ELT)** com Python  
- **Armazenamento opcional** em banco de dados Oracle ou Data Lake  
- **Agendamento de execução diária** às 2h da manhã via container  
- **Camada de visualização** com Power BI  
- **Usuários finais**: profissionais de dados, gestores e estudantes  

Essa arquitetura foi representada por meio de containers Docker, simulando um pipeline realista de dados corporativos.

---

##  Tecnologias Utilizadas

- **Power BI** → Visualização interativa e dashboards  
- **DAX** → Criação de medidas analíticas  
- **Python** → Scripts de ETL e manipulação de dados  
- **Docker** → Orquestração de containers para simulação de arquitetura  
- **Modelagem Star Schema** → Relacionamento entre dimensões e fatos  
- **Storytelling com dados** → Layout orientado à experiência do usuário  

---

## 📁 Estrutura do Repositório
**data**                  → Arquivos CSV da base Kaggle

**Insight_Career.pbix**    → Arquivo do Power BI com o dashboard

**README.me**                → Documentação do projeto

**docker**               → Scripts e estrutura da arquitetura simulada
---

##  Objetivos

- Identificar padrões salariais por cargo e região  
- Mapear habilidades mais demandadas no mercado  
- Compreender a distribuição de níveis de senioridade  
- Simular uma arquitetura de dados escalável e automatizada  

---

##  Créditos

Este projeto foi desenvolvido para fins acadêmicos como parte do curso de graduação em **Data Science**.  
Feito por : Jéssica Gambôa, Aline Formiga e Alexandre Campos.


---


