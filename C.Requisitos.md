# Requirements-Definition

## Modelo de Casos de uso (Cdu)
Next sections include the the use case diagrams and brief descritption of each system component. It is not complete. 

### Login / Registo (CdU01#)
O diagrama de casos de uso asseguir mostras os componentes de caso de uso "Login / Regsito".

INCLUIR DIGRAMA DE CASO DE USO "Login / Registo"

The login use case will provide the user authentication and is expected to be implemented by an external federated authentication server. Next, a brief description of the use cases to be implemented:

* **CdU01.1 — Novo Registo** — O Cliente efetua um registo na plataforma para que possa usar a mesma.

* **CdU01.2 — Define username** — O cliente define o username pretendido.

* **CdU01.3 — Define password** — O cliente define a password para, juntamente com o username ter acesso à plataforma desenvolvida.

* **CdU01.4 — Regista NIF** — O cliente insere o seu NIF para se poderem emitir facturas das suas compras.

* **CdU01.5 — Insere Morada** — O cliente insere a morada no seu perfil de modo a definir o destino das suas encomendas.

* **CdU01.6 — Insere Contato** — O cliente insere o seu contato para que possa ser contactado quando necessário.

* **CdU01.7 — Insere e-mail** — O cliente o seu e-mail, para onde será enviada a confirmação e fatura das suas encomendas.

* **CdU01.8 - Login** - O cliente efetua login na aplicação de modo a poder consultar/fazer compras, visualizar e alterar os seus dados.

* **CdU01.9 - User Profile** -  Após efetuar o seu login, o cliente tem acessso ao seu perfil, podendo visualizar e editar o mesmo

* **CdU01.10 - Logout** - Após aceder à plataforma, o cliente efetua "Logout" se modo a sair da aplicação com segurança.

* **CdU01.11 - Valida Produtor** - O administrador valida o registo do produtor.

* **CdU01.12 - Elimina Produtor** - O admininstraddor elimina o registo do produtor.

* **CdU01.13 - Consulta Stock** - O administrador e o produtor, consultam o stock dos produtos de forma a gerir a disponibilidade dos mesmo na plataforma.

* **CdU01.14 - Regista Produtor** - O administrador regista produtores.

* **CdU01.15 - Insere/Elimina produto** - O produtor, mediante a consulta efetuada, tem a possibilidade de inserir ou eliminar produtos.



### Compras (CdU02.#)
The following use case diagram shows the use cases of component "Compras".
O diagrama de casos de uso asseguir mostras os componentes de caso de uso "Compras".

INCLUIR DIGRAMA DE CASO DE USO "Compras"

Asseguir, uma breve descrição de cada caso de uso:

* **CdU02.1 — Gerir Carrinho** —  O Administrador valida produtor, isto é, se eles estão aptos a exercer para usufruir da plataforma, venda de seus produtos.

* **CdU02.2 — Apagar artigos** — O cliente tem a possibilidade de apagar artigos no carrinho

* **CdU02.3 — Editar artigos** — Caso o produtor não cumpra os criterios de qualidade estabelecidos, a camâra poderá eliminar o produtor, entre outras razões que a camâra poderá utilizar está funcionalidade

* **CdU02.4 — Adicionar artigos** — O administrador deve ser capaz de extrair a morada do cliente para o envio da encomenda.

* **CdU02.5 — Ver Itens** — O cliente insere, após efetuar a sua seleção de artigos, visualiza os mesmos de forma a confirmar a escolhas.

* **CdU02.6 — Confirmar dados de envio** — Após a visualização e confirmação dos itens escolhidos, o cliente confirma os dados de envio.

* **CdU02.7 - Efetua Compra** — Depois de confirmar a sua encomenda e modade de envio, o cliente submete a dua compra.

* **CdU02.8 — CheckOut** — Depois de submeter a compra, é apresentado ao cliente os dados para o pagamento da mesma e os tipos de pagamento.

* **CdU02.9 — Gerir Compra** — O admin faz a gestão das compras dos clientes, para verificar a conformidade das mesmas

* **CdU02.10 — Login** — Tanto o cliente como o admin têm de fazer login para efetuarem as suas operações.




### Produtor (Cdu03.#)

INCLUIR DIGRAMA DE CASO DE USO "PRODUTOR"

* **CdU03.1 — Notifica Data/Hora entrega** —  O admin notifica o cliente acerca da data e hora da entrega da sua encomenda.

* **CdU03.2 — Verifica Encomenda** — O Admin faz uma verificação da encomenda antes de notificar o cliente e o produtor.

* **CdU03.3 — Valida encomenda** —  Após a verificação, o admin valida a encomenda 

* **CdU03.4 — Notifica produtor** — Depois de validar a encomenda, o admin notifica o produtor.

* **CdU03.5 — Separa produtos** — Assim que notificado pelo admin, o produtor procede à separação dos mesmos.

* **CdU03.6 — Embala produtos** — Após a separação dos produtos, o produtor procede ao seu embalamento.

* **CdU03.7 — Requisita transporte** — O admin, requisita os meios de recolha e entrega dos produto.

* **CdU03.8 — Recolhe produtos** — Após requisição, é efetuada a recolha dos produtos pela empresa de transporte.

* **CdU03.9 — Entrega encomenda** — Após a recolha dos produtos no produtor é efetuado o envio dos mesmo ao cliente.

* **CdU03.10 — Recebe encomenda** — O cliente procede à receção da sua encomenda.



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

INTRO......................:

* **PC01 — Deadlines**

* **PC02 — Open Source** 

* **PC03 — Languages** 

[Back Home](Home)