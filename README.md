# MyDev
<meta charset="UTF-8">

<script>
  function pulaLinha(){
	document.write("<br><br>");
}
  function mostra (frase){
  	document.write(frase );
  	pulaLinha();
  }	
  function calculaLitro (peso, ml)  {
  	return (pesoInformado * 35)/1000; 
  }

  var nome =  prompt("Informe o seu nome");
  var pesoInformado = parseInt(prompt( nome + " qual é o seu peso?"));
  
  var agua = calculaLitro ( parseFloat(pesoInformado * 35)/100);
  
  document.write( "<big>" + nome + "</big>" + "<big>, você precisa beber</big> " +"<big>"+agua+"</big>"+"<big>L de agua por dia!</big>");
  pulaLinha();
    mostra("<big> E por sinal, ja pode ir se hidratar!");
    mostra("Até logo!</big>");
</script>
