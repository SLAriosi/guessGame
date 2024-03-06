## Event-driven

==>> A DOM é direcionada a eventos ||--> Event-driven <--||. Significa que ela poderá reagir a qualquer tipo de evento relacionado à página.

# Podemos entender em 2 fases

==>> A ocorrência do evento e reação à ocorrência


# 1.Eventos

==>> Ações que acontecem na página, site ou aplicação

|->> Carregamento do documento, aparição de elementos na tela.

|->> Modificação de propriedades da página (largura, altura, scroll)

|->> Cliques de mouse e digitação do teclado

|->> Interação com sons, imagens, vídeos

|> Além de outras coisas.

# 2.Reações

==>> O sistema poderá executar reações às ações. Executar uma função sempre que determinada ação acontecer.

## Exemplos

|> Ao clicar em um botão, apresenta em tela um elemento que estava escondido.

> const button = document.querySelector('button')

===> Vamos registrar o evento na nossa aplicação

|->> button.addEventListener('click', function(e) {
    console.log(e) |-> objeto contendo tudo sobre o evento
   document.querySelector('p').style.display = "block"
})

|-> addEventListener recebe 2 argumentos
|-> O primeiro é uma string com nome do evento
|-> Depois, uma função callback
|-> que irá executar um código em reação ao evento
