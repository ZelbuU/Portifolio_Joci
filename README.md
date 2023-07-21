# Portifolio_Joci


<h1> Projeto: Portifólio de Joci </h1>

Arquivo (s):
<ul>
  <li>gdpro</li>
</ul>

  Descrição: Página Web que calcular a média aritmética de quatro notas.
  
  Tecnologia utilizadas:
  
 <ul>
    <li>HTML</li>
 </ul>  
 
 Dificuldades/erros entrados durante o desenvolvimento do projeto:
 
Erros: Eu errei muito nas aspas, em ('volue') e ('nota1'). Eu estava colocando essas "", e errei em muitas letras.

dificuldade: Em ver o reultado da média.

Solução:  var resultado = document.getElementById('resultado') esse codigo serve para Retorna a referência do elemento através do seu ID. e  resultado.innerHTML = essa propriedade define ou obtém a sintaxe HTML ou XML descrevendo os elementos descendentes.



<h1> Aula do dia 25/05/2023 </h1>

Arquivo (s):
<ul>
  <li>Media_Ponderada.txt</li>
</ul>

Tecnologia Utilizadas:

<ul>
  <li>Google apps script e HTML</li>
</ul>  

Resumo da aula: tevemos uma aula de fixação de conteudo, e o professor nos ajudou a desenvolver o codigo: Era pra fazer uma página que calcula média ponderada de 2 notas, mas estava errada, não conseguimos ter os calculos, porque o não estava enviando os dados ao servidor, e o professor nos ensinou a como calcular ponderada.

Codigos Utilizados: text, e number, h1. e <button onclick=""></button>, <script> </script> etc, e utilizamos um novo codigo google.script.run: um objeto fornecido pelo Google Apps Script que permite chamar funções no servidor.

Link:https://script.google.com/macros/s/AKfycby4N2HFW5_fRz5xOdTm3r92eXVm6mQb2g-5DzZbFUYhIoRFIE6Vvjh28LbaqR6V1eeC/exec


<h1> Aula do dia 01/06/2023 </h1>

Arquivo (s): 
<ul>
 <li>Media_Ponderada.txt</li>
</ul>

Tecnologia Utilizadas:

<ul>
  <li>Google apps script e HTML</li>
</ul>  

Resumo da aula: O professor nos ensinou uma nova função: google.script.run.withSuccessHandler: Uma função que envia dados ao servidor, e com isso conseguimos fazer a atividade passada(25/05/2023).

Códigos Utilizados: Os mesmo da aula passada(25/05/2023), e um novo código: google.script.run.withSuccessHandler(funcaoRetorno): Um metodo que define a função de retorno de chamadaque será chamada no cliente quando a função do servidor for executada om sucesse.

Link:https://script.google.com/macros/s/AKfycby4N2HFW5_fRz5xOdTm3r92eXVm6mQb2g-5DzZbFUYhIoRFIE6Vvjh28LbaqR6V1eeC/exec

<h1> Aula do dia 02/06/2023 </h1>

Arquivo (s):
<ul>
  <li>Login.txt</li>
</ul>

Tecnologia Utilizadas:

<ul>
  <li>Google apps script e HTML</li>
</ul>  

Resumo da aula: Fizemos um código para cadasstrar o e-mail e senha do usuário, o e-mail e senha são fixo, eu que passava o comando, e agora etou fazendo o meu portifólio

Códigos Utilizados: <label>, <input type=, usamos os códigos password, email, e submit, <form> </form>, <script> </script>, var, document.getElementById, google.script.run.withSuccessHandler.
E no Código.gs utilizei essee códigos  if (email === emailCorreto && senha === senhaCorreta) {
    return 'Login bem-sucedido';
  } else {
    return 'Login falhou';
  }
}
A fução if: É uma estrutura de controle condicional presente em várias linguagens de programação, incluindo JavaScript. "==" verifica a igualdade de dois valores. Ele retorna verdadeiro se os dois valores forem iguais, e falso se forem diferentes."&&" ele é usado para combinar duas expressões booleanas e retorna verdadeir, falso caso for oa contrário. else ele é utilizado em conjunto com "if" para criar ramos alternativos de execução de código.

Link:https://script.google.com/macros/s/AKfycbywAV9QO5MOPapdNf1NDZERmnemWgLBpX-UCXWtOzPKDavUOYLUaTq7mZE8U8CXwXzk/exec


<h1> Aula do dia 15/06/2023 </h1>


Arquivo (s):
<ul>
  <li>AttDeFixação.txt</li>
</ul>


Tecnologia Utilizadas:

<ul>
  <li>Google apps script e HTML</li>
</ul>  

Resumo da Aula: Aprendemos a como pegar um URL.

Códigos Utilizados:

Essa função serve para receber os dados do formulário

function doPost(e){
  Logger.log(e.parameter.msg)
  Logger.log(e.parameter.endereco)
}

Essa função que retorna a URL da aplicação

function pegarUrl(){
 var url = ScriptApp.getService().getUrl();
 return url
 }


<h1> Aula do dia 16/06/2023 </h1>


Arquivo (s):
<ul>
  <li>AttDeFixação.txt</li>
</ul>


Tecnologia Utilizadas:

<ul>
  <li>Google apps script, HTML, Google Drive</li>
</ul>  


Resumo da Aula: Fizemos o google apps script enviar uma mensagem para o servidor, o servidor não retornou, a mensagem retornou nas execucões do Apps Script. Bom, foi isso que eu me lembro de ter feito.

Códigos Utilazados: 

Essa função serve para pegar a URL 

<? var url = pegarUrl() ?>
  
Essa função serve para retorna a URL

function pegarUrl(){
 var url = ScriptApp.getService().getUrl();
 return url
 }

 E usamos novamente o código Logger.log. Essa função serve para receber os dados do formulário

function doPost(e){
  Logger.log(e.parameter.msg)
  Logger.log(e.parameter.endereco)
}

Link: https://script.google.com/macros/s/AKfycbx3HLwYonu-gxYQETN3-BfuadkYVuCXohMqGmVZQCC1P7JfxUQ8P3eHepcrvN1u0KA/exec



<h1> Aula do dia 21/06/2023 </h1>


Arquivo (s):
<ul>
  <li>AttAvaliativa1.txt</li>
</ul>


Tecnologia Utilizadas:

<ul>
  <li>Google apps script</li>
</ul>  

Resumo da Aula: Nessa aula fizemo uma Atividade Avaliativa, que tinha que saber qual era a distancia que uma mulher estava da casa de sua mãe, e quanto ela iria gastar de gasolina, e o preço da gasolina.


Códigos Utilizados: 

<label for="preco"> </label>

<input type="" id="" ="">

<button onclick="()"> </button> </br>

<script> </script>

E com essa função conseguimos multiplicar a distancia e oconsumo, e depois dividimos o preço.

function doGet() {
   return HtmlService.createTemplateFromFile('Gasosa').evaluate();
}
function valorFinal(distancia, consumo, preco){
var custo = ((distancia/consumo)*preco);
return custo;
}

Link: https://script.google.com/macros/s/AKfycbztCCv6OYA1KnFGedphXfkZyvorwFBplrMtfG0sw4DtfXM2aCXfdKZlsXO7BNN6sDQ/exec

<h1> Aula do dia 22/06/2023 </h1>


Arquivo (s):
<ul>
  <li>AttAvaliativa2.txt</li>
</ul>


Tecnologia Utilizadas:

<ul>
  <li>Google apps script</li>
</ul>  


Resumo Da Aula: Nessa tivemos que fazer a segunda atividade avaliativa, mas nessa eu só fiz copiar o primeiro código e fazer um form, e acessalo pelaas execuções do Apps Script.

Códogos Utilizados: 

 Para pegar a URL
 <? var url = pegarUrl() ?>
<form action="<?= url ?>" method="POST">

 function pegarUrl(){
 var url = ScriptApp.getService().getUrl();
 return url
 }












