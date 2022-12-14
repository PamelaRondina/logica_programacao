# Curso: Lógica de Programação

## Lista de exercícios e respostas

### Atividade: 01_01_primeiro_teste.html

No primeiro teste, aprendemos:
- [x] Incluir título `<h1> </h1>`
- [x] Pular linha `<br>`
- [x] Incluir link `<a href="link">aqui</a>!`
- [x] Chamar e fechar linguagem JavaScript `<script> </script>` 
- [x] Chamar um pop up `alert`

```html
<h1>Meu primeiro teste!</h1>
<br>
Seria isso um programa? Descubra visitando o Alura <a href="http://www.alura.com.br">aqui</a>!

<script>
alert("Isso sim é um programa");
</script>
```
Resultado:

**Pop Up**

![image](https://user-images.githubusercontent.com/108991648/182516300-c059ffa6-12e6-4e21-9026-126653edc865.png)

![image](https://user-images.githubusercontent.com/108991648/182516389-f636c45d-65c4-4278-a28c-410090bd25c4.png)

______
### Atividade: 02_08_calculando_gastos.html

Realizar a conta para localizar a média: 200 + 100 + 300 + 400 / 4:

```html
<meta charset="UTF-8">
<br><br>

<script>
    document.write("A média do valor gasto com as viagens é ");
    document.write((200 + 100 + 300 + 400) / 4);
</script>
```
Resultado:

![image](https://user-images.githubusercontent.com/108991648/182516769-bac68a2f-8b45-4b09-9b19-d62600158f5e.png)

______
### Atividade: 02_12_prova.html

 Criar um programa para saber qual a sua porcentagem de acertos.
- [x] Prova de 50 questões de múltipla escolha. 
- [x] **/** a quantidade de acertos pelo total de questões
- [x] **x** o resultado final por 100 

```html
<meta charset="UTF-8">

<script>
    document.write("Eu acertei: ");
    document.write(15 / 50 * 100);
    document.write("% da prova");
</script>
```
Ou

```html
<script>
    document.write("Eu acertei: "+ 15/50*100 + "% da prova");
</script>
```
Resultado:

![image](https://user-images.githubusercontent.com/108991648/182506065-53f4b259-6ede-481a-b66e-e939b6a1cfbd.png)
______________________
### Atividade: 02_14_document_write.html

Duas programadoras:
- [x] A primeira, para pular uma linha utilizou `document.write("<br>")`
- [x] A segunda, apenas incluir `+ "<br>"` 

> Ambos os códigos dão o mesmo resultado, a programadora decide sua melhor versão!

1ª programadora:
```html
<meta charset="UTF-8">

<script>
    document.write("Flávio nasceu em " + (2016 - 39));
    document.write("<br>");
    document.write("Joaquim nasceu em " + (2016 - 20));
    document.write("<br>");
    document.write("Barney nasceu em " + (2016 - 40));
</script>
```

2ª programadora
```html
<meta charset="UTF-8">

<script>
    document.write("Flávio nasceu em " + (2016 - 39) + "<br>");
    document.write("Joaquim nasceu em " + (2016 - 20) + "<br>");
    document.write("Barney nasceu em " + (2016 - 40));
</script>
```
Resultado:

![image](https://user-images.githubusercontent.com/108991648/182507707-b9d2c164-47d6-4607-b1f1-a8fc4169a66b.png)

________________

### Atividade: 03_02_tapando_buraco.html**

Atribuir váriável.

Código inicial:
```html
<meta charset="UTF-8">

<script>
    document.write("O resultado da fórmula é : " + n * (10 / 20));
</script>
```

Código alterado, com a inclusão de `var n = 1`

```html
<meta charset="UTF-8">

<script>
    var n = 1
    document.write("O resultado da fórmula é : " + n * (10 / 20));
</script>
```
________________

### Atividade: 03_05_tabuada

A programadora escreveu o código que exibe na tela o resultado da tabuada de 5! 

```html
<meta charset="UTF-8">

<script>
    document.write("5 vezes 1 é " + 5 * 1+ "<br>");
    document.write("5 vezes 2 é " + 5 * 2+ "<br>");
    document.write("5 vezes 3 é " + 5 * 3+ "<br>");
    document.write("5 vezes 4 é " + 5 * 4+ "<br>");
    document.write("5 vezes 5 é " + 5 * 5+ "<br>");
    document.write("5 vezes 6 é " + 5 * 6+ "<br>");
    document.write("5 vezes 7 é " + 5 * 7+ "<br>");
    document.write("5 vezes 8 é " + 5 * 8+ "<br>");
    document.write("5 vezes 9 é " + 5 * 9+ "<br>");
    document.write("5 vezes 10 é " + 5 * 10+ "<br>");
</script>
```
Altere para a tabuada do 8 incluindo variáveis:

```html
<meta charset="UTF-8">

<script>
    var n = 8
    document.write(n + " x 1 = " + n * 1 + "<br>");
    document.write(n + " x 2 = " + n * 2 + "<br>");
    document.write(n + " x 3 = " + n * 3 + "<br>");
    document.write(n + " x 4 = " + n * 4 + "<br>");
    document.write(n + " x 5 = " + n * 5 + "<br>");
    document.write(n + " x 6 = " + n * 6 + "<br>");
    document.write(n + " x 7 = " + n * 7 + "<br>");
    document.write(n + " x 8 = " + n * 8 + "<br>");
    document.write(n + " x 9 = " + n * 9 + "<br>");
    document.write(n + " x 10 = " + n * 10 + "<br>");;
</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/182622666-5b447bca-42c6-4a29-8885-264c7d6710cc.png)
__________________

### Atividade: 03_08_detetive_roy.html

O detetive Roy localizou este código:

```html
<meta charset="UTF-8">

<script>
    document.write( (12 + 15 + 13) / 3);
</script>
```

O programa calcula a média dos dados:
- [x] Linda tem 12 anos;
- [x] Guaraciara tem 15 anos;
- [x] Pérola tem 13 anos.

Melhorando o código do programa:

```html
<meta charset="UTF-8">

<script>
    var idadeLinda = 12;
    var idadeGuaraciara = 15;
    var idadePerola = 13;
    var media = (idadeLinda + idadeGuaraciara + idadePerola) / 3;
    document.write(Math.round(media));
</script>
```


> note que o segundo resultado está arredondado devido a função `Math.round()` no segundo código.

Resultado:

![image](https://user-images.githubusercontent.com/108991648/182669422-b8961e6a-92b1-4246-b712-a42562a94b29.png)

Melhorando, ainda mais o código:

```html
<meta charset="UTF-8">

<script>
    var idadeLinda = 12;
    var idadeGuaraciara = 15;
    var idadePerola = 13;
    var soma = idadeLinda + idadeGuaraciara + idadePerola
    var media = (soma) / 3;
    document.write(Math.round(media));
</script>
```

__________

### 03_12_calcula_consumo.html

Álcool ou Gasolina?

Problema:
- Veículo com tanque de <b>40</b> Litros; 
- Tanque cheio faz <b>480km</b> com Gasolina;
- Tanque cheio faz <b>300km</b> com Álcool.

Para calcular:
- Distância percorrida / quantidade de litros gastos
- Imprima o valor utilizando document.write.
- Organize as contas em variáveis

Qual é o <b>consumoDeGasolina</b> e o <b>consumoDeÁlcool</b>? <br><br>

```html
<meta charset="UFT-8">

<script>
 var tanque = 40;
 var caminhoComGasolina = 480;
 var caminhoComÁlcool = 300;
 var consumoDeGasolina = caminhoComGasolina / tanque;
 var consumoDeÁlcool = caminhoComÁlcool / tanque;

 document.write("Veículo com tanque de " + tanque + " litros.<br><br>");
 document.write("Com gasolina, o tanque cheio percorre " + caminhoComGasolina + "km;<br>");
 document.write("Com álcool, o tanque cheio percorre " + caminhoComÁlcool + "km.<br><br>");
 document.write("Meu consumo com gasolina é de " + consumoDeGasolina + "km por litro.<br>");
 document.write("Meu consumo com álcool é de " + consumoDeÁlcool + "km por litro.");
</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/182684359-b747c07c-9ea5-4246-9b5c-947bcb13e95a.png)

____

### Atividade: 04_09_alert_asteriscos.hthml

O primeiro código, está com erro, não responde no Browser.

```html
<meta charset="UTF-8">

<script>
    var idade1 = 10;
    var idade2 = 20;
    var idade3 = 30;
    var totalIdades = idade1 + idade2 + idade3;
    var mediaIdades = totalIdades/3;
    alert("***Total de idades é " + totalIdades + "***");
    alert("***A média das idades é " +  mediaIdades + "***");
</script>
```

Código alterado, responde no Browser:
- [x] incluso a `function exibeAlerta(mensagem)`, chamando um parâmetro "mensagem"
- [x] Função com informação do que deve fazer, no caso `alert()`
- [x] `alert` com parâmetro de "***" + mensagem + "***"
- [x] Resultado da função exibeAlerta é de:
   * "***" primeiro
   * em seguida, a mensagem, que está dentro das **( )** 
   * "***" por último
 
```html
<meta charset="UTF-8">

<script>
    function exibeAlerta(mensagem) {
        
        alert("***" + mensagem + "***");
    }

    var idade1 = 10;
    var idade2 = 20;
    var idade3 = 30;
    var totalIdades = idade1 + idade2 + idade3;
    var mediaIdades = totalIdades/3;

    exibeAlerta("Total de idades é " + totalIdades);
    exibeAlerta("A média das idades é " +  mediaIdades);
</script>
```

Resultado:

02 Pop Ups gerados, cada um com uma frase:

![image](https://user-images.githubusercontent.com/108991648/182914084-0acbd444-f96b-4273-9415-9b8614adeef1.png)

_______________________

### Atividade: 04_10_nao_mostra_como_fez.html

1º código:

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write("*********************************");
        pulaLinha();
        document.write(frase);
    }

    mostra("BEM-VINDO AO MEU PROGRAMA");
    mostra("ELE REALMENTE FUNCIONA")
    mostra("EU USEI FUNÇÃO PARA FAZER ISSO")
</script>
```

2º código:

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write("*********************************");
        pulaLinha();
        document.write(frase);
        pulaLinha()
    }

mostra("BEM-VINDO AO MEU PROGRAMA");
mostra("ELE REALMENTE FUNCIONA")
mostra("EU USEI FUNÇÃO PARA FAZER ISSO")
</script>
```

3º código: 
```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
                document.write("*********************************");
        document.write(frase);
        pulaLinha()
    }

mostra("BEM-VINDO AO MEU PROGRAMA");
mostra("ELE REALMENTE FUNCIONA")
mostra("EU USEI FUNÇÃO PARA FAZER ISSO")

</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/182917036-baa845dd-d269-4416-b4c5-e22494af4d6a.png)

____________

### Atividade 04_12_a_diferença_na_idade.html

Faça um programa onde:
- [x] Tenha a sua idade
- [x] A idade de uma irmã/amigo
- [x] Mostre a diferença entre elas

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(texto){
        document.write("Idade Pamela é " + idadePamela);
        pulaLinha();
        document.write("Idade Ysa é " + idadeYsa);
        pulaLinha();
        document.write(texto);
        pulaLinha();
    }

var idadePamela = 30;
var idadeYsa = 13;
var subtraçãoIdades = idadePamela - idadeYsa

mostra("Nossa diferença de idade: "+ subtraçãoIdades + " anos");

</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/182943251-ff1a2d82-503a-4288-81be-cd3d6241932f.png)

________________________

### Atividade 04_13_problema_das_geracoes

Problema: em média, um casal tem filhos quando atinge a idade de 28 anos. Seguindo essa média, se os portugueses chegaram em 1500 no Brasil, então, a primeira geração de brasileiros surgiu em 1528, a segunda em 1556 e assim por diante. Desde 1500 até o ano atual, quantas gerações se passaram?

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase){
        document.write("Os portugueses chegaram em " + inicio);
        pulaLinha();
        document.write("Foram passadas " + arredonda + " gerações");
    }

var inicio = 1500;
var atual = 2022;
var conta = ((atual - inicio) / 28);
var arredonda = Math.round(conta);

mostra();

</script>
```
Resultado:

![image](https://user-images.githubusercontent.com/108991648/182953921-11791751-46ab-451e-8f15-ccd9920586eb.png)

______________

### Atividade: 04_14_mostra_idade2.html

Primeiro código:

```html
<meta charset="UTF-8">

<script>

    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
   }

var ano = 2022
mostra("Eu nasci em: " + (ano - 31));
mostra("Bruno nasceu em: " + (ano - 30));
mostra("Ysa nasceu em: " +(ano - 13));

</script>
```

Código alterado:

- [x] Utilize 2 `<br>s` na função pulaLinha.
- [x] Utilize a tag `<hr>` entre os `<br>s`, criando um traço
- [x] Utilize a tag `<big>`, aumentando o tamanho da fonte

```html
<meta charset="UTF-8">

<script>

    function pulaLinha() {
        document.write("<br><hr><br>");
    }

    function mostra(frase) {
        
        document.write("<big>" + frase + "</big>");
        pulaLinha();
    
    }

var ano = 2022

mostra("Eu nasci em: " + (ano - 31));
mostra("Bruno nasceu em: " + (ano - 30));
mostra("Ysa nasceu em: " +(ano - 13));

</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/182982777-1915aa0b-f8ba-457c-abda-f3d0aa1ee59f.png)

**Execute erros e veja no console**
 - [x] Esqueça a palavra function na hora de declarar uma de suas funções.
- [x] Esqueça os parênteses na declaração da função pulaLinha

1. Uncaught SyntaxError: Unexpected token '{'

_______________

### Atividade: 05_01_imc.html 

Neste exercício, notamos a inclusão de 02 parâmetros dentro de uma função `function calculaImc (altura, peso)`

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br><br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

  function calculaImc (altura, peso) {
        var imc = peso / (altura * altura);
        var resultado = Math.round(imc)
        mostra("O imc calculado é: " + resultado);
    }
  
calculaImc(1.70, 73);
calculaImc(1.80, 90);

</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/183091089-d6bda709-2943-43ec-b89c-d01dd854e7f5.png)
______________

### Atividade: 05_05_retorno_de_funcoes.html

Nesta atividade, criamos 03 funções:
- [x] `pulaLinha` pulando 2 linhas
- [x] `mostra` escrevendo a frase e pulando 2 linhas
- [x] `calculaImc` 
    - com dois parâmetros: altura, peso
    - `var imc` para realizar o cálculo do imc
    - `var resultado` arredondando o resultado
    - `return` para retornar o resultado nas variáveis mais abaixo
- [x] `var imcPam e imcBruno`
    - Após realizar a função `calculaImc`, o `return`devolve o resultado para o `imc Pam`e para `imcBruno`
- [x] `mostra` apresenta o resultado final.


```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br><br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    function calculaImc (altura, peso) {
        var imc = peso / (altura * altura);
        var resultado = Math.round(imc);
        return resultado
    }
  
var imcPam = calculaImc(1.70, 73);
var imcBruno = calculaImc(1.80, 90);

mostra(imcPam);
mostra(imcBruno);

</script>
```

Resultado:

25 

28

__________

### Atividade: 05_08_olha_o_calculo_do_imc_novamente.html

Código com erro.

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    function calculaImc(altura, peso) {
        var imc = peso / (altura * altura);
    }

    var imcCalculado = calculaImc(1.77, 75);
    mostra("O meu IMC é : " + imcCalculado);
</script>
```

Erro localizado! Adicionando o `return` para a ultima variável ter uma resposta:

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    function calculaImc(altura, peso) {
        var imc = peso / (altura * altura);
        var resultado = Math.round(imc)
        return resultado
    }

var imcCalculado = calculaImc(1.77, 75);
     
mostra("O meu IMC é : " + imcCalculado);
</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/183136834-ea0f65ba-f95e-4984-9674-21577a795b0e.png)

_______________

### Atividade 05_10_calculaimc.html

Exercício demonstrando o resultado final em dois formatos:
- var imcCalculado = calculaImc(1.63, 48);
    mostra("O meu IMC é " + imcCalculado);
<br>
- mostra("O meu IMC é " + calculaImc(1.63, 48) );
```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br><br>");
    }

    function mostra(frase) {
        document.write(frase);
    }

    function calculaImc(altura, peso) {

        return peso / ( altura * altura );
      
    }

    var imcCalculado = calculaImc(1.63, 48);
    mostra("O meu IMC é " + imcCalculado);
    pulaLinha();
    mostra("O meu IMC é " + calculaImc(1.63, 48) );
</script>
```
Resultado:

![image](https://user-images.githubusercontent.com/108991648/183142787-80e4807e-d240-48f3-a84f-76d9f26a8f3f.png)

_____________

### Atividade: 05_11_interagindo_com_usuario.html

Nesta atividade, vamos inncluir pop ups para que o usuário possa interagir.

- [x] `prompt("texto)` abrirá um pop up para que o usuário preencha


```html
<meta cherset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br><br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    function calculaImc(altura, peso) {

        return peso / (altura * altura);
    }

var nome = prompt("Qual é o seu nome?");
var alturaInformada = prompt(nome + ", informe sua altura");
var pesoInformado = prompt(nome + ", informe seu peso");

var imc = calculaImc(alturaInformada, pesoInformado);
var imcCerto = Math.round(imc)

document.write(nome + ", o seu IMC é: " + imcCerto);

</script>
```

_____

### Atividade 05_15_agora_eu_quero_ver.html

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {

        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    function a(texto) {
        return "(" + texto + ")";
    }

    function b(texto) {
        return "@" + texto + "@";
    }

    function c(nome, sobrenome) {
        return b(nome + " " + a(sobrenome));

    }

var resultado = c("Flávio", "Almeida");

mostra(resultado);

</script>
```

O que será exibido?

Função A: 
```
function a(texto) {
        return "(" + texto + ")";
    }
```
Função B:
```
    function b(texto) {
        return "@" + texto + "@";
    }
```
Função C:
```
	function c(nome, sobrenome) {
        return b(nome + " " + a(sobrenome));
    }
```

<br>Temos que ler a seguinte variável:

```
var resultado = c("Flávio", "Almeida");

mostra(resultado);
```
<br>Vamos começar a interpretar:

- [x] `var resultado = c`
- [x] Vamos começar a ler a partir da função C 
- [x] Função C tem nome(Flávio) e sobrenome(Almeida), mas  mas ela retorna para a função B em `return b`<br><br>
- [x] Na função B ela inicia com @ + texto + @
- [x] Lemos assim: `@ + (nome + " " + a(sobrenome)) + @`

> Ficaria: @ + Flávio + "espaço" = @Flávio  
<br>

- [x] Depois ela retorna para a função A em `a (sobrenome)`
- [x] Na função A temos: "(" + texto + ")"  = (sobrenome)
- [x] Lemos assim: (Almeida)

> Até agora temos: @ + Flávio + "espaço" + "(" + Almeida + ")" = @Flávio (Almeida)

- [x] Com isso, encerramos a função A e temos que retornar para a função B, o final da função B é o @

> Temos o resulado: @ + Flávio + "espaço" + "(" + Almeida + ")" + @ = @Flávio (Almeida)@

Resultado:

@Flávio (Almeida)@

______________

### Atividade: 06_01_futebol.html

Inclundo `parseInt()`, neste caso, a string de `prompt` se tornará em um número, desde que, seja informado um número.

![image](https://user-images.githubusercontent.com/108991648/183304865-c9f0500e-d6ac-47e0-9d4b-e07523d2dda8.png) Usuário informa um número = 10, 15, 155, 209 ...
![image](https://user-images.githubusercontent.com/108991648/183304895-cea0b666-23c8-4ef2-825f-b21a190ccc3a.png)  Usuário informa uma palavra = chuva, sol, copo... **(Ocorre erro: NaN)**

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {

        document.write("<br><br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

var vitorias = parseInt(prompt("Quais são as vitórias?"));
var empates = parseInt(prompt("Quantos são os empates?"));

var pontos = vitorias * 3 + empates;

mostra("Os pontos do seu time:" + pontos);
</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/183223378-7a99cb7f-d231-4ff5-bc71-09694238ff38.png)
___________

### Atividade 06_07_interagindo_com_usuario2.html

Nesta atividade, incluímos o `if (se algo for <, = ou > a outro) {imprima("tal item")}`


- [x] `&&` siginifica "e" 
- [x] Note que a variável foi chamada após o `&&`
- [x] O texto a ser impresso deve estar dentro do bloco **{ }**

```html
if(imcCerto >= 18.5 && imcCerto <= 35) {
    mostra("Legal! Seu IMC é excelente!");
}
```

```html
<meta cherset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br><br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    function calculaImc(altura, peso) {

        return peso / (altura * altura);
    }

var nome = prompt("Qual é o seu nome?");
var alturaInformada = prompt(nome + ", informe sua altura");
var pesoInformado = prompt(nome + ", informe seu peso");

var imc = calculaImc(alturaInformada, pesoInformado);
var imcCerto = Math.round(imc)

mostra(nome + ", o seu IMC é: " + imcCerto);

if(imcCerto < 18.5) {
    mostra("Cuidado! Seu IMC está abaixo do recomendado!");
}

if(imcCerto >= 18.5 && imcCerto <= 35) {
    mostra("Legal! Seu IMC é excelente!");
}

if (imcCerto >35) {
    mostra("Cuidado! Seu IMC está acima do recomendado!");
}


</script>
```

Resultado:

* 1º foram chamados 3 alertas: nome, altura e peso.

![image](https://user-images.githubusercontent.com/108991648/183309322-b760c9fe-a916-49b9-80bb-e8dfc784adc9.png)

________________

### Atividade 06_08_jogo_de_adivinhacao.html

Nesta atividade, fizemos um jogo de adivinhação.

- [x] A condição `if == se` recebe o resultado de uma operação dentro dos **( )**
- [x] Dentro do bloco **{ }** que informamos o que deve ser escrito na tela do usuário
- [x] A condição `else == se não` também tem seu parâmetro dentro de um bloco **{ }**

```
if(numero == chute){
    mostra("Você acertou! Também pensei no " + numero);
} else {
    mostra("Ih! Não foi dessa vez! O número que pensei foi " + numero)
}
```



```html
<meta cherset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br><br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

var numero = Math.round(Math.random() * 5);
var chute = parseInt(prompt("Tente adivinhar em qual número estou pensando..."))

if(numero == chute){
    mostra("Você acertou! Também pensei no " + numero);
} else {
    mostra("Ih! Não foi dessa vez! O número que pensei foi " + numero)
}

</script>
```

____________

### Atividade 06_11_onde_esta_o_erro_de_braga.html

Esta atividade, de acordo com a resposta do usuário, deve exibir a mensagem "Pode dirigir" ou "Não pode dirigir".

- [x] Permitido dirigir acima dos 18 anos ou mais;
- [x] E que possua carteira de motorista.

Código inicial:

```html
<meta charset="UTF-8">

<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    var idade = parseInt(prompt("Qual é sua idade?"));
    var temCarteira = prompt("Tem carteira? Responda S ou N");

</script>
```

Código adicionado, antes de `</script>`
```html
if (idade >= 18 && temCarteira == "S"){
        mostra("Pode dirigir!");
    }else {
        mostra("Não pode dirigir!");
    }
```
____

### Atividade: 06_13_jogo_adivinha.html

- [x] Criar função sorteia

1. Você pode criar uma função sorteia que recebe um número n e sorteia um número entre 0 a n, retornando esse valor. Dessa forma, em vez de escrever `var numeroPensado = Math.round(Math.random() * n);`, você escreveria `var numeroPensado = sorteia(n);`. Faça essa modificação, criando a nova função e utilize-a.

2. Faça com que seu jogo mostre, quando o usuário errar a tentativa, se o número que ele chutou era maior ou menor ao número pensado pelo programa

Meu código:
```html
<meta charset="UTF-8">
<script>

    function pulaLinha() {

        document.write("<br>");
    }

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
    }

    function sorteia() {
        var dados = Math.round(Math.random() * 10   );
        return dados
    }

var numeroPensado = sorteia();

var chute = parseInt(prompt("Já pensei. Qual você acha que é?"));

    if(chute == numeroPensado) {

        mostra("Uau! Você acertou, pois eu pensei no " + numeroPensado);
    
    } else {
        if (chute < numeroPensado){
            mostra("Você errou! O número que pensei foi " + numeroPensado + ". Seu número " + chute + " é menor que " + numeroPensado);
        } else { 
            mostra("Você errou! O número que pensei foi " + numeroPensado + ". Seu número " + chute + " é maio que " + numeroPensado);
        }
    }

</script>
```

Código do instrutor:

```html
<meta charset="UTF-8">
<script>

    function pulaLinha() {

        document.write("<br>");
    }

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
    }

    function sorteia(n) {

        return Math.round(Math.random() * n);
    }    

    var numeroPensado = sorteia(10);


     var chute = parseInt(prompt("Já pensei. Qual você acha que é?"));

    if(chute == numeroPensado) {

        mostra("Uau! Você acertou, pois eu pensei no " + numeroPensado);
    } else {

        if(chute > numeroPensado) {

            mostra("Você errou! Seu chute é maior que o número pensado!");

        } else {

            mostra("Você errou! Seu chute é menor que o número pensado!");
        }

    }
</script>
```

_______

### Atividade: 07_01_ano_copa.html

```html
<meta charset="UTF-8">
<script>

    function pulaLinha() {

        document.write("<br>");
    }

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
    }

    var limite = parseInt(prompt("Pesquisa: `Quais anos são bissextos?`. Escolha uma data limite: "));

    var anoCopa = 1930;

    while(anoCopa <= limite) {
        mostra("Teve copa em: " + anoCopa);
        anoCopa = anoCopa + 4;
    }

    mostra("FIM");

</script>
```

Resultado:

Alerta + resposta usuário +

![image](https://user-images.githubusercontent.com/108991648/184470237-d4fcc7e1-401a-4d96-9324-c8f7c9aa9be7.png)

__________________

### Atividade: 07_04_numeros_30_40.html

Imprimir os números de 30 até 40, porém, não mostrar 33 e 37.


```html
<meta charset="UTF-8">
<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    var contador = 20;

    while(contador <= 40) {

        if( contador == 33 ) {
        contador = contador + 1;
        }
        else if(contador == 37) {    
            contador = contador + 1;
        }
        else {
        mostra(contador);
        contador = contador + 1; 
        }
      }

    mostra("FIM");

</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/184537269-cf544f40-98c1-47f3-83f1-70219c660b8b.png)

__________

### Atividade: 07_05_numeros_20_0.html

Imprimir os números de 20 até 0.

```html
<meta charset="UTF-8">
<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
        pulaLinha();
    }

    var contador = 20;

    while(contador >= 0) {
        mostra(contador);
        contador = contador - 1; 
        }
      

    mostra("FIM");

</script>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/184537461-f9154402-bba9-4062-b64a-d16ba8d65799.png)

_________

Atividade: 07_06_copa_data_limite.html

Exibir mensagem final: ""Ufa! Esses foram os anos de copa até"

```html
<meta charset="UTF-8">

<script>

    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
    }

var anoCopa = 1930;
var limite = parseInt(prompt("Qual é o ano limite?"));

    while(anoCopa <= limite) {

        mostra(anoCopa + " tem copa!");
        anoCopa = anoCopa + 4;
    }

mostra("<br>" + "Ufa! Esses foram os anos de copa até " + limite);

</script>
```
Resultado: 

![image](https://user-images.githubusercontent.com/108991648/184724977-ab93517a-db0e-41e7-be15-3b32131e4ccf.png)

__________

### Atividade: 07_07_simulando_tela_login.html

O usuário vai incluir o login e senha, após 1 tentativa o programa não funciona mais. Passe o exercício para 3 tentativas. 

> Atenção: Se ele acerta na primeira tentativa, não faz sentido continuar a perguntar seu login e senha.

```html
<meta charset="UTF-8">

<script>

    var loginCadastrado = "alura";
    var senhaCadastrada = "alura321";

    var maximoTentativas = 3;
    var tentativaAtual = 1;

    while(tentativaAtual <= maximoTentativas) {

        var loginInformado = prompt("Informe seu login");
        var senhaInformada = prompt("Informe sua senha");

        if( loginCadastrado == loginInformado && senhaCadastrada == senhaInformada ) {

            alert("Bem-vindo ao sistema, " + loginInformado);

            tentativaAtual = maximoTentativas; // acertou, então faço o gasto de todas as tentativas para sair do loop. Lá embaixo vai incrementar + 1! 

        } else {

            if (tentativaAtual == 3) {
                alert("Número permitido de tentativas ultrapassado!");
            } else {
                alert("Login inválido. Tente novamente");
            }
        }

       // vai para a próxima tentativa, 
       // tentativaAtual = tentativaAtual++
        tentativaAtual = tentativaAtual +1  
    }

</script>
```

<hr>

### Atividade: 07_08_tabuada_while_and_for.html

FOR:

```javascript
for(var multiplicador = 1; multiplicador <= 10; multiplicador++) {

    mostra(7 * multiplicador);

}

mostra("FIM");
```

WHILE:

```javascript
var multiplicador = 1;

while(multiplicador <= 10) {

    mostra(7 * multiplicador);
    multiplicador = multiplicador + 1
}

mostra("FIM");
```

________________________

### Atividade: 07_11_de_for_para_while.html

Faça de For para While

FOR
```javascript

for( var i = 0; i < 10; i++ ) {
    alert( "O resultado é " + (2 * i) );
}

```

WHILE

```javascript
var i = 1;

while(i <=10) {

    alert("O resultado é " + (2 * i))
    i = i + 1
}

mostra("FIM");
```

OU 

```javascript
var i = 0;
while( i < 10) {
    alert( "O resultado é " + (2 * i) );
    i++;    
}
```

<hr>

### Atividade: 07_12_media_idade_familiares.html

Faça um programa:

- [x] Leia a quantidade de familiares que o usuário desejar;
- [x] Some todos os valores
- [x] Faça a média

```javascript
<meta charset="UTF-8">

<script>

    function pulaLinha() {

        document.write("<br><br>");
    }

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
    }

// Quantidade de familiares
var totalPessoas = parseInt(prompt("Qual é a quantidade de pessoas?"));

var numero = 1 

// Esta var fora de while par poder somar!
var totalIdades = 0

while(numero <= totalPessoas) {
    var idade = parseInt(prompt("Informe a idade: "));
    totalIdades = totalIdades + idade;
    numero++;
}

mostra("O total das idades é de: " + totalIdades);

var mediaIdades = totalIdades/totalPessoas

mostra("A média das idades é de: " + mediaIdades);


mostra("Fim!")

</script>
```

Resultado:

O total das idades é de: 60

A média das idades é de: 20

Fim!

<hr>

### Atividade: 07_15_jogo_adivinha.html

Fornecer ao usuário 3 tentativas para descobrir o número.

```javascript
<meta charset="UTF-8">

<script>

    function pulaLinha() {

        document.write("<br><br>");
    }

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
}

var numeroPensado = Math.round(Math.random() * 10);

var tentativas = 1;

while(tentativas <= 3) {

    var chute = parseInt(prompt("Você tem 3 chances, adivinhe o número que estou pensando... Dica: 0 até 10"));

    if(chute == numeroPensado) {

        mostra("Você ACERTOU, o número pensado era " + numeroPensado);
        break;

    } else {

        mostra("Você ERROU! O numero pensado era:  " + numeroPensado);
    }

    tentativas++;
}

mostra("FIM");
</script>
```

<hr>

### Atividade: 07_17_estrelas.html

Criar 3 linhas com 10 ("*")

```javascript
<meta charset="UTF-8">

<script>

    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
    }

    for(var linha = 1; linha <=3; linha++) {
        for(var coluna = 1; coluna <= 10; coluna++) {
            document.write("*");
        }
        pulaLinha();
    }

</script>
```

<hr>

### Atividade: 08_01_adivinha_mais.html

- [x] `<input/>` tag NÂO possui fechamento, cria uma lacuna de preenchimento

- [x] `<button>` tag POSSUI fechamento, cria um botão, texto sem **" "** 

- [x] `input.value` compara com a lacuna input criada

- [x] `button.onclick()` compara ao clicar no botão criado

- [x] `input.focus();` o cursos do mouse retorna para a lacuna criada pelo input/  


```html
<meta charset="UTF-8">

<input/>

<button>Compare com o meu segredo</button>

<script>
    var segredo = 2;

    var input = document.querySelector("input");

    function verifica(){
       if(input.value == segredo) {
        alert("Acesso liberado!")

    } else {
        alert("Acesso negado!! Erro de segredo!!");
    } 
    input.value = " ";
    input.focus();
    }
    
    var button = document.querySelector("button");
    button.onclick = verifica;
```

<hr>

### Atividade 09_01_adivinha_mais_atualizado.html

Neste exercícios vamos ver sobre array [l, i, s, t, a, s]

- [x] `var segredos = [5, 7, 10, 2];` uma array, lista
- Arrys iniciam sua contagem a partir do 0, no exemplo acima temos:
   * 1º item: posição 0 == 5;
   * 2º item: posição 1 == 7;
   * 3º item: posição 2 == 10;
   * 4º item: posição 3 == 2
- [x] `segredos.length` retorna a quantidade de elementos que uma array possui

```html
<meta charset="UTF-8">

<input/>

<button>Compare com o meu segredo</button>

<script>

    var segredos = [5, 7, 10, 2];

    var input = document.querySelector("input");
    input.focus();
    
    function verifica(){
       var achou = false;

       for(var posicao = 0; posicao < segredos.length; posicao++){
        if(input.value == segredos[posicao]) {
            alert("Acesso liberado!")
            achou = true;
            break;
        }
               
    } 
    
    alert("Acesso negado!! Erro de segredo!!");
    
    input.value = "";
     
    }
    
    var button = document.querySelector("button");
    button.onclick = verifica;

</script>
```
<hr>

