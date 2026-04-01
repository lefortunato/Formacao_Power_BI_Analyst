# 


<div align="center">
  
# 📊 Formação Power BI Analyst

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Metodologia](https://img.shields.io/badge/Metodologia-Análise%20de%20Dados-blue)
![Nível](https://img.shields.io/badge/Nível-Iniciante%20/%20Intermediário-yellow)

</div>

---

## 📋 Sumário
* [🏗️ Definições de Papéis no Ecossistema de Dados](#-objetivo-deste-tópico)
* [💡 O que é BI (Business Intelligence)](#-objetivo-deste-t%C3%B3pico)
* [❔ Diferença entre Dados, Informação e Conhecimento)](#-objetivo-deste-t%C3%B3pico)
* [🏗️ Data Analytics e Big Data)](#-objetivo-deste-t%C3%B3pico)
* [⚙️ Fundamentos de ETL vs. ELT)](#-objetivo-deste-t%C3%B3pico)
* [⚙️ Fundamentos de ETL vs. ELT)](#-objetivo-deste-t%C3%B3pico)
* [⚙️ Fundamentos de ETL vs. ELT)](#-objetivo-deste-t%C3%B3pico)
* [⚙️ Fundamentos de ETL vs. ELT)](#-objetivo-deste-t%C3%B3pico)
  
* [🔗 Como Contribuir / Contato](#-como-contribuir--contato)

---
## 🏗️ 1. Definições de Papéis no Ecossistema de Dados
Na área de dados, as funções se dividem conforme o estágio do fluxo de trabalho:

**Engenheiro de Dados:** Responsável por construir e manter as "estradas" (pipelines). Ele extrai os dados de fontes brutas, limpa e os armazena em bancos de dados ou Data Warehouses. </br></br>
**Cientista de Dados:** Focado em modelos estatísticos e matemáticos. Utiliza algoritmos de Machine Learning para identificar padrões e prever tendências futuras. </br></br>
**Analista de Dados:** O responsável por transformar dados em insights. Utiliza ferramentas como Power BI para criar visualizações que ajudam a empresa a tomar decisões baseadas em fatos. </br></br>

## 💡 2. O que é BI (Business Intelligence)
Business Intelligence é um conjunto de estratégias, processos e tecnologias que transformam dados brutos em informações significativas para a tomada de decisão estratégica. O foco principal é olhar para o passado e o presente para entender o desempenho do negócio. </br></br>

## ❔ 3. Diferença entre Dados, Informação e Conhecimento
Podemos entender essa evolução como uma pirâmide:

**Dados:** São fatos brutos e isolados, sem contexto (ex: o número "150"). </br></br>
**Informação:** É o dado processado e contextualizado (ex: "Vendemos 150 unidades do Produto A em São Paulo"). </br></br>
**Conhecimento:** É a interpretação da informação para gerar uma ação ou conclusão (ex: "As vendas em São Paulo cresceram 20%, precisamos reforçar o estoque lá"). </br></br>

## 📈 4. BI e Data Science: Os 4 Níveis de Análise
A análise de dados evolui em complexidade e valor agregado:

**Análise Descritiva (BI):** "O que aconteceu?" – Relatórios e dashboards de vendas passadas. </br></br>
**Análise Diagnóstica (BI):** "Por que aconteceu?" – Identificação de causas e correlações para um resultado específico. </br></br>
**Análise Preditiva (Data Science):** "O que pode acontecer?" – Uso de modelos para prever comportamentos futuros. </br></br>
**Análise Prescritiva (Data Science):** "O que devemos fazer?" – Recomenda o melhor caminho a seguir com base nas previsões. </br></br>

## 🏗️ 5. Data Analytics e Big Data
Para lidar com grandes volumes de dados (Big Data), utilizamos uma estrutura de fluxo bem definida:

**Data Source:** São as fontes de origem dos dados, como bancos de dados SQL, arquivos CSV, APIs ou logs de sistemas. </br></br>
**ETL:** O processo de extrair, transformar e carregar os dados. </br></br>
**Data Warehouse (DW):** Um repositório centralizado e otimizado para análise, onde os dados já chegam estruturados. </br></br>
**Análise de Dados:** A fase de exploração dos dados para responder perguntas de negócio. </br></br>
**Visualização dos Dados:** A criação de dashboards e gráficos (no Power BI, por exemplo) para comunicar os resultados. </br></br>

## ⚙️ 6. Fundamentos de ETL vs. ELT
A principal diferença entre os dois processos é onde a transformação do dado acontece.

**O que é ETL (Extract, Transform, Load)**
Os dados são transformados antes de chegarem ao destino final. É ideal para quando precisamos de segurança rigorosa e os dados de destino devem estar perfeitamente limpos.

**O que é ELT (Extract, Load, Transform)**
Os dados são carregados brutos no destino e a transformação ocorre dentro do próprio armazém de dados (Data Warehouse/Lake).

**Vantagens do ELT** </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **. Tempo de carregamento:** Mais rápido, pois o dado vai direto para o destino. </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **. Tempo de transformação:** Aproveita o alto poder de processamento da nuvem. </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **. Complexidade de implementação:** Geralmente menor, pois exige menos ferramentas intermediárias. </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **. Suporte a Data Warehouses:** Modernos DWs (como BigQuery ou Snowflake) são desenhados para suportar ELT com facilidade. </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **. Usabilidade:** Permite que os analistas transformem os dados conforme a necessidade, sem depender sempre da engenharia. </br></br>

| Característica | ETL | ELT
| :---: | :---: | :---: |
| Ordem	| Extrai > Transforma > Carrega	| Extrai > Carrega > Transforma
| Onde transforma	| Em um servidor temporário (staging)	| No banco de dados de destino
| Flexibilidade	| Baixa (o dado já chega pronto)	| Alta (o dado bruto está disponível)

**Quando usar ETL:** Quando você lida com dados sensíveis que precisam de máscaras antes de serem armazenados ou quando o banco de destino não tem poder de processamento. </br></br>
**Quando usar ELT:** Quando você trabalha com Big Data, utiliza ferramentas em nuvem e precisa de agilidade para que diferentes áreas analisem os mesmos dados brutos. </br></br>


## 🛠️ 7. Configuração do Ambiente e Obtenção de Dados
Nesta etapa, preparamos as ferramentas e os insumos necessários para o desenvolvimento do projeto.

| Ferramenta | Link | Versão Utilizada
| :---: | :---: | :---: |
| Power BI	| https://download.microsoft.com/download/8/8/0/880bca75-79dd-466a-927d-1abf1f5454b0/PBIDesktopSetup_x64.exe |	64-bit
| Plataforma de base de dados	| https://www.kaggle.com/ | Não se aplica
| Base de dados p/ testes	| https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset |	Não se aplica


**1. Instalação do Power BI Desktop**  </br>
O Power BI Desktop é a aplicação gratuita de autorização onde criamos os relatórios. </br></br>
**Download:** Pode ser feito diretamente pelo site oficial da Microsoft ou pela Microsoft Store (recomendado para atualizações automáticas). </br>

**Instalação:** Segue o padrão simples de assistente de instalação para Windows. </br></br>

**2. Obtenção de Dados (Kaggle)** </br><
Para este projeto, utilizamos o Kaggle, uma das maiores comunidades de ciência de dados do mundo, que oferece datasets (conjuntos de dados) gratuitos para estudo e prática.

**Fonte Principal:** Kaggle Portal

**Dataset de Referência:** Diabetes Dataset

Este conjunto de dados é ideal para praticar análise exploratória, pois contém diversas variáveis numéricas e categóricas que permitem correlações interessantes (como idade, nível de glicose e diagnóstico).

**3. Fluxo Inicial no Power BI** </br>
Com o software instalado e o arquivo .csv ou .xlsx em mãos:

Utilizamos a opção "Obter Dados" no Power BI.

Conectamos ao arquivo baixado do Kaggle.

Antes de carregar, selecionamos "Transformar Dados" para abrir o Power Query e garantir que os tipos de colunas estejam corretos (ex: garantir que a coluna de ID não seja somada como um número).


## 🛠️ 8. Documentação do Power BI
Nesta etapa, apresentarei os links de documentação e base de exemplos para exploração.

| Documentação | Link | 
| :---: | :---: |
| Microsoft Power BI	| https://learn.microsoft.com/pt-br/power-bi/ |
| Exemplos de base de dados	| https://learn.microsoft.com/pt-br/power-bi/create-reports/sample-datasets |


## 🔗 **Como Contribuir / Contato**</br></br>
Este projeto foi desenvolvido como parte de um desafio prático de segurança cibernética. Sinta-se à vontade para explorá-lo, cloná-lo e adaptá-lo!

| Botão | Ação |
| :--- | :--- |
| ⭐ Dar Estrela | Se gostou do projeto, considere dar uma estrela no GitHub. |
| 🤝 Conecte-se | **<img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="Link para o LinkedIn" align="center"> <a href="https://www.linkedin.com/in/leandro-antonio-fortunato/" target="_blank">  Visite meu linkedin</a>**  |
| 📧 Fale Comigo | 📧 [E-mail para contato](mailto:leandroantonio.fortunato@hotmail.com) |

