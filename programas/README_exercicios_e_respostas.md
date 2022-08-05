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
2. 
