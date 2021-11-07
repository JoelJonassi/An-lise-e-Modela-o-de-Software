# Business processes modelling
Para o cliente comprar os produtos e beneficiar da entrega ao domicilio no mesmo dia util, terá que comprar na plataforma antes da 15:00. Caso nao haja o produto a camara recorrerá aos produtores locais para se abastecer.

![BPMN_diagram.png](https://bitbucket.org/repo/y5rxLzz/images/3667922231-BPMN_diagram.png)
----

# Modelo de domínio
 
O diagrama inicial permite dar vislumbre do projecto, mostrando as entidades do sistema. Este modelo ajuda as partes interressadas a ter uma compressão comum acerca do domínio do sistema.

 
## Diagrama
 
 O Diagrama abaixo ilustra as entidades que foram consideradas na primeira fase "1º Sprint", para a implementação do projeto.


![Diagrama_dominio](images/Diagrama_dominio.png)


# Definições

* **Utilizador** - Os produtores, os clientes e a câmara municipal que usufrem da Plataforma web.

* **Produtor** - Representa o vendedor que pretende alanvacar as suas vendas, usufruindo do sistema.

* **Cliente** - O comprador do produto.

* **Camara Municipal** - Entidade que valida um produtor, nediante assinatura presencial e validade de possuir produtos locais.
  
* **Login** - Para os utilizadores da plataforma poderem usufruir devem estar registados, para fazer uma encomenda devem ter iniciado a sessão na plataforma.

* **Presença** - Prova presencial que o produtor deve fazer, para ser validada a sua conta na plataforma como sendo produtor.
  
* **Produto** - Alimento especifico, preço.

* **Categoria** - Categoria de alimentos.
  
* **Preço** - Valor que o produto custa em €.
  
* **Consultar** - Funcionalidade que permite a câmara municipal consultar os produtos em stock.
  
* **Stock** - Produto disponivel para venda.
  
* **Carrinho** - No processo de escolha dos produtos o cliente pode coloca-los no carrinho.

* **Pagamento** - Transação eletrónica, que permite pagar produto.
  
* **Fatura** - Após o pagamento é emitida uma fatura para o cliente.

* **Transporte do Produto** - Meio de transporte para o envio das encomendas.

* **Encomenda** - Conjunto de produtos.



  
[Pagina Inicial](Home)