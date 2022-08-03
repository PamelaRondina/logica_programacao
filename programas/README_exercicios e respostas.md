**Atividade: 01_primeiro_teste.html**

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

**Atividade: calculando_gastos.html**

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

**Atividade: document_write.html**

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
**Atividade: prova.html**

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



