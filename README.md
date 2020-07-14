# CSS - Grid Terminado
Genial acabe CSS Grid y hice una practica solo abre en el navegador el archivo HTML junto con
el CSS
```CSS
.contenedor{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: 100px repeat(4, 1fr) 100px;
    grid-gap: 10px;
    grid-template-areas: "header header header"
                         "conten conten aside"
                         "conten conten aside"
                         "conten conten aside"
                         "widUno widDos aside"
                         "footer footer footer";
    grid-auto-flow: row dense;
    grid-auto-row: 100px;
}

```
> Estas solo son algunas propiedades de las muchas que tenemos