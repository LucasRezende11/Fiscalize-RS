# FISCALIZE RS

## Web Page of the app:  [<URL HERE>](https://fiscalize-rs.streamlit.app/)

## Description
The FISCALIZE RS is an initiative aimed at democratizing access to municipal management information and strives to provide an overview of municipalities, allowing individuals to actively exercise their citizenship and oversee whether the municipalities are fulfilling their basic and constitutional duties. Through the tool, users can access socioeconomic information, municipal public accounts, and indicators of key sectors such as health and education.
Furthermore, it seeks to highlight the importance of proper management of public resources and investments in health, education, and sanitation, with the goal of promoting comprehensive development.

It was developed in Python and utilizes the Streamlit platform for visualization and deployment. Therefore, the final form of the project is a Streamlit app.

## Databases
The databases used aim to provide an extensive overview of the socio-economic situation of the city being searched, enabling users to effectively monitor and assess it.
Among the primary data sources utilized, the SIDRAPY API stands out as a key provider of economic data from the Instituto Brasileiro de Geografia e Estatística (IBGE). Additionally, a custom Python script was developed for web scraping to collect data that was not accessible through API integration or available in standard database formats such as Excel.
Another important data source was the website of the Tribunal de Contas do Estado do Rio Grande do Sul, which provided comprehensive information on municipal revenue, expenses, education, health, and expenditure limits.
The IBGE CIDADES platform, an IBGE tool for accessing their data, was also used to gather information on the Índice de Desenvolvimento da Educação Básica (IDEB) and mortality rates.
More information about the sources of information or the concepts that balizaram the construction of this tool is avaible in the references page in the app (Referências).

## Folder structure
### pages
This folder contains all the code that constructs the pages within the app.

- **fiscalize_rs.py**
  This is the "About" page, which provides an overview of the tool and allows users to send messages with suggestions or questions.

- **Indicadores_de_Receita_Municipal.py**
  This page displays information about municipal revenue, including the various revenue categories, and provides analysis on the municipality's dependence on other state-level entities.

- **Indicadores_Econômicos.py**
  This page provides information on economic indicators, such as GDP (PIB), past mayors of the city, population statistics, and the distribution of economic sectors.

- **Indicadores_de_Saúde.py**
  This page displays information on health indicators, including the mortality rate, the ASPS index, basic immunization, and the city's health expenditures.

- **Indicadores_de_Educação.py**
  This page displays information on education indicators, such as the IDEB, the MDE index, and the city's education expenditures.

- **Indicadores_de_Gestão_Fiscal.py**
  This page presents the city's compliance with fiscal expenditure regulations, including personnel expenses, debt costs, and adherence to rules during election years.

- **Indicadores_de_Saneamento.py**
  This page provides information on the city's water supply service, sewer coverage, and solid waste management services.

- **Referências.py**
  This page outlines the sources of the databases used, defines key terms utilized in the development of the app, and references the laws and regulations that guide compliance and standards.

---

### project.py
This is the main file containing the code that starts the other pages and runs the app itself.

---

### data_tables
This folder contains the databases that provide information for building the app's pages. These databases were generated by an external code created to scrape data from various sources.

---

## License
This project is licensed under a custom license. You are free to use, modify, and share this software, provided that:

You are not allowed to sell or distribute it for commercial purposes.
For more details, refer to the LICENSE file in the repository.

---

## Contact me
LinkedIn: www.linkedin.com/in/lucas-rezende-22212922a
