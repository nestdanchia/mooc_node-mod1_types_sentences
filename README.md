# Entrega mooc_node-mod1_types_sentences
# miradaxModulo1
test miradax modulo1
Si sigo las instrucciones del test da 1/10.5  si no imprimo por consola la primer linea en blanco el programa tampoco detecta las tablas pero el resultado del tests es 8/10.5
daniel@DESKTOP-GTVGOF8 MINGW32 /c/miradaxnodejs6/ejemplosM1/test1/mooc_node-mod1_types_sentences-master
$ npm run checks

> mooc_node-mod1_types_sentences@ checks C:\miradaxnodejs6\ejemplosM1\test1\mooc_node-mod1_types_sentences-master
> node tests/launcher.js


Test: 1: Checking that the assignment file exists...
        Score: 0.5/0.5
        Remarks: The directory 'C:\miradaxnodejs6\ejemplosM1\test1\mooc_node-mod1_types_sentences-master' has been found

Test: 2: Running 'mooc_node-mod1_types_sentences.js'
        Score: 0.5/0.5
        Remarks: The file has been successfully run

Test: 3: Checking the output length
        Score: 1.5/1.5
        Remarks: The output length is OK

 Good morning, its 12 hours

Test: 4: Checking the initial greeting
        Score: 1.5/1.5
        Remarks: The initial greeting has been found

Test: 5: Checking that the PI value is printed
        Score: 1.25/1.25
        Remarks: 6 decimals of the PI value have been found

Test: 6: Checking the equivalence table
        Score: 0/1.25
        Remarks: The element 24 has not been found.
                        Expected: /.*?24.*?18.*?30.*?11000.*?/
                        Received: 23 dec  =17hex= 27oct =10111 bin

Test: 7: Checking the equivalence table for odd numbers between 10 and 20
        Score: 0/1.25
        Remarks: The element 0 has not been found.
                        Expected: /.+?1.+?1.+?1.+?1.+?/
                        Received:

Test: 8: Checking that unicode characters are printed correctly
        Score: 1.25/1.25
        Remarks: 'hello' in chinese has been found

Test: 9: Checking that the farewell sentence is printed
        Score: 1.5/1.5
        Remarks: The farewell sentence has been found
Final Result: 8/10.5
daniel@DESKTOP-GTVGOF8 MINGW32 /c/miradaxnodejs6/ejemplosM1/test1/mooc_node-mod1_types_sentences-master
$

Puede descargar este programa
al ordenador local, como un fichero ZIP. El programa puede clonarse también con `git clone ..` (si
git está instalado).

Una vez descargado, se debe entrar en el directorio `mooc_node-mod1_types_sentences` (descargado) y
completar el programa pedido en el fichero `mooc_node-mod1_types_sentences.js` (este fichero esta ya vacío
en dicho directorio). El fichero `mooc_node-mod1_types_sentences.js` debe editarse o sustituirse por otro con
la solución. La ejecución del programa-de-test indica que partes del código del fichero
`mooc_node-mod1_types_sentences.js` se han realizado correctamente y cuales no.

El programa-de-test se copia, instala y ejecuta con los siguientes comandos:

```bash
$ ## El .zip del programa-de-test puede descargarse o copiarse con el siguiente comando:
$ git clone https://github.com/practicas-ging/mooc_node-mod1_types_sentences
$
$ cd mooc_node-mod1_types_sentences ## El directorio de trabajo pasa a ser el del proyecto copiado: entrega_
$
$ npm install ## Instala el programa-de-test, que es un paquete npm
$
$ npm run checks ## Pasa los tests indicando que partes de mooc_node-mod1_types_sentences.js
……..………………… ## están correctamente implementadas y cuales no.
...(realimentación)....
$
```

Los tests pueden pasarse tantas veces como sea necesario; incluso con el ejercicio incompleto.
El programa-de-test incluye además un comando para generar el fichero ZIP

```bash
$
$ npm run zip ## Este comando comprime los ficheros a entregar como un fichero xx.zip
$             ## El directorio de trabajo contiene ahora el fichero: mooc_node-mod1_types_sentences.zip
```

El fichero `mooc_node-mod1_types_sentences.zip` contiene los ficheros de la practica comprimidos y puede subirse a la plataforma para su evaluación.
