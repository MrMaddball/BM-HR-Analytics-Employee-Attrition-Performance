# Análise de Atrito e Desempenho de Funcionários - HR Analytics

<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_Visualizacao_Dashboard_1.png" alt="Dashboard HR Analytics" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>

## 📊 Sobre o Projeto

Este projeto de HR Analytics tem como objetivo analisar os fatores que influenciam a rotatividade (atrito) e o desempenho dos funcionários numa organização. Utilizando técnicas de análise de dados, modelação estatística e visualização, procuramos identificar padrões e insights que possam auxiliar na tomada de decisões estratégicas de recursos humanos.

## 🎯 Objetivos

- Identificar os principais fatores que contribuem para o atrito de funcionários
- Analisar o desempenho dos colaboradores em diferentes departamentos
- Criar modelos preditivos para antecipar possíveis saídas de talentos
- Fornecer recomendações baseadas em dados para melhorar a retenção de talentos
- Desenvolver dashboards interativos para monitorização contínua de métricas de RH

## 📋 Estrutura do Projeto

### Dados
O projeto utiliza um conjunto de dados de RH com informações sobre:
- Dados demográficos dos funcionários
- Histórico de desempenho
- Satisfação no trabalho
- Tempo na empresa
- Departamentos e funções
- Compensação e benefícios

### Modelação de Dados

<details>
<summary><b>Modelo OLTP (Transacional)</b></summary>
<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_OLTP_Diagrama.png" alt="Diagrama OLTP" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>
</details>

<details>
<summary><b>Modelo OLAP (Analítico)</b></summary>
<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_OLAP_Diagrama.png" alt="Diagrama OLAP" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>
</details>

<details>
<summary><b>Dicionário de Dados</b></summary>
<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_Dicionario_Dados.png" alt="Dicionário de Dados" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>
</details>

## 🔍 Análises Realizadas

### Consultas SQL

<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
  <div style="flex: 0 0 48%; margin-bottom: 20px;">
    <h4>Consulta 1</h4>
    <img src="Imagens/CA_AiDAPT01_P1_Script_SQL_Consulta_1.png" alt="Consulta SQL 1" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
  </div>
  <div style="flex: 0 0 48%; margin-bottom: 20px;">
    <h4>Consulta 2</h4>
    <img src="Imagens/CA_AiDAPT01_P1_Script_SQL_Consulta_2.png" alt="Consulta SQL 2" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
  </div>
</div>

### Joins e Análises Relacionais

<details>
<summary><b>Análise por Departamento</b></summary>
<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_Script_SQL_Joins_Pepartamento.png" alt="Joins Departamento" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>
</details>

<details>
<summary><b>Análise de Informações Pessoais</b></summary>
<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_Script_SQL_Joins_Personalinfo.png" alt="Joins Informações Pessoais" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>
</details>

<details>
<summary><b>Análise de Rotatividade</b></summary>
<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_script4_SQL._joins_Rotatividadepng.png" alt="Joins Rotatividade" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>
</details>

### Transformação de Dados
<div align="center">
  <img src="Imagens/CA_AiDAPT01_P1_Dados_Apos_Transformacoes.png" alt="Dados Após Transformações" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
</div>

## 📊 Visualizações e Dashboards

<div style="display: flex; justify-content: space-between; flex-wrap: wrap; margin-top: 20px;">
  <div style="flex: 0 0 48%; margin-bottom: 20px;">
    <h3 align="center">Dashboard Principal</h3>
    <img src="Imagens/CA_AiDAPT01_P1_Visualizacao_Dashboard_1.png" alt="Dashboard 1" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
  </div>
  <div style="flex: 0 0 48%; margin-bottom: 20px;">
    <h3 align="center">Dashboard de Métricas Detalhadas</h3>
    <img src="Imagens/CA_AiDAPT01_P1_Visualizacao_Dashboard_2.png" alt="Dashboard 2" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); max-width: 100%;" />
  </div>
</div>

## 📈 Documentos do Projeto

<div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin: 30px 0;">
  <div style="flex: 0 0 45%; background-color: #f8f9fa; padding: 20px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-bottom: 20px;">
    <h3 align="center">📊 Apresentação PowerPoint</h3>
    <div align="center">
      <img src="https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white" alt="PowerPoint" style="margin-bottom: 15px;" />
      <p>Apresentação completa do projeto com resultados, gráficos e conclusões principais.</p>
      <a href="Documentação/CA_AiDAPT01_P1_Apresentacao_Final.pptx" style="display: inline-block; background-color: #B7472A; color: white; padding: 10px 20px; text-align: center; text-decoration: none; border-radius: 5px; margin: 10px 0;">
        <b>⬇️ Descarregar Apresentação</b>
      </a>
    </div>
  </div>
  
  <div style="flex: 0 0 45%; background-color: #f8f9fa; padding: 20px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-bottom: 20px;">
    <h3 align="center">📑 Relatório de Análise em R</h3>
    <div align="center">
      <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" style="margin-bottom: 15px;" />
      <p>Análise estatística avançada incluindo exploração de dados, testes de hipóteses, modelação preditiva e visualizações.</p>
      <a href="Documentação/CA_AiDAPT01_P1_Analise_em_R.pdf" style="display: inline-block; background-color: #276DC3; color: white; padding: 10px 20px; text-align: center; text-decoration: none; border-radius: 5px; margin: 10px 0;">
        <b>📄 Ver Relatório Completo</b>
      </a>
    </div>
  </div>
</div>

## 🛠️ Tecnologias Utilizadas

<div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin: 20px 0;">
  <div style="text-align: center; margin: 10px;">
    <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
    <p>Armazenamento de Dados</p>
  </div>
  <div style="text-align: center; margin: 10px;">
    <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    <p>Armazenamento NoSQL</p>
  </div>
  <div style="text-align: center; margin: 10px;">
    <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
    <p>Análise Estatística</p>
  </div>
  <div style="text-align: center; margin: 10px;">
    <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" alt="Power BI" />
    <p>Visualização de Dados</p>
  </div>
</div>

## 📁 Estrutura de Diretórios

```
📦 HR-Analytics-Project
 ┣ 📂 Código
 ┃ ┣ 📜 CA_AiDAPT01_P1_MongoDB.docx
 ┃ ┣ 📜 CA_AiDAPT01_P1_Script_Original_Projeto.sql
 ┃ ┣ 📜 CA_AiDAPT01_P1_Scripts_MongoDB.txt
 ┃ ┗ 📜 CA_AiDAPT01_P1_report _corr.Rmd
 ┣ 📂 Dados
 ┃ ┣ 📜 CA_AiDAPT_Dicionario_de_dados.xlsx
 ┃ ┗ 📜 CA_AiDAPT_Normalizacao_Final.xlsx
 ┣ 📂 Documentação
 ┃ ┣ 📜 CA_AiDAPT01_P1_Analise_em_R.pdf
 ┃ ┣ 📜 CA_AiDAPT01_P1_Apresentacao_Final.pptx
 ┃ ┗ 📜 CA_AiDAPT01_P1_ibm_hr_data.csv
 ┣ 📂 Imagens
 ┃ ┣ 📜 CA_AiDAPT01_P1_Dados_Apos_Transformacoes.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_Dicionario_Dados.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_OLAP_Diagrama.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_OLTP_Diagrama.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_Script_SQL_Consulta_1.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_Script_SQL_Consulta_2.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_Script_SQL_Joins_Pepartamento.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_Script_SQL_Joins_Personalinfo.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_Visualizacao_Dashboard_1.png
 ┃ ┣ 📜 CA_AiDAPT01_P1_Visualizacao_Dashboard_2.png
 ┃ ┗ 📜 CA_AiDAPT01_P1_script4_SQL._joins_Rotatividadepng.png
 ┗ 📂 Visualizações
   ┗ 📜 CA_AiDAPT01_P1_Power_BI.pbix
```

## 🚀 Como Utilizar

<div style="background-color: #f8f9fa; padding: 15px; border-radius: 8px; margin: 20px 0;">
  <ol>
    <li>Clone este repositório: <code>git clone https://github.com/MrMaddball/BM-HR-Analytics-Employee-Attrition-Performance.git</code></li>
    <li>Explore os scripts SQL na pasta <code>Código</code></li>
    <li>Analise os dados brutos na pasta <code>Dados</code></li>
    <li>Consulte a documentação na pasta <code>Documentação</code></li>
    <li>Abra os dashboards Power BI na pasta <code>Visualizações</code></li>
  </ol>
</div>

## 📝 Conclusões Principais

<div style="background-color: #f0f7ff; padding: 15px; border-radius: 8px; margin: 20px 0;">
  <ul>
    <li>Identificámos que fatores como distância de casa, horas extraordinárias e satisfação no trabalho são determinantes para o atrito de funcionários</li>
    <li>Departamentos com maior rotatividade: Vendas e TI</li>
    <li>Funcionários com mais de 2 anos na empresa e sem promoção recente apresentam maior risco de saída</li>
    <li>Implementação de programas de reconhecimento e planos de carreira claros podem reduzir significativamente o atrito</li>
  </ul>
</div>

## 👥 Equipa

<div style="background-color: #f5f5f5; padding: 15px; border-radius: 8px; text-align: center; margin: 20px 0;">
  <p>Projeto desenvolvido como parte do curso AiDAPT01 - Grupo 03</p>
</div>

## 📄 Licença

Este projeto é para fins educacionais e de demonstração.

---

<div align="center">
  <p>Para mais informações, contacte através do GitHub.</p>
  <a href="https://github.com/MrMaddball" style="display: inline-block; background-color: #24292e; color: white; padding: 8px 16px; text-align: center; text-decoration: none; border-radius: 5px; margin: 10px 0;">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>