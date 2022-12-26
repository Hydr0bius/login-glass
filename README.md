# Login glass

login semitransparente. Se hizo uso de *linear-gradient* en el body para la mezcla de un verde y amarillo:

```CSS
body{
background: linear-gradient(to right, #04db15, #d6da0c);
}
```
Así como uso de *before* en la parte del *login-card* para generar uno igual con una rotación de -5 grados y que este se posicione -1 de la posición Z:
```CSS
.login-card::before{
    content: '';
    position: absolute;
    background: rgba(255, 255, 255, 0.15);
    inset: 0;
    transform: rotate(-5deg);
    z-index: -1;
}
```


[Link](https://hydr0bius.github.io/login-glass/) de la página
![login](image/login.png)
