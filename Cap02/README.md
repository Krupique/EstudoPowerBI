# Descrição do Capítulo 2

## Primeiros passos com Power BI Desktop

<div align="justify">
  Drill down e Drill up (Descer na granularidade) <br/>
  É a capacidade de ir descendo nos dados, por exemplo. Exibir o grupo por ano, descer e exibir por semestre, descer e exibir por trimestre, por mês, por dia, etc... <br/>
  <b>Observação</b>: Quando tiver problemas com acento é problema de encoding. Quando estiver com problemas de tipo de dados, é a configuração regional.

 </div>
 
 ## Power BI Desktop Workflow
 ![image](https://user-images.githubusercontent.com/30851656/152414929-04fb9e28-f301-4c2e-a9a1-e28fccca2e81.png)

<div align="justify">
  Toda análise começa com a definição do problema a ser resolvido.<br/>
  Dashboard são vários gráficos na mesma tela.<br/>
Como o estudo é olhar para o passado, a técnica aplicada será Business Inteligence. Análise descritiva.<br/>
  Um <b>dashboard</b> de Power BI é uma única página, geralmente chamada de tela, que usa visualizações para contar uma história. Como ele é limitado a uma página, um dashboard bem projetado contém apenas os elementos mais importantes da história.<br/>
O cérebro não consegue processar muitas informações ao mesmo tempo.

 </div>
 
 ## Estudo de caso
 <div align="justify">
 Você é Analista de Dados na empresa XYZ Corporation International, uma revendedora de automóveis de luxo com sede em São Paulo. A empresa começou sua operação no Brasil em 2016 e atua nos quatro estados da região sudeste, mais os estados do Paraná e Bahia.<br/>
Seu gerente vai apresentar os resultados da equipe comercial para o novo CEO da empresa e precisa da sua ajuda para construir um Dashboard que represente os dados de vendas
no período de 2016 a 2019.<br/>
Sua fonte de dados é um arquivo Excel com dados coletados do sistema de vendas e CRM da empresa, com a as seguintes colunas:<br/>
 </div>
<table>
  <th>
    Coluna
    <td>Descrição</td>
  </th>
  
  <tr>
    <td>DataNotaFiscal</td>
    <td>Data de emissão da nota fiscal</td>
  </tr>
  
  <tr>
    <td>Fabricante</td>
    <td>Fabricante do veículo</td>
  </tr>
  
  <tr>
    <td>Estado</td>
    <td>Estado onde foi realizada a venda</td>
  </tr>
  
  <tr>
    <td>PrecoVenda</td>
    <td>Preço de venda do veículo</td>
  </tr>
  
  <tr>
    <td>PrecoCusto</td>
    <td>Preço de custo do veículo para a empresa</td>
  </tr>
  
  <tr>
    <td>TotalDesconto</td>
    <td>Total de Desconto fornecido sobre o preço de venda</td>
  </tr>
  
  <tr>
    <td>CustoEntrega</td>
    <td>Custo de entrega do veículo ao proprietário</td>
  </tr>
  
  <tr>
    <td>CustoMaoDeobra</td>
    <td>Custo de Mão de Obra (secretária, mecânico, etc...)</td>
  </tr>
  
  <tr>
    <td>NomeCliente</td>
    <td>Nome do cliente que comprou o veículo</td>
  </tr>
  
  <tr>
    <td>Modelo</td>
    <td>Modelo do veículo</td>
  </tr>
  
  <tr>
    <td>Cor</td>
    <td>Cor do veículo</td>
  </tr>
  
  <tr>
    <td>Ano</td>
    <td>Ano de fabricação do veículo</td>
  </tr>
</table>

<div>
Seu gerente precisa das seguintes informações: <br/>
1- Total de Vendas por Ano <br/>
2- Custo de Entrega do Veículo Por Fabricante <br/>
3- Custo de Mão de Obra Por Estado <br/>
4- Total de Vendas Geral e Matriz de Vendas <br/>
  </div>
  
 ### Solução
 ![image](https://user-images.githubusercontent.com/30851656/152416498-d8456242-f6b3-4be5-822f-c4fd4121c064.png)
