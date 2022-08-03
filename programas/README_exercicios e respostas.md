# Curso: Lógica de Programação

## Lista de exercícios e respostas

### Atividade: 01_01_primeiro_teste.html

No primeiro teste, aprendemos:
- [x] Incluir título `<h1> </h1>`
- [x] Pular linha `<br>`
- [x] Incluir link `<a href="link">aqui</a>!`
- [x] Chamar e fechar linguagem JavaScript `<script> </script>` 
- [x] Chamar um popup `alert`

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

Código altedado, com a inclusão de `var n = 1`

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

Melhorando o programa

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

__________

