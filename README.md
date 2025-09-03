# 0123456789
"0123456789" (se puede abreviar como 09) es un lenguaje de programacion basado en [brainfuck](https://es.wikipedia.org/wiki/Brainfuck) que usa los numeros del 0 al 9 como instrucciones.


| Instruccion  | Significado                                                                                                                           |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------- |
| `1`    | Incrementa el puntero.                                                                                                                      |
| `2`    | Decrementa el puntero.                                                                                                                      |
| `3`    | 	Incrementa el byte apuntado.                                                                                                               |
| `4`    | Decrementa el byte apuntado.                                                                                                                |
| `5`    | Escribe el byte apuntado en el flujo de salida..                                                                                            |
| `6`    | 	Lee un byte del flujo de entrada y lo almacena en el byte apuntado.                                                                        |
| `7`    | Avanza a la instrucción inmediatamente posterior al 8 correspondiente si el byte actualmente apuntado es nulo (si es 0).                    |
| `8`    | 	Retrocede a la instrucción inmediatamente posterior al 7 correspondiente si el byte actualmente apuntado no es nulo (si es distinto de 0). |
| `9`    | Imprime el codigo fuente del programa en el byte apuntado                                                                                   |
| `0`    | Imprime un numero aleatorio de 0 al nueve en el byte apuntado                                                                               |

## Ejemplos
Coloca numeros del 0-9 en 10 casillas de memoria:
<pre <span class="nb">131331333133331333331333333133333331333333331333333333</span> </pre> <br>
Imprime Hello World en ASCII,
<pre <span class="nb">33333333337133333331333333333313333333333313331322222481331134442444113323333333334444444233313131</span> </pre> <br>
Interprete de 09 escrito en 09 (basado en https://brainfuck.org/dbfi.b)
<pre <span class="nb">11137748117483313133333337233331133248331131313333371331333333224831116233771741182711822482728231171817231477231481827774828332472333333333172414811811882282827728177181171183722827282311481718374118222277228272832273132247144132247132711322488817231482833114417181171188227113277282817722827283742311472231331472417223114888271324818171818171181182271131131182274111111118227111111118227141111182271611182271318227322828</span> </pre> <br>
Si haces algo sorprendente escrito en 09, puede que aparezcas aqui, asegurate de guardar tus archivos en formato .09 (:
## Interprete y convertidor
En este repositorio se encunetra un interprete de 09 escrito en Scratch, ademas, puesto que 09 y brainfuck es exactamente igual, se incluye un convertidor para convertir proyectos de brainfuck a 09 y viceversa
> [!NOTE]
> El 0 y el 9 son instrucciones unicas de 09 que brainfuck no tiene, por lo tanto, si conviertes un proyecto de 09 a brainfuck, se ignoraran esas 2 instrucciones
