# Requirements-Definition

## Modelo de Casos de uso (Cdu)
Next sections include the the use case diagrams and brief descritption of each system component. It is not complete. 

### Login / Registo (CdU01#)
O diagrama de casos de uso asseguir mostras os componentes de caso de uso "Login / Registo".

![image](Images\UC_Login-Registo.JPG)

The login use case will provide the user authentication and is expected to be implemented by an external federated authentication server. Next, a brief description of the use cases to be implemented:

* **CdU01.01 — Novo Registo** — O Cliente efetua um registo na plataforma para que possa usar a mesma.

* **CdU01.02 — Define username** — O cliente define o username pretendido.

* **CdU01.03 — Define password** — O cliente define a password para, juntamente com o username ter acesso à plataforma desenvolvida.

* **CdU01.04 — Regista NIF** — O cliente insere o seu NIF para se poderem emitir facturas das suas compras.

* **CdU01.05 — Insere Morada** — O cliente insere a morada no seu perfil de modo a definir o destino das suas encomendas.

* **CdU01.06 — Insere Contato** — O cliente insere o seu contato para que possa ser contactado quando necessário.

* **CdU01.07 — Insere e-mail** — O cliente o seu e-mail, para onde será enviada a confirmação e fatura das suas encomendas.

* **CdU01.08 - Login** - O cliente efetua login na aplicação de modo a poder consultar/fazer compras, visualizar e alterar os seus dados.

* **CdU01.09 - User Profile** -  Após efetuar o seu login, o cliente tem acessso ao seu perfil, podendo visualizar e editar o mesmo

* **CdU01.10 - Logout** - Após aceder à plataforma, o cliente efetua "Logout" se modo a sair da aplicação com segurança.

* **CdU01.11 - Valida Produtor** - O administrador valida o registo do produtor.

* **CdU01.12 - Elimina Produtor** - O admininstraddor elimina o registo do produtor. Caso o produtor não cumpra os criterios de qualidade estabelecidos, a camâra poderá eliminar o produtor, entre outras razões que a camâra poderá utilizar está funcionalidade.

* **CdU01.13 - Consulta Stock** - O administrador e o produtor, consultam o stock dos produtos de forma a gerir a disponibilidade dos mesmo na plataforma.

* **CdU01.14 - Regista Produtor** - O administrador regista produtores.

* **CdU01.15 - Insere/Elimina produto** - O produtor, mediante a consulta efetuada, tem a possibilidade de inserir ou eliminar produtos.



### Compras (CdU02.#)
The following use case diagram shows the use cases of component "Compras".
O diagrama de casos de uso asseguir mostras os componentes de caso de uso "Compras".

![image](Images\UC_Compras.JPG)

Asseguir, uma breve descrição de cada caso de uso:

* **CdU02.01 — Gerir Carrinho** —  O Administrador valida produtor, isto é, se eles estão aptos a exercer para usufruir da plataforma, venda de seus produtos.

* **CdU02.02 — Apagar artigos** — O cliente tem a possibilidade de apagar artigos no carrinho

* **CdU02.03 — Adicionar artigos** — O Cliente adiciona os artigos nos seu carrinho conforme a sua preferência.

* **CdU02.04 — Ver Itens** — Após efetuar a sua seleção de artigos, visualiza os mesmos de forma a confirmar a escolhas.

* **CdU02.05 — Confirmar dados de envio** — Após a visualização e confirmação dos itens escolhidos, o cliente confirma os dados de envio.

* **CdU02.06 - Efetuar Compra** — Depois de confirmar a sua encomenda e forma de envio, o cliente submete a sua compra.

* **CdU02.07 — CheckOut** — Depois de submeter a compra, é apresentado ao cliente os dados para o pagamento da mesma e os tipos de pagamento.

* **CdU02.08 — Login** — Tanto o cliente como o admin têm de fazer login para efetuarem as suas operações.




### Recolha/Envio (Cdu03.#)

![image](Images\UC_Recolha_Envio.JPG)

* **CdU03.01 — Notifica Data/Hora entrega** —  O admin notifica o cliente acerca da data e hora da entrega da sua encomenda.

* **CdU03.02 — Verifica Encomenda** — O Admin faz uma verificação da encomenda antes de notificar o cliente e o produtor.

* **CdU03.3 — Valida encomenda** —  Após a verificação, o admin valida a encomenda 

* **CdU03.4 — Notifica produtor** — Depois de validar a encomenda, o admin notifica o produtor.

* **CdU03.5 — Separa produtos** — Assim que notificado pelo admin, o produtor procede à separação dos mesmos.

* **CdU03.6 — Embala produtos** — Após a separação dos produtos, o produtor procede ao seu embalamento.

* **CdU03.7 — Requisita transporte** — O admin, requisita os meios de recolha e entrega dos produto.

* **CdU03.8 — Recolhe produtos** — Após requisição, é efetuada a recolha dos produtos pela empresa de transporte.

* **CdU03.9 — Entrega encomenda** — Após a recolha dos produtos no produtor é efetuado o envio dos mesmo ao cliente.

* **CdU03.10 — Recebe encomenda** — O cliente procede à receção da sua encomenda.

## Regras de Negocio
As Regras de Negoçio (RN) são a fonte de muitas decisões de negoçios. Podem alterar a qualquer momemnto e podem impactar mais do que casos de uso. É importante seguir e identifica-los.

* **RN01 — Custo da encomenda** — O Custo da encomenda pode alterar de acordo com o municipio em o cliente resida, caso este não pertença ao municipio que aderir a plataforma, lhe será cobrado uma taxa 0.01% por quilometro.

* **RN02 — Escolher produto** — Após as 15.00pm, as encomendas que o cliente fizer serão enviados no dia seguinte.

* **RN04 — Tempo para Cancelar Encomenda** — A encomenda pode ser cancelada antes das 14:30pm caso tenha feito a encomenda no dia anterior apartir das 15:00pm até 14:30 do dia em causa.

* **RN05 - Desconto** - Por cada compra acima de 50 euros o cliente tem 5% de desconto.

* **RN06 - Devoluções** - O produtor que tiver um número 25% de devoluções deve ser notificado, 50% deve ser banido sistema.

* **RN07 - Transporte** - O processo de recolha e envio dos produtos é efetuado uma vez por dia como forma de promover a sustentabilidade ambiental.

* **RN08 - Comprar** - Só pode usufruir da plataforma o cliente que estiver registado.


## Requisitos Técnicos

Nesta secção foram incluidas as regras de negoçios, os requisitos não-funcionais , os constrangimentos, também nesta secção foram incluidos os pressupostos tidos em conta pela equipa.

## Requisitos Não Funcionais


* **RNF01 — Plataforma** - A aplicação suporta no máximo 100 pessoas conectadas simultaneamente. 

* **RNF02 — Compatibilidade** - A aplicação tem se ser compatível com o sistema opracional Android a partir da versão 4.0.3. 

* **RNF03 — Plataforma web** - Toda a atividade relacionada com o cliente é realizada numa plataforma Web.

* **RNF04 — Usabilidade** - Design responsivo nas interfaces gráficas.

* **RNF05 — Performance** - O utilizador não deve esperar mais de 3 segundos, em média, para visualizar novo conteúdo após um clique do rato.

* **RNF06 — Recursos** - A aplicação não deve exigir muito processamento nem memória.

* **RNF07 — Tipo de Interface** - Usar formulário para entrada de dados e dialog boxes, Maximizar a facilidade de uso via teclado e não via rato.

* **RNF08 — Web Browser** - O sistema deve ser compatível com as versões correntes do Chrome, Safari, Firefox, Microsoft Edge, Etc. 

* **RNF09 — Conta Cliente** - O utilizador deve ter mais de 18 anos.


## Pressupostos e constrangimentos

Pressupostos e constrangimentos que tenham impacto sobre o projeto:

* **PC01 — Data Limite** - O projeto deverá estar pronto a arrancar no 2º semestre, para validar os protótipos.

* **PC02 — Equipamento** - A equipa irá utilizar software com licença pedagogica, IDEs, BitBucket e Jira. Os computadores terão sistema operativo com licença pedagogica. Todo e qualquer equipamento requesitado será providenciado. 

* **PC03 — Lingua** - A plataforma suporta os idiomas português, inglês e francês, sendo o português o idioma predefinido.

* **PC04 — Custo** - O projecto terá um custo de três salários de desenvolvedores e um para o orientador do projeto durante o tempo de vida útil do projeto, isto envolve também manuntençao da plataforma.

* **PC05 — Beneficio** - O projecto vai trazer valor aos produtores locais e experiência aos desevolvedores do projeto.


[Back Home](Home)