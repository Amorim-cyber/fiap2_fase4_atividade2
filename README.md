<H1>Capítulo 7 - Power BI // FASE 4</H1>

<h3>Início</h3>

No <a href="https://github.com/Amorim-cyber/fiap2_fase4_atividade1">projeto anterior</a> desenvolvemos o procedimento de ETL dos dados do nosso projeto, montamos o cubo baseado no modelo dimensional e publicamos o mesmo em um ambiente OLAP.

<img src="assets\STAR.png"> 



O intuito do projeto `Capítulo 7 - Power BI // FASE 4` será utilizar o modelo dimensional acima no <b>Power BI</b>. Vamos elaborar relatórios analíticos e explica-los caso a caso.

Este documento será dividido nos seguintes tópicos:

* Composição dos dados no Power 
* Elaboração do relatório
* Considerações finais

<hr>

<h3>Composição dos dados no Power BI</h3>

Procuramos transformar os dados localizados no banco Oracle em planilhas de excel afim de facilitar a carga no Power BI. Clique <a href="excel">aqui</a> caso queira visualiza-los. 

<IMG src="assets\excelFiles.png">

Dentro do Power BI, importamos e tratamos cada arquivo. A relação entre as tabelas ficou da seguinte forma:

<IMG src="assets\Modelo.png">

Será por meio desse modelo que iremos construir nosso relatório.

<hr>

<h3>Elaboração do relatório</h3>

Como nossa aplicação presa em ajudar tanto prestadores de serviços quanto moradores, resolvemos separar a analise sobre esses dois tipos de usuários.

* <b>Análise morador</b>

  Desenvolvemos o dashboard do morador na seguinte forma:

  <img src="assets\analiseMorador.png">

  

  <img style="float: left;" src="assets\filtro.png">

  

  <b>Definição:</b>  Um filtro simples, separado por 3 categorias de morador: Free Trial, Standard e Premium. Dentro de cada categoria conseguimos filtrar por morador.

  

  <b>Por que inclui-lo?</b>

  A motivação é analisar diferenças de consumo por tipo de cliente, ver se existe um padrão de consumo. 

  O filtro serve também como uma ferramenta de busca para encontrar informações específicas sobre um determinado morador. 

  

  

  <img style="float: left;" src="assets\gastoPorMaterial.png">

  

  <b>Definição:</b>  Um gráfico rosca detalhando os valores gastos por materiais e suas respectivas porcentagens. Com este é possível visualizar facilmente a participação de cada tipo de gasto no total investido.

  

  <b>Por que inclui-lo?</b>

  É importante termos conhecimento sobre quais materiais foram utilizados para negociar promoções com os nossos parceiros. Neste exemplo, Ardelia comprou mais de 7 mil reais em caixa de luz, poderíamos criar uma promoção customizada para ela oferecendo um desconto nas proximas compras desse produto em específico.

   <img style="float: left;" src="assets\gastoPorProfissao.png">

  

  

  

  

  

  

  

  

  

  <b>Definição:</b>  Um gráfico "pizza" detalhando os valores gastos por profissão e suas respectivas porcentagens, tornando mais clara a visualização do gasto de cada profissão perante o total.

  

  <b>Por que inclui-lo?</b>

  Precisamos ter essa informação afim analisar qual profissional se sobressai e qual não é demandado nesse mercado. 

  

  <img style="float: left;" src="assets\valorTotal.png">

  

  <b>Definição:</b>  Uma soma simplificada do total de gasto.

  

  <b>Por que inclui-lo?</b>

  Para realizar uma análise relativa perante os demais dados do relatório.

  

  

  <img style="float: left;" src="assets\valorTotalGastoAno.png">

  <b>Definição:</b> Um gráfico de área mostrando a evolução dos gastos filtrados por ano, separados pelo ano anterior, atual e seguinte.

  

  <b>Por que inclui-lo?</b>

  Identificar tendências de consumo entre os anos. Neste exemplo podemos olhar uma tendencia de queda desse ano para o ano passado, teremos que rever todo nosso plano de negócios caso essa tendencia permaneça em um quadro mais amplo.

  

  

  <img style="float: left;" src="assets\valorTotalGastoRegiao.png">


  

  <b>Definição:</b> Um gráfico de barra mostrando o gasto por cada região/ano. 

  

  <b>Por que inclui-lo?</b>

  Analisar o comportamento de consumo por região ao longo do tempo. Neste exemplo observamos uma mudança de endereço aonde ocorre os serviços nos últimos dois anos.  

  

  

  <img src="assets\concentracao.png">

  

  <b>Definição:</b> Um mapa detalhado da onde foram feitos os serviços. Dar uma outra visualização aos dados. Essa cliente teve 3 registros de serviços, sendo 2 em Minas gerais e 1 na Bahia. Quanto maior o numero de registros maior o tamanho do circulo 

  

  <b>Por que inclui-lo?</b>

  Oferecer uma visualização mais atraente aos dados

  

* <b>Análise prestador</b>

  Seguindo a mesma lógica do relatório de moradores, o relatório de prestadores ficou da seguinte forma:

  <img src="assets\analisePrestador.png">



<hr>

<h3>Considerações finais</h3>

Buscamos aplicar nosso modelo construído no projeto passado para o universo do Power BI. Geramos relatórios dinâmicos tanto para a parte demandante (Prestador) quanto para a ofertante (Morador). O <a href="reports\Relatorio.pdf">relatório</a> mostrado aqui ilustra uma análise de apenas um morador e um prestador, contudo fique a vontade para ter acesso ao arquivo completo clicando <a href="powerBI\BI.pbix">aqui</a>.



<h3>Forte Abraço!</h3>











