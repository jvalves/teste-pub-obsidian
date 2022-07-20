oobsi# Usando o Devtools

# O que é o Devtools

As _devtools_ (ferramentas de dev), são um conjunto de ferramentas construídas direto no navegador de internet (como o Chrome ou o Firefox). As devtools podem nos ajudar a editar as páginas enquanto elas estão sendo exibidas, e diagnosticar problemas rapidamente, o que, em última instância, nos ajuda a construir sites melhores, mais rápido. No nosso caso, vamos usar o **Google Chrome.**

## Abrindo o DevTools

Existem muitas formas de se abrir as DevTools, porque situações diferentes requerem acesso rápido a partes diferentes de sua interface.

-   Quando queremos trabalhar com a DOM, ou o CSS, é só clicar com o botão direito em um elemento da página e escolher “Inspecionar elemento”. Assim, cairemos na aba de **Elementos**. Ou, aperte Cmd+Option+C (no Mac) ou Ctrl+Shift+C (no Windows e Linux);
-   Quando queremos ver mensagens **log**, ou rodar JavaScript, basta apertar Cmd+Option+J (no Mac), ou Ctrl+Shift+J, para ir direto para o painel de **Console**

Guia de Elementos

Quando você quiser olhar para algum elemento específico da página para ver seu nome, estilos e atributos, clique no elemento com o botão direito e selecione **Inspecionar**

![[Pasted image 20220712144855.png]]

Ou aperte Cmd+Option+C (no Mac) ou Ctrl+Shift+C (no Windows e Linux);

<aside> 💡 Em breve vídeo aqui sobre a parte de elementos

</aside>

# Guia de Console

Web developers often log messages to the Console to make sure that their JavaScript is working as expected. To log a message, you insert an expression like `console.log('Hello, Console!')` into your JavaScript. When the browser executes your JavaScript and sees an expression like that, it knows that it's supposed to log the message to the Console. For example, suppose that you're in the process of writing the HTML and JavaScript for a page:

Devs frequentemente usam mensagens no **console** para ter certeza de que o código está funcionando como devia. Para colocar uma mensagem no console, você pode inserir uma expressão como `console.log("Hey, Mundo!")` no seu código JavaScript. Quando o navegador executar seu código e encontrar esta expressão, vai saber que deve mostrar a mensagem no console. Por exemplo, suponha que você escreveu o código de HTML e JavaScript abaixo:

```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>
<h1>Hey, Mundo!</h1>
    <script>
      console.log('Carregando...');
      console.log('Hey, Console!');
    </script>
</body>
</html>
```

A imagem abaixo mostra como esse código seria carregado no navegador.

Do lado esquerdo temos a página carregada. Do lado direito, temos as mensagens sendo exibidas no console.

![[Pasted image 20220712144922.png]]

Em linhas gerais, devs utilizam o console para duas funcões principais:

-   Verificar se o código está sendo executado na ordem certa
-   Inspecionar valores de variáveis em dado momento da execução do código.

É através do console que vamos ver o que praticamos no JavaScript nas próximas aulas!