# Desafio-Controle-de-Fluxo-Java

<p>O sistema deverá receber dois parâmetros via terminal que representarão dois números inteiros, com estes dois números você deverá obter a quantidade de interações (for) e realizar a impressão no console (System.out.print) dos números incrementados, exemplo:</p>
  Se você passar os números 12 e 30, logo teremos uma interação (for) com 18 ocorrências para imprimir os números, exemplo: `"Imprimindo o número 1"`, `"Imprimindo o número 2"` e assim por diante.
 <br>
  Se o primeiro parâmetro for MAIOR que o segundo parâmetro, você deverá lançar a exceção customizada chamada de `ParametrosInvalidosException` com a segunda mensagem: "O segundo parâmetro deve ser maior que o primeiro"
 <ol>
  <li>Crie o projeto `DesafioControleFluxo`</li>
  <li>Dentro do projeto, crie a classe `Contador.java para realizar` toda a codificação do nosso programa.</li>
  <li>Dentro do projeto, crie a classe `ParametrosInvalidosException` que representará a exceção de negócio no sistema.</li>
 </ol>
<p>Abaixo temos um trecho de código no qual você poderá seguir alterando as partes que contenham `??`</p>
<br>



    public class Contador {
	      public static void main(String[] args) {
	      Scanner terminal = new Scanner(System.in);
	      System.out.println("Digite o primeiro parâmetro");
	      int parametroUm = terminal.??;
	      System.out.println("Digite o segundo parâmetro");
	      int parametroDois = terminal.??;
       	      try {
			//chamando o método contendo a lógica de contagem
			contar(parametroUm, parametroDois);
		
	      }catch (? exception) {
			//imprimir a mensagem: O segundo parâmetro deve ser maior que o primeiro
	      }
      	}



