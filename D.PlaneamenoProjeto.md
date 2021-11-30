# Arquitetura Técnica

The functional components have different technical requirements. The "tickets acquisition" and "tickets reporting" components need to accessible from anywhere, so it will be implemented as a web application using the more used/cheap/easy tools to build it.

The main requirement for the "Canteen POS" component is to be easy, fast and 100% uptime at meal hours.

Os componentes funcionais tem diferentes requisitos técnicos. Os produtos devem ser acessiveis de qualquer lugar, por isso será desenvolvida uma aplicação web, usando ferramentas baratas, mais utilizadas e de fácil utilização.
O principal  reuquisito da plataforma e-commerce de produtos locais é que seja de fácil utilização seguindo os padrões das plataformas existentes, rápida entrega das encomendas.


![TechArch](images/CanteenTechArch.png)


# Product Backlog (PB) preparation
In this project, the product backlog is made of Use Cases (UC) and Use Case Slices (UCS) instead of using user stories.

## UC Prioritization
The UC prioritization is the task of assigning the priority level to each item of the PB, ordering them by priority level, so the higher priority items are developed first. The MoSCoW technique, used here, uses 4 priority levels: Must, Should, Could and Would/Won't.

UC Code | UC Name | Priority
-----|-----|-----
UC1.01 | Purchase ticket | Must
UC2.01 | Validade ticket | Must
UC1.02 | Cancel ticket | Should
UC1.03 | List ticket purchases | Should
UCx.xx | ... | ...|

The table is not complete.

## Project Roadmap
(Not required in the 2020-21 academic year)

The project will be lauched in 3 releases.

Date | Release | Features | Sprint_Nr 
--- | --- | --- | ---
16th February | R01 Tickets | sales/validation, money loads  | 06 
20th April | R02 More tickets | Advanced tickets features | 09 
22th June | R03 Reporting | Detailed reports and graphics | 12

[Back Home](Home)