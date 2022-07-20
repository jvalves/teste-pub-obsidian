---
title: "Autenticando no Github"
---

# Autenticando no Github

Antes de começar, certifique-se que você possua o **GitBash** ou algum terminal que permita escrever em Bash e usar os comandos do Git. Se não tiver, realize o download de acordo com [esse guia](https://www.canva.com/design/DAFBPzOHcMQ/view).

Tudo pronto? Vamos lá!

1. Faça o Login no Github clicando **[aqui](https://github.com/login)**;
2. Na página principal, clique no ícone da sua foto, que fica no canto superior direito onde está sua foto (opção _view profile and more_), e selecione a opção **Settings**;

![[github (2).png]]


3. Na tela de settings, vá descendo entre as opções do lado esquerdo, e selecione **Developer Settings**

![[New Project.png]]


4. Em seguida, clique na opção **Personal access tokens**, e na lista que aparecerá ao lado, selecione **Generate new token**. Ao fazer isso, é possível que peçam novamente sua senha. Digite a senha normalmente e podemos prosseguir.
   
![[New Project (1).png]]


5. Defina as configurações do novo Token. As configurações que precisam ser definidas são: Nome do Token, Duração do token (aqui sugerimos 365 dias, que pode ser definido escolhendo a opção _Custom_), e suas permissões. Para o que vamos fazer aqui na Labenu, basta preencher as opções que estão em **repo**. 

![[config token.png]]

6. **Copie o token gerado.** Ele não vai aparecer de novo para você!

![[tela de token.png]]

7. Pronto, pode seguir para os passos dos exercícios e quando for dar o primeiro `git push`, insira esse **token** no lugar onde for requisitada a sua **senha**!