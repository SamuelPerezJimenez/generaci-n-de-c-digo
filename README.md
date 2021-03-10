# Analizador Sintáctico y generación de código en c++ C# 

## Documentacion
generación de código: Al hacer clic en compilar se muestra un mensaje con la generación del código en c++ (el mismo se guarda en la carpeta raíz del programa)
Este analizar reconoce las siguientes palabras:
```
1. inicio
2. proceso
3. fin
4. si
5. ver
6. mientras
7. entero
8. cadena
```
## Ejemplo
```c#
inicio ;
cadena var1 # "hola" ;
entero var5 # 23 ;

proceso ;
si ( 23 == var5 )
{
ver "Analizador semántico" ;
}

si ( var1 == "hola" )
{
ver "MATERIA COMPILADORES" ;
}
fin ;
```
