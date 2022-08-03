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

![image](https://user-images.githubusercontent.com/108991648/182506065-53f4b259-6ede-481a-b66e-e939b6a1cfbd.png)
______________________

**Atividade: document_write.html**
Temos dois usuários:
- [x] O primeiro, para pular uma linha utilizou `document.write("<br>")`
- [x] O segundo, apenas incluir `+ "<br>"` 

> Ambos dão o mesmo resultado, a programadora decide sua melhor versão!

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

![image](https://user-images.githubusercontent.com/108991648/182507707-b9d2c164-47d6-4607-b1f1-a8fc4169a66b.png)

________________


