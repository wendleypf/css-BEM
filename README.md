## css - BEM

A sigla **BEM** significa Block Element Modifier,
ou **Bloco Elemento Modificador**.

O **BEM** é uma metodologia aplicada no CSS, onde aplicamos uma nomenclatura específica as classes
para que o código CSS fique mais legível.

**BLOCK:** o elemento pai será o bloco.
````html
<section class="card">
    
</section>
````

**ELEMENT:** cada um dos elementos filhos desse bloco
são identificados com dois underlines (__)
após o nome da classe BLOCK.

````html
<section class="card">
    <a href="#" class="card__link">Comprar</a>
</section>
````
**MODIFIER:** Um modificador é identificado por dois traços (--) após um BLOCK ou ELEMENT. Ele faz modificações que podem ser reutilizadas, por exemplo, um link rosa que possui uma variação maior na cor turquesa.
````html
<section class="card">
    <a href="#" class="card__link">Comprar</a>
    <a href="#" class="card__link--highlight">Compre já</a>
</section>
````