# Análise de Atrito e Desempenho de Funcionários - HR Analytics

![Dashboard HR Analytics](Imagens/CA_AiDAPT01_P1_Visualizacao_Dashboard_1.png)

## 📊 Sobre o Projeto

Este projeto de HR Analytics tem como objetivo analisar os fatores que influenciam a rotatividade (atrito) e o desempenho dos funcionários em uma organização. Utilizando técnicas de análise de dados, modelagem estatística e visualização, buscamos identificar padrões e insights que possam auxiliar na tomada de decisões estratégicas de recursos humanos.

## 🎯 Objetivos

- Identificar os principais fatores que contribuem para o atrito de funcionários
- Analisar o desempenho dos colaboradores em diferentes departamentos
- Criar modelos preditivos para antecipar possíveis saídas de talentos
- Fornecer recomendações baseadas em dados para melhorar a retenção de talentos
- Desenvolver dashboards interativos para monitoramento contínuo de métricas de RH

## 📋 Estrutura do Projeto

### Dados
O projeto utiliza um conjunto de dados de RH com informações sobre:
- Dados demográficos dos funcionários
- Histórico de desempenho
- Satisfação no trabalho
- Tempo na empresa
- Departamentos e funções
- Compensação e benefícios

### Modelagem de Dados

#### Modelo OLTP (Transacional)
![Diagrama OLTP](Imagens/CA_AiDAPT01_P1_OLTP_Diagrama.png)

#### Modelo OLAP (Analítico)
![Diagrama OLAP](Imagens/CA_AiDAPT01_P1_OLAP_Diagrama.png)

### Dicionário de Dados
![Dicionário de Dados](Imagens/CA_AiDAPT01_P1_Dicionario_Dados.png)

## 🔍 Análises Realizadas

### Consultas SQL
Foram desenvolvidas diversas consultas SQL para extrair insights dos dados:

#### Consulta 1
![Consulta SQL 1](Imagens/CA_AiDAPT01_P1_Script_SQL_Consulta_1.png)

#### Consulta 2
![Consulta SQL 2](Imagens/CA_AiDAPT01_P1_Script_SQL_Consulta_2.png)

### Joins e Análises Relacionais

#### Análise por Departamento
![Joins Departamento](Imagens/CA_AiDAPT01_P1_Script_SQL_Joins_Pepartamento.png)

#### Análise de Informações Pessoais
![Joins Informações Pessoais](Imagens/CA_AiDAPT01_P1_Script_SQL_Joins_Personalinfo.png)

#### Análise de Rotatividade
![Joins Rotatividade](Imagens/CA_AiDAPT01_P1_script4_SQL._joins_Rotatividadepng.png)

### Transformação de Dados
![Dados Após Transformações](Imagens/CA_AiDAPT01_P1_Dados_Apos_Transformacoes.png)

## 📊 Visualizações e Dashboards

### Dashboard Principal
![Dashboard 1](Imagens/CA_AiDAPT01_P1_Visualizacao_Dashboard_1.png)

### Dashboard de Métricas Detalhadas
![Dashboard 2](Imagens/CA_AiDAPT01_P1_Visualizacao_Dashboard_2.png)

## 📈 Análise em R

Foi realizada uma análise estatística avançada utilizando a linguagem R, incluindo:
- Análise exploratória de dados
- Testes de hipóteses
- Modelagem preditiva
- Visualizações estatísticas

O relatório completo pode ser encontrado em [Análise em R](Documentação/CA_AiDAPT01_P1_Analise_em_R.pdf).

## 🛠️ Tecnologias Utilizadas

- **Armazenamento de Dados**: SQL Server, MongoDB
- **Análise de Dados**: R, SQL
- **Visualização**: Power BI
- **Documentação**: Microsoft Office Suite

## 📁 Estrutura de Diretórios

- **Código**: Scripts SQL, R e MongoDB
- **Dados**: Conjuntos de dados e dicionários
- **Documentação**: Relatórios e apresentações
- **Imagens**: Capturas de tela e diagramas
- **Visualizações**: Arquivos Power BI

## 🚀 Como Utilizar

1. Clone este repositório
2. Explore os scripts SQL na pasta `Código`
3. Analise os dados brutos na pasta `Dados`
4. Consulte a documentação na pasta `Documentação`
5. Abra os dashboards Power BI na pasta `Visualizações`

## 📝 Conclusões Principais

- Identificamos que fatores como distância de casa, horas extras e satisfação no trabalho são determinantes para o atrito de funcionários
- Departamentos com maior rotatividade: Vendas e TI
- Funcionários com mais de 2 anos na empresa e sem promoção recente apresentam maior risco de saída
- Implementação de programas de reconhecimento e planos de carreira claros podem reduzir significativamente o atrito

## 👥 Equipe

Projeto desenvolvido como parte do curso AiDAPT01 - Grupo 03

## 📄 Licença

Este projeto é para fins educacionais e de demonstração.

---

Para mais informações, entre em contato através do GitHub.