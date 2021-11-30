# Requirements-Definition

## Modelo de Casos de uso (Cdu)
Next sections include the the use case diagrams and brief descritption of each system component. It is not complete. 

### Cliente (CdU01#)
O diagrama de casos de uso asseguir mostras os componentes de caso de uso "Cliente".

![UseCase01](images/TicketsPurchaseUC.png)

The login use case will provide the user authentication and is expected to be implemented by an external federated authentication server. Next, a brief description of the use cases to be implemented:
* **CdU01.1 — Encomendar Produtos** — The user get new ticket for a meal in a specific canteen, date, meal type, and dish type.

* **CdU01.2 — Cancelar Encomenda** — ...


* **CdU01.3 — Registo na plataforma** — ...

* **CdU01.3 — Histórico** — ...

* **CdU01.3 — Avaliar comerciantes** — ...

* **CdU01.3 — List ticket purchases** — ...

* **CdU01.4 — List money loads** — ..
Etc.


### Camara Municipal (Cdu2.#)
The following use case diagram shows the use cases of component "Canteen POS".
O diagrama de casos de uso asseguir mostras os componentes de caso de uso "Camara Muncipal".

![UseCase01](images/CanteenPosUC.png)

Asseguir, uma breve descrição de cada caso de uso:
* **CdU02.1 — Validar Produtor** —  O Administrador valida produtor, isto é, se eles estão aptos a exercer para usufruir da plataforma, venda de seus produtos.

* **CdU02.2 — Consultar Stock** — O administrador "Camâra Municipal" deve ser capaz de consultar o stock existente.

* **CdU02.3 — Eliminar produtor** — Caso o produtor não cumpra os criterios de qualidade estabelecidos, a camâra poderá eliminar o produtor, entre outras razões que a camâra poderá utilizar está funcionalidade

* **CdU02.3 — Extrair A morada** — O administrador deve ser capaz de extrair a morada do cliente para o envio da encomenda.

* **CdU02.4 — Reprint bill** — ..

* **CdU02.5 — Print bill** — ..

### Produtor (Cdu.#)

* **CdU02.1 — Insere produto/Elimina Produto** —  O Administrador valida produtor, isto é, se eles estão aptos a exercer para usufruir da plataforma.

* **CdU02.2 — Consultar Stock** — 
* **CdU02.3 — Eliminar produto** —  A qualquer momento o produtor pode eliminar o produto da plataforma.

* **CdU02.4 — Consultar o nível de satisfação dos seus clientes** — O produtor pode consulatar o nível de satisfação dos seus clientes.

* **CdU02.5 — Print bill** — .
[Not developed]


## Regras de Negocio
As Regras de Negoçio (RN) são a fonte de muitas decisõse de negoçios. Podem alterar a qualquer momemnto e podem impactar mais do que casos de uso. É importante seguir e identifica-los.
* **RN01 — custo do produto** — O Custo do produto pode alterar de acordo com o conselho em o cliente resida, caso este não seja do municipio lhe será cobrado uma taxa 0.01% por quilometro.

* **RN02 — Escolher produto** — Após as 15.00pm, as encomendas que o cliente fizer serão enviados no dia seguinte.

* **RN03 — Maximo de produtos por dia** — By day, Each user can buy two tickets to each meal, lunch or dinner.

* **RN04 — Tempo para Cancelar Encomenda** — A encomenda pode ser cancelada antes das 14:30pm caso tenha feito a encomenda no dia anterior apartir das 15:00pm até 14:30 do dia em causa.

* **RN05 — other rules to be validated by the system** — ...
Etc.


## Technical requirements
In this section are grouped the business rules, non-functional requirements, and other constraints. It also includes the assumptions that the team will embody in the project.  


## Requisitos Não Funcionais
Most of the Non-Functional Requirements (NFR) are implicit in the condition:
* **NFR01 — Web platform** — The "tickets acquisition" component should run in a Web platform;

* **NFR02 — User account** — The users should use the IPCA's email account to login;

* **NFR03 — Web browser** — the system should be compatible with the current version or higher of the Safari, Chrome, and Firefox browsers.
Etc.

## Assumptions and constraints
All constraints and decisions that have a relevant impact on the project, should be explicitly mentioned and documented:
* **AC01 — Deadlines** — The project should be ready for deployment in the beginning of the 2nd semester;

* **AC02 — Open Source** — The team will use open source technology, as much as possible.

* **AC03 — Languages** — The "tickets acquisition" component will support Portuguese and English languages
Etc.

[Back Home](Home)