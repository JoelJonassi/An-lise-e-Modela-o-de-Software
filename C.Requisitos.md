# Requirements-Definition

## Modelo de Casos de uso (Cdu)
Next sections include the the use case diagrams and brief descritption of each system component. It is not complete. 

### Cliente (CdU01#)
O diagrama de casos de uso asseguir mostras os componentes de caso de uso "Cliente".

INCLUIR DIGRAMA DE CASO DE USO "CLIENTE"

The login use case will provide the user authentication and is expected to be implemented by an external federated authentication server. Next, a brief description of the use cases to be implemented:

* **CdU01.1 — Encomendar Produtos** — 

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

INCLUIR DIGRAMA DE CASO DE USO "CAMARA MUNICIPAL"

Asseguir, uma breve descrição de cada caso de uso:

* **CdU02.1 — Validar Produtor** —  O Administrador valida produtor, isto é, se eles estão aptos a exercer para usufruir da plataforma, venda de seus produtos.

* **CdU02.2 — Consultar Stock** — O administrador "Camâra Municipal" deve ser capaz de consultar o stock existente.

* **CdU02.3 — Eliminar produtor** — Caso o produtor não cumpra os criterios de qualidade estabelecidos, a camâra poderá eliminar o produtor, entre outras razões que a camâra poderá utilizar está funcionalidade

* **CdU02.3 — Extrair A morada** — O administrador deve ser capaz de extrair a morada do cliente para o envio da encomenda.

* **CdU02.4 —** — ..

* **CdU02.5 —** — ..

### Produtor (Cdu.#)

INCLUIR DIGRAMA DE CASO DE USO "PRODUTOR"

* **CdU02.1 — Insere produto/Elimina Produto** —  O Administrador valida produtor, isto é, se eles estão aptos a exercer para usufruir da plataforma.

* **CdU02.2 — Consultar Stock** — 
* **CdU02.3 — Eliminar produto** —  A qualquer momento o produtor pode eliminar o produto da plataforma.

* **CdU02.4 — Consultar o nível de satisfação dos seus clientes** — O produtor pode consulatar o nível de satisfação dos seus clientes.

* **CdU02.5 — ** — .


## Regras de Negocio
As Regras de Negoçio (RN) são a fonte de muitas decisõse de negoçios. Podem alterar a qualquer momemnto e podem impactar mais do que casos de uso. É importante seguir e identifica-los.
* **RN01 — custo do produto** — O Custo do produto pode alterar de acordo com o conselho em o cliente resida, caso este não seja do municipio lhe será cobrado uma taxa 0.01% por quilometro.

* **RN02 — Escolher produto** — Após as 15.00pm, as encomendas que o cliente fizer serão enviados no dia seguinte.

* **RN03 — Maximo de produtos por dia** — By day, Each user can buy two tickets to each meal, lunch or dinner.

* **RN04 — Tempo para Cancelar Encomenda** — A encomenda pode ser cancelada antes das 14:30pm caso tenha feito a encomenda no dia anterior apartir das 15:00pm até 14:30 do dia em causa.

* **RN05 — Outras regras a serem validadas pelo sistema** — ...
Etc.


## Technical requirements
INTRO................:

## Requisitos Não Funcionais

* **RNF01 — ** 

* **RNF02 — Conta do cliente e conta do produtor**

* **RNF03 — Plataforma web** 

## Pressupostos e constrangimentos
Pressupostos e constrangimentos que tenham impacto sobre o projeto:

* **PC01 — Data Limite** O projeto deverá estar pronto a arrancar no 2º semestre, para validar os protótipos.

* **PC02 — Equipamento** A equipa irá utilizar software com licença pedagogica, IDEs, BitBucket e Jira. Os computadores terão sistema operativo com licença pedagogica. Todo e qualquer equipamento requesitado será providenciado. 

* **PC03 — Lingua** A plataforma suporta os idiomas português, inglês e francês, sendo o português o idioma predefinido.

* **PC04 — Custo** O projecto terá um custo de três salários de desenvolvedores e um para o orientador do projeto durante o tempo de vida útil do projeto, isto envolve também manuntençao da plataforma.

* **PC05 — Beneficio** O projecto vai trazer valor aos produtores locais e experiência aos desevolvedores do projeto.



[Back Home](Home)