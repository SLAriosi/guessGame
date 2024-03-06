## Element e Node
* ---

As tags HTML, quando usadas pela DOM, podem chamar de 
> node (nó)
Ou de 
> element (elemento)

...
> Pegando um elemento
const __h1__ = __document__.querySelector('h1') 
<!-- HTMLElement -->


> Pegando vários elementos
const __links__ = __document__.querySelectorAll('a')
<!-- Nodelsit -->
...

## Recebendo e modificando valores

> Podemos pegar qualquer valor das tags e, também, alterar eles.

> innerText
> console.log(h1.innerText)

> innerHTML
> console.log(h1.innerHTML)

> alterando o texto (ou o HTML)
> h1.innerText = "Novo título"

## Alterando estilos

> Podemos alterar estilos ou adicionar classes em elementos.

> alterando o estilo
|---> h1.style.backgroundColor = "red"

> adicionando classes
|---> h1.classList.add('hide')

> removendo classes
|---> h1.classList.remove('hide')

> alternando 
|---> h1.classList.toggle('hide')