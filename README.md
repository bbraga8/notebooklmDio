 # NotebookLM — Big Data e Data Analytics

Este repositório apresenta o material de estudo utilizado em um **NotebookLM** dedicado aos temas **Big Data** e **Data Analytics**.

O objetivo é reunir fontes organizadas para apoiar estudos, resumos, perguntas, comparações e revisões sobre análise de dados e processamento de grandes volumes de dados.

## 📓 Acesse o NotebookLM

[Abrir notebook no NotebookLM](https://notebook.google.com/notebook/c2c4c5bf-f78d-41d8-8727-acb04d14cde6)
O notebook contém as fontes relacionadas aos estudos de Big Data e Data Analytics. As respostas geradas no NotebookLM devem indicar de qual fonte foi extraída a informação, permitindo a conferência direta do conteúdo original.

## 🎯 Objetivos de estudo

- Compreender os fundamentos de Big Data.
- Estudar conceitos de Data Analytics.
- Relacionar dados, ferramentas e técnicas de análise.
- Produzir resumos e perguntas a partir das fontes fornecidas.
- Utilizar as referências para revisar conceitos e validar respostas.

## 📚 Fontes utilizadas

### Vídeos do YouTube

| Fonte | Tema | Tipo |
|---|---|---|
| [Vídeo 1](https://www.youtube.com/watch?v=FF25PP4dq9M) | Estudo sobre dados e análise de dados | Vídeo |
| [Vídeo 2](https://www.youtube.com/watch?v=FwjaHCVNBWA) | Estudo sobre dados e análise de dados | Vídeo |

## 🧭 Como usar o notebook

1. Abra o [notebook](https://notebook.google.com/notebook/c2c4c5bf-f78d-41d8-8727-acb04d14cde6).
2. Consulte uma das fontes cadastradas.
3. Faça perguntas sobre Big Data ou Data Analytics.
4. Verifique as citações apresentadas em cada resposta.
5. Clique na fonte citada para conferir o trecho original.
6. Use o conteúdo para criar resumos, mapas de conceitos e planos de estudo.
- 
Fontes
  ↓
NotebookLM
  ↓
Perguntas e resumos
  ↓
Citações verificadas
  ↓
Anotações e revisão

Com base no acervo bibliográfico e nos materiais do seu caderno, aqui está a síntese detalhada e estruturada dos conceitos, ferramentas, metodologias e casos práticos apresentados:

---

### 1. Principais Conceitos Abordados nas Fontes
As fontes abordam a transformação digital e a análise de dados a partir de três pilares centrais:
*   **Big Data:** Focado na gestão e exploração de grandes volumes cotidianos de informação que chegam com alta velocidade e variedade, demandando arquiteturas capazes de extrair valor dos dados.
*   **Business Intelligence (BI) e Analytics:** Voltados para a exploração on-line e a conversão de dados brutos em inteligência estratégica. Isso inclui o uso de relatórios interativos, cubos OLAP e **modelagem relacional** (como o **Modelo Estrela / Star Schema**) para otimizar operações e suportar decisões.
*   **Métricas de Desempenho Operacional (Service Desk / ITSM):** Análise aplicada ao gerenciamento de serviços de TI para medir a produtividade e a qualidade do atendimento através de KPIs como **MTTR (Tempo Médio de Resolução)**, **FRT (Tempo de Primeira Resposta)**, **Backlog** e **cumprimento de SLA**.

---

### 2. Diferença entre Big Data e Data Analytics / Business Intelligence
De acordo com o material bibliográfico e técnico:
*   **Big Data:** Refere-se à infraestrutura, captura e processamento de volumes massivos de dados estruturados e não estruturados (como dados de redes sociais, geolocalização ou logs de grandes ecossistemas), utilizando tecnologias distribuídas como Hadoop, Hive, HBase e ecossistemas em nuvem como Google BigQuery ou HP Vertica.
*   **Data Analytics / Business Intelligence:** Foca na camada analítica e visual. O objetivo do BI é pegar esses dados (já estruturados ou em formato de Data Warehouses/Data Marts) e aplicar regras de negócio, agregações temporais e fórmulas visuais (usando ferramentas como Power BI ou Tableau) para responder a perguntas de negócio e direcionar tomadas de decisão estratégicas.

---

### 3. Etapas Envolvidas em um Processo de Análise de Dados
O ciclo completo de um projeto de BI e análise de dados abrange cinco etapas principais:

1.  **Obtenção e Conexão de Dados (Extract):** Conexão com diversas fontes de dados, incluindo arquivos planos (CSV, Excel), bancos de dados relacionais (SQL Server, MySQL), bancos em nuvem (BigQuery) ou APIs da web.
2.  **Preparação e Limpeza de Dados (Data Preparation / ETL):** Filtragem, tratamento de valores nulos, transformação de tipos de dados e estruturação das consultas (realizados no **Power Query** através da linguagem M).
3.  **Modelagem de Dados (Data Modeling):** Organização das tabelas no formato de **Modelo Estrela (Star Schema)**, separando dados transacionais em uma **Tabela Fato** (`factTickets`) e dados descritivos em **Tabelas Dimensão** (`dimDate`, `dimAgent`, `dimCategory`), além da criação de medidas calculadas em **DAX**.
4.  **Visualização e Análise (Data Visualization):** Construção de relatórios e dashboards interativos com cartões KPI, gráficos de barras/colunas, linhas temporais, matrizes e mapas para expor os indicadores de negócio.
5.  **Publicação, Compartilhamento e Tomada de Decisão:** Envio dos relatórios para plataformas em nuvem (Power BI Service) ou repositórios de projetos (GitHub) para garantir que a liderança acesse dados atualizados e confiáveis.

---

### 4. Como os Dados Podem ser Utilizados na Tomada de Decisões (Casos Reais)
As fontes destacam como a análise de dados gera vantagem competitiva e reduz custos em cenários reais:

*   **Reeleição de Barack Obama (2012):** A equipe combinou dados demográficos de eleitores com audiências de TV e preços de anúncios via plataforma HP Vertica. Isso permitiu focar recursos apenas em eleitores indecisos e partidários, otimizando compras de mídia e evitando desperdício de verbas com opositores.
*   **Macy's:** Analisou os hábitos de compra de clientes no comércio físico e e-commerce por meio de seu banco de dados relacional. A personalização de campanhas gerou uma **economia de até 500.000 euros anuais** em e-mails indiscriminados, reduziu os cancelamentos de newsletters em mais de 20% e permitiu ofertas em tempo real no aplicativo móvel.
*   **Amazon (Amazon Connections):** Implementou um sistema interno de consultas diárias não anônimas aos funcionários para avaliar satisfação laboral e liderança. Especialistas em Praga e Seattle analisavam os dados e geravam informes diários para a direção ajustar as condições de trabalho.
*   **Service Desk Corporativo:** Permite identificar a causa-raiz de tickets recorrentes (como "Redefinição de Senha") para propor automações, reduzir o tempo de resolução (MTTR) e dimensionar a equipe para evitar o estouro de prazos de SLA.

---

### 5. Ferramentas e Técnicas Mencionadas nas Fontes
*   **Ferramentas de BI e Visualização:** Microsoft Power BI (Desktop e Service), Microsoft Excel (Power Pivot, Power Query) e Tableau.
*   **Tecnologias de Big Data e Banco de Dados:** Hadoop, Hive, HBase, HP Vertica, Google BigQuery e MySQL.
*   **Linguagens de Programação e Fórmulas:** **DAX** (Data Analysis Expressions) para medidas e colunas calculadas, **Linguagem M** para ETL no Power Query, SQL, Python e R.
*   **Técnicas e Estruturas Analíticas:** Modelo Estrela (Star Schema), Cubos OLAP, Mineração de Dados (Data Mining), Teoria dos Grafos para Redes Sociais e Metodologia PMBOK para gestão de projetos.
*   **Plataformas de Versionamento e Aprendizado:** GitHub para publicação de portfólios, Parallels para execução de ambientes Windows em Mac e o exame de certificação **PL-300** da Microsoft.

---

# 6. Resumo dos Vídeos Integrados ao Caderno

1.  **"Course Preview | PL-300 | Design and manage analytics solutions using Power BI" (Microsoft Learn):**
    *   Focado na preparação para o exame de certificação **PL-300**.
    *   Aborda como substituir processos manuais e propensos a erro no Excel por relatórios automatizados no Power BI.
    *   Ensina a conectar a múltiplas fontes, transformar dados, criar modelos de dados com DAX e publicar dashboards seguros e acessíveis no Power BI Service para tomadores de decisão.

2.  **"Power BI for Data Analytics - Full Course for Beginners" (Luke Barousse):**
    *   Um curso prático focado em construir projetos completos de portfólio (analisando dados reais de empregos em Data Science e Service Desk).
    *   Explica a história do Power BI, destacando como ele surgiu em 2013 para resolver a limitação do Excel no compartilhamento de dashboards.
    *   Detalha a diferença entre o **Power BI Desktop** (aplicativo gratuito para desenvolvimento de relatórios) e o **Power BI Service** (plataforma em nuvem para colaboração em Workspaces e publicação na web).
    *   Demonstra a aplicação de ETL no Power Query, modelagem Star Schema, fórmulas DAX avançadas, criação de visuais interativos (gráficos de colunas/barras, linhas, mapas e slicers) e a publicação do projeto final no **GitHub** acompanhado de um arquivo `README.md` detalhado.


### 7. Comparação entre as Fontes
*   **Fontes Bibliográficas Teóricas (`BigDataBu.Bib.pdf` e `BigDataBu.An.pdf`):** Oferecem uma fundamentação acadêmica e conceitual sólida, focando em arquitetura distribuída (Hadoop), algoritmos de Data Mining e em grandes estudos de caso estratégicos de impacto global (campanha de Obama, Macy's e gestão de RH da Amazon).
*   **Guia de Portfólio de BI (`Projeto_BI_Suporte_Portfolio.pdf`):** Atua como uma ponte prática voltada ao mercado de trabalho corporativo, fornecendo um roteiro exato para estruturar dashboards operacionais de Service Desk, definindo o modelo relacional Star Schema e fórmulas DAX essenciais (MTTR, SLA%, Backlog).
*   **Vídeos de Treinamento em Power BI (Microsoft Learn & Luke Barousse):** Concentram-se na execução técnica hands-on das ferramentas do ecossistema Microsoft, ensinando passo a passo o uso do Power Query, DAX, publicação no Power BI Service e a apresentação de projetos no GitHub para contratação no mercado de trabalho.



