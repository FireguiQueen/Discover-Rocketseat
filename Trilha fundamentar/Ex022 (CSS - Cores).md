# Cores
Usamos do CSS para alterar cores do nosso documento.


## Tipos 
* background-color (cor do fundo das caixas)
* color (cor dos textos)
* border-color (corda da borda)

## Valores
* Podemos definir o valor por: 
```go
- palavra chave // transparent..
- nome da cor // red, blue.. 
- hexadecimal (#00 00 00 ) // #red green blue)
- funções: rgb, rgb, hsl, hsla
```


```css
element{ 
    // Keyword
    color: currentcolor; 
    color: transparent; 


    // Named-color 
    color: red;
    color: blue; 


    // Hex-color      (RED - GREEN - BLUE)
    color: #090;      /* Verde, pois é 0 para a cor vermelha, 9 para verde e 0 para azul.                      */ 
    color: #009900;   /* Verde novamente, porém, com esta quantidade de números, podemos alterar mais a cor    */ 
    color: #090f;     /* Verde transparente. Quando vemos uma letra, estamos trabalhando com a transparência   */
    color: #009900aa; /* Podemos alterar mais ainda a cor e sua transparência                                  */ 

    /* Para mudarmos a cor, temos "0" até "9"  &  para a transparência (opacidade), temos de "a" até "f"
    Sendo "a" pouca transparência, e conforme subimos a letra, deixamos mais transparente. */ 
    color: #990000aa; 
    color: #990000dd; 
    color: #990000ff; 
    /* Caso você utilize da maneira mais extensa (#00 00 00), será necessário colocar a letra alfabética duas vezes. 
    Cada vez que subimos o número de cada cor, mais forte ela fica, então mesmo haja 10 para o vermelho, a cor final 
    não será vermelha, e sim um verde alterado, pois o número da cor verde está mais forte. */ 
    color: #109900; 


    // Rgb(000, 000, 000, 0.2)              
    color: rgb(200, 00, 00, 0.7); 
    /*  RGB significa: Red - Green - Blue                               */    
    /*  O RGB vai de 0 até 225, ou seja, do mais escuro ao mais claro   */ 
    /*  "0.5" seria o nível da transparência                            */    

}