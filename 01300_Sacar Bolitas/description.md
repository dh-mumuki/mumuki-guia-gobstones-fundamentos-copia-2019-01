De la misma forma que uno puede dar el comando de "poner bolita" (`Poner`), tenemos una forma de "sacar bolita" (`Sacar`), que quita exactamente una bolita del color dado.

Por ejemplo, el siguiente programa saca dos bolitas de color Rojo de la posición inicial.

```gobstones
program {
  Sacar(Rojo)
  Sacar(Rojo)
}
```

> Sabiendo esto, escribí un programa que elimine **sólo** la bolita roja de este tablero. **¡Tené cuidado!** Prestá atención a la posición del cabezal :wink:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>