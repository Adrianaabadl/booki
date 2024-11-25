# Booki

## Dudas 

1. De la barra <nav> tengo que pegar a la esquina, intente quitando margenes pero no me salio, lo otro es, al hacer hover, debe ponerse ese border-top ?


```css
  header .accommodation {
    /* border-top: #0065fc solid 2px;  */
    padding: 5px;
    color: none;
  }
```
For next session, no margin on the base, then, next ones, will have some margin on the body.

On the mobile no margin! thats your base remember

So I dont have margins in the individuals components, cause the margin is already in the body. 

Work on the versions of the figma


## Git issues

```bash
ssh -T git@github.com
cat ~/.ssh/id_ed25519.pub
```



## Dudas (8/11/2024)

No estoy segura de si es la correcta forma
```css
  .search-bar .map {
    display: flex;
    width: 100%; 
    justify-content: center;
  }
```
Para el desktop, max with y anadir la sombra/shadow

Para la separacion del texto:
```css
  .popular-section .title-popular {
    margin: 15px 0 0 15px;  /* margin-top: 15px; margin-left: 15px; */
  }
``` 


Mover las estrellas al final
```css
  .popular-section .title-popular {
    margin: 15px 0 0 15px; 
  }
  
  .popular-section .star {
    margin-top: 65px;
  }
```
Considerando hacerlo flex y tratar de mover los items




Quitar esta media query y pasarla a mi mobile first
```css
  .accommodation-section .bloc1 {
    flex-direction: column;
    width: 100%;
  }
  .accommodation-section span{
    margin-left: 10px;
  }
  .accommodation-section{
    flex: none;
    width: 90%;
    margin-right: 0%;
    padding: 5%;
    height: auto;
    background-color: white
  }
  .accommodation-section h2 {
    margin: 25px 0;
  }
  .accommodation-section .border-picture{
    width: 95%;
    margin-bottom: 20px;
  }
  .accommodation-section img{
    object-fit: cover;
    height: 180px;
  }
  .accommodation-section .border-popular{
    width: 100%;
  }
  
  .accommodation-section .bloc2 {
    justify-content: start;
}
```