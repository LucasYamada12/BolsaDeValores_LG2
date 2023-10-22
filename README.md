#Pregão na bolsa de valores

## Descrição:
<p>
Esta aplicação simula um pregão na bolsa de valores, o período diário de negociaçãos de ações entre compradores e vendedores.
</p>

## Funcionalidades:
<p>
<strong>Investidor:</strong> pessoa que é cliente de uma ou mais corretora e que envia ordens de compra e venda de ativos, consegue comprar ativos por meio da corretora, e os armazena em um array, além de ser possível adicionar mais dinheiro na conta do Investidor, e possuí um Tratamento de excessões, que não permite a compra de ativos que superem a quantidade de dinheiro na conta do investidor, e não deixa o Investidor comprar um número de ativos menor do que 0.
<p/>  
<p>
<strong>Carteira:</strong> são os ativos que foram comprados pelo Investidor, recebe como paramêtro em seu método construtor a lista dos ativos do Investidor.
<p/>
<p>
<strong>Corretora:</strong> empresa que realiza o serviço de envio das ordens de seus clientes, possui um atributo "taxa", uma remuneração pelos serviços prestados pela corretora de valores ou bancos e impacta diretamente no preço que os ativos podem ser vendidos e comprados, cobrando uma certa taxa pra cada ativo comprado pelo Investidor.
<p/>
<strong>Ativos:</strong> papel negociado pelas empresas listadas na bolsa pode ser Ações ordinária, preferenciais ou FII - fundos de investimentos imobiliários.
<p>
<p>
<strong>FII e Ações:</strong> são subclasses da classe "Ativos" e herdam seus métodos e atributos.
</p>
<strong>Bolsa:</strong> empresa responsável pelas negociações realizadas durante o pregão, possui uma lista que guarda os ativos dos Investidores, e uma lista que guarda as corretoras, que pertencem à esta empresa.
<p/>
<p>
<strong>Custodiante:</strong> detentor ou fiel depositário de garantia dos papéis negociados, possui uma lista que conteém as carteiras dos Investidores.
</p>
<p>
<strong>Dynamic Array:</strong> estrutura de dados dinâmica implementada para a construção da aplicação.
</p>

## Atividade realizada por:
<p>
Lucas Eiki Yamada</br>
Júlio Antunes Estrela(https://github.com/JulioEstrela)
</p>
