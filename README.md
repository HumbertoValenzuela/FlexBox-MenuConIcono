# FlexBox-MenuConIcono
* FlexBox Menú Sencillo y un Menú con icono info

```javascript
/* Iconos */
div .texto span {
    font-size: 0.5rem;
    display: block;
    margin-top: 0.5rem;
}

.iconos__ul li a {
    display: flex; 
    justify-content: center;
}

.icono {
    flex: 0 1 2rem;
}
@media screen and (min-width:480px){
    .iconos__ul {
        display: flex;
        flex-wrap: wrap;
    }
    .iconos__ul li {
       flex: 0 1 50%;
    } 
}

@media screen and (min-width:768px) {
    .iconos__ul li {
        flex: 1;         
        /*flex-grow:1; toma mismo espacio*/
    } 
}
```
