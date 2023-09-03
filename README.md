# TAILWINDCSS

<div align="center">

![The Good and Bad About TailWind](https://onedrive.live.com/embed?resid=F3F3AE118D1DE0A%2158654&authkey=%21AP14BVJy7l00CUY&width=660 'The Good and Bad About TailWind')

</div>

Important Links:
[https://tailwindcss.com/docs/flex-direction](Tailwind CSS Documentation)
[https://tailwindcss.com/docs/customizing-colors](Colors in Tailwind CSS)

- Classes utilitárias: representam as propriedades do CSS (no Bootstrap as classes representam um componente pronto e caso queira customizar algo, será necessário reescrever a classe ou criar uma nova). Uma das grandes vantagens do Tailwind, é que não precisamos seguir um padrão visual pré definido pelo framework. As classes de utilidades do Tailwind permitem um maior controle na estilização da página, pois há uma alta variedade de classes, o que torna o layout mais personalizado.

### Preflight

O Tailwind, ele vai ter como padrão um recurso que se chama preflight, o preflight ele vai trabalhar muito parecido como um reset CSS, um normalize CSS, ou seja, o seu objetivo, vai ser diminuir as discrepâncias entre os navegadores, as inconsistências entre esses navegadores.

O Preflight foi construído com base no modern-normalize, é um conjunto de estilos básicos que atuam com o intuito de reduzir as inconsistências entre navegadores, visto que cada um define seu próprio conjunto padrão de propriedades CSS que são aplicadas aos elementos HTML. 

**Quais estilos são redefinidos:**

- Remove os estilos dos cabeçalhos (h1 até h6), como a margem, peso e tamanho de fonte, o tornando idêntico ao texto base.
- Remove o estilo das listas ul e ol, resultando em nenhum número ou marcador por padrão. Caso queira estilizar uma lista, pode fazê-lo usando os utilitários list-style-type e list-style-position.
- Define todas as margens como zero para elementos que normalmente teriam margens por padrão.
- Todas as tags referentes a imagem se tornam elementos em nível de bloco ao invés de linha, assumindo o display: block por padrão.
- Define todas as bordas para uma largura de 0 pixel, sólida e a cor da borda definida por padrão.
