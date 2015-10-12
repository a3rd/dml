# Class Diagram

## Complete Code

<code> 
[Customer|-forname:string;surname:string|doShiz()]<>-orders*>[Order]
[Order]++-0..*>[LineItem]
[Order]-[note:Aggregate root{bg:wheat}]
</code>


### Description 

#### Node 

<code> [Customer|-forname:string;surname:string|doShiz()] </code>


#### Edge 

<code> [A]<>-text*>[B] </code>

<code> [C]++-text..*>[D] </code>

<code> [E]-[F] </code>

### Description - [Order] node


### Formatting 

#### Nodes

<code> [] </code> parent container


##### Separators

<code> | </code> cell separator

<code> ; </code> line break

#### Edges

arrow types
<code> ++- </code>



# Use Case

Example code

<code>
[Customer]-(Sign In)
[Customer]-(Buy Products)
(Buy Products)>(Browse Products)
(Buy Products)>(Checkout)
(Checkout)<(Add New Credit Card)
</code>

### Formatting
#### Nodes

<code> [] </code> Actor

<code> () </code> Use Case

#### Edges

<code> - </code> standard connector

<code> < </code> <<extend>>, dashed

<code> > </code> <<include>>, dashed


