# Desafio-Banco-DIO

***Condições, Loops e Exceções na Prática com Java***


```
Desafio prático de Código do BootCamp Santander 2024;
Trilha Back-End JAVA
```


> Minhas soluções foram testadas fora do ambiente da DIO no Intellijei Community 2023 e aprendi uma maneira de resolver os desafios de forma mais rápida e com menos erros 👽;


### O repositorio no ![Static Badge](https://img.shields.io/badge/git-hub-blue) 🎱


> Primeiramente vamos a maneira correta de testar cada desafio fora do ambinete do desafio, ele funciona de forma diferente do ambinete de uma IDE;

> Eu utilizei o Intellijei mas podem usar a de sua preferência, o importante é compreender a lógica proposta pelo desafio primeiramente;

***O Código***⚛️

> AS classes foram criadas dentro do pacote "com.desafios.dio", basicamente como uma forma de encapsular o coidgo vamos dizer assim, para que na Main so sejam chamados os metodos que solucionam os desafios;

![codigo.png](src/assets/codigo.png)


> Assim a Main ficaria assim:

![image.png](src/assets/main.png)

***obs***‼️

➡️ Reparem que os códigos estão comentados, descomente um de cada vez e teste como quiser;

➡️ Fiquem atentos aos imports, por exemplo, se você descomentar  "ErrorEXC.java" terão que importar do pacote "com.desafios.dio.*", assim ficarão disponiveis todas as classes do pacote ;


### A Plataforma DIO 🛰



> Na plataforma vc tem um ambiente semelhante ao abaixo no primeiro desafio;


> import java.util.Scanner;
>
> public class SimulacaoBancaria {
>
> public static void main(String[] args) {
> Scanner scanner = new Scanner(System.in);
> double saldo = 0;
> boolean continuar = true;
>
> while (continuar) {
>
>     int opcao = scanner.nextInt();
>
>     switch (opcao) {
>         case 1:
>             // TODO: Ler o valor a ser depositado e atualizar/imprimir o saldo.
>             break;
>         case 2:
>             // TODO: Ler o valor a ser sacado e verificar/imprimir se há saldo suficiente.
>             break;
>         case 3:
>             // TODO: Exibir o saldo atual da conta.
>             break;
>         case 0:
>             System.out.println("Programa encerrado.");
>             continuar = false;  // Atualiza a variável de controle para encerrar o loop
>             break;
>         default:
>             System.out.println("Opção inválida. Tente novamente.");
>     }
> }
> scanner.close();
> }
>
>
>
>
>> Inserindo minha resposta recebi que meu codigo não passou no teste;
>>
>
> ![image.png](assets/dio.png)
>
>
>> Mas se rodarmos o código na iDE ele funciona, aqui eu percebi que na plataforma e necessário que a grafia das saidas estejam corretas também, se repararmos a saída esperada esta diferente da minha saída já que "Saldo Insuficiente" estão sem o ponto final e o "I" é maiusculo, devemos nos atentar a este detalhes, Corrigindo os testes ficam ok para a entrega dos desafios;
>>
>
> ![image.png](assets/solucao.png)
>
>
> ### Conclusão ☑️
>
>
> ***Estes simples desafios oferecem uma boa maneira de estudar e aguçar a lógica e o pensamento computacional de inicinates na programação, tornando assim mais simples o aprendizado da linguagem 😏***;
>
>
> **Vamos nos conectar** [My github](https://github.com/rafaelrss41) 👽 !!
>
>
