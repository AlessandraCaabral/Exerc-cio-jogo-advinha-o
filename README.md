<h1>Resoluação do exercício advinhe o número plataforma Alura<\h1>


> Status: Resolvido. 

  
  <meta charset="utf-8">

<script>

	function pulalinha() {
		document.write("<br><br>")
	}

	function mostra(frase){

		document.write(frase)
		pulalinha()
	}

function sorteia(n){
    return Math.round(Math.random() * n);

}

var numeroPensado = sorteia(20); 

var chute = parseInt(prompt("Estou com um número na minha cabeça. Caro aventureiro, quer se arriscar em um bom chute? Pense em um número de 0 até 20")); 

	if (chute == numeroPensado) {

		mostra("BOAAAAAAAA AVENTUREIRO, VOCÊ ACERTOU!!! Eu estava mesmo pensando no número" + numeroPensado);                                                                                                                           
	} else {

		if (chute > numeroPensado) {

			mostra("Você errou! Seu chute é maior que o número pensado!"); 

	
	} else
	{

		mostra(" Eitaaaaa você errou ! ;/ Eu tinha pensando no número ... " + numeroPensado); 
	}
}
</script>
