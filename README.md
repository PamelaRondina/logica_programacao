# Lógica de Programação

**Exercícios e Resultados [Aqui](https://github.com/PamelaRondina/logica_programacao/blob/main/programas/README_exercicios_e_respostas.md)**

**Regras da Convenção**

Conforme a convenção devemos:
- [x] Salvar arquivos `desta_forma.html`
- [x] **< >** são tags, são feitas em letras minúsculas
- [x] As tags são abertas e fechadas com **/**, `<h1>` e `</h1>`
- [x] Em JavaScript tudo em minúsculo
- [x] Variáveis são salvas:
   * 1 palavra: `assim`
   * 2 ou mais: `destaForma` ou `destaFormaAqui`

> O sistema até reconhece a tag sendo digitada em letra MAIÚSCULA, mas o correto é digitar em minúscula. 

**Incluir título**
* Dentro de HTML:
- [x] `<h1>`  início título
- [x] `</h1>` final título
 
```html
<h1>Aqui será o título!</h1>
```

* Dentro de JS com HTML

- [x] `document.write` dentro de JS escrever em HTML
- [x] `("<h1>Título</h1>")` em HTMl dentro de JS, nas **(" ")**

```html
<script>
    document.write("<h1>Título</h1>");
</script>
```

 **Incluir link**
- [x] `<a>` início âncora
- [x] `href="texto"` atributo para incluir o link, dentro da 1ª âncora
- [x] palavra **aqui**, cliclando levará para outro site
- [x] `</a>` final âncora
 
 `<a>aqui</a>!`
`<a href="http://www.site.com.br">aqui</a>`

 ```html
 Visitando o site <a href="http://www.site.com.br">aqui</a>!
 ```

**Depurador (*debugger*)**

- [x] Apertar **F12** no teclado
- [x] Ir em *Console*
- [x] Mensagens de erro estarão em vermelho

![image](https://user-images.githubusercontent.com/108991648/182258030-576ee244-b907-44cf-885f-8fd637cfaca4.png)

**Mundos**
- [x] `<script>` início JavaScript
- [x] Aqui vamos escrever os códigos dinâmicos
- [x] `</script>` final JavaScript
- [x] `document.write` dentro de JS escrever em HTML
- [x] `("<h1>Título</h1>")` em HTMl dentro de JS, nas **(" ")**

```html
<script>
    document.write("parâmetro 1");
    document.write(18);
    document.write("<h1>Título</h1>");
</script>
```
> textos são em **(" ")** e números apenas em **( )**

Se tivermos:

* string + string = string
   * ("10") + ("2") = 102
<br>
* número + número = número
   * (10) + (2) = 12
<br>
* string + número = string
   * ("10") + (2) = 102
<br>
* strings + números = string
   * ("A" + "B" + 20 + 10 + "C" + (5 + 10) + "D") = AB2010C15D

> strings: ou textos, estarão em **" "**

**Criar alertas**

- [x] `meta charset="UTF-8"` código para o programa aceitar acentuações
- [x] `<script>` iniciar a linguagem JavaScript dentro do Html
- [x] `alert` criar um popup
- [x] `("parâmetro")` deve estar entre **( )** e **" "**
- [x] **;** *sempre* encerrar a linha com ;   
- [x] `</script>` finalizar a linguagem JavaScript 

```JavaScript
<meta charset="UTF-8">

<script>
alert("Este é um popup feito com JavaScript");
</script>
```

**Variável**

- [x] `var`declarada apenas pela 1ª vez
- [x] `var =` var recebe

```html
<meta charset="UTF-8">

<script>
    var n = 1;
    document.write("O resultado da fórmula é : " + n * (10 / 20));

    n = 2
    document.write("O resultado da fórmula é : " + n * (10 / 20));
</script>
```

**Usando funções Matemáticas**

Para arredondar um resultado:

- [x] `Math.round()` - dentro das **( )** incluir um valor ou uma variável. O resultado será arredondado.

Resultado de 33,33 vai para 33.

**Criando um nova função**

> Assim como a variável, a função deve ser inclusa no início do programa!

- [x] `function` apresentar uma nova função
- [x] `pulaLinha()` nome da função e com **( )**
- [x] `{ }` dentro das **{ }** 
- [x] `document.write` indentado e incluir o que essa função fará, dentro das **{ }** 
- [x] Para executar esta função inserir `pulaLinha();`. 
- [x] Os **( )** são obrigatórios para chamar a função!

```JavaScript
<script>

function pulaLinha() {

    document.write("<br>");

}

</script>
```

**Função com 1 (um) parâmetro**
- [x] Repete os passos do item anterior
- Dentro das **( )** da função ganha um parâmetro
- [x] O mesmo parâmetro se repete dentro das **( )** de `document.write(aqui)`
- [x] As funções podem ser inclusas dentro de outras funções

```JavaScript
<script>

function mostra(frase) {

    document.write(frase);
    pulaLinha();

}

</script>
```

**Função com 2 (dois) parâmetros**
- [x] Dentro das **( )** da função ganha dois parâmetros, são separados por **,**
- [x] O mesmo parâmetro se repete na variável criada

```JavaScript
<script>

function calculaImc(altura, peso) {

    var imc = peso / (altura * altura);
    mostra("O imc calculado é: " + imc);
    
}

calculaImc(1.71, 73);
calculaImc(1.72, 68);

</script>
```

____

Comandos: Html | Descrição
:-|:-
< > | São tags
< / > | Fechar uma tag
< a > | Âncora
< br > | Pular linha
< h1 > | Título
< b > | Negrito
< hr > | Risco 
< big > | Aumenta o tamanho da letra
< h1 align="center" > | Título 1 + centralizado
------ |  -------
href = | Atributo
------ |  -------
Ctrl+S | Salvar
Ctrl+R | Atualizar Página
Ctrl+O | Abrir arquivo no navegador
F12 + Console | Para localizar um problema no código
------ |  -------
< meta charset = "UTF-8"> | Utilizar no navegador para acentuação
**Comandos: JavaScript** | **Descrição**
// | Comentário
= | Recebe
== | Igual
!= | Diferente
&& | E
{ } | Bloco
< script > | Iniciar linguagem JavaScript
var | variável
**Funções**| ---------
alert("texto") | Cria um *pop up* de alerta
prompt("texto") | Pop up para o usuário inserir um resultado, retorna o resultado como string
parseInt("texto")| Converte uma string para número
if("texto") { "texto" } | Se 
else | Se não
while | Enquanto
Math.round() | arredondar o resultado
Math.random() | Número aleatório
console.log() | Resultado aparece no console do Browser
**Erros**| ----------
NaN | Não é um número