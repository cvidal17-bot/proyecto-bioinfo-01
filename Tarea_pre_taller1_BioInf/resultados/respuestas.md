&#x20;**1)	¿Cuántos dominios estructurales (o regiones) conservadas, con más de 3 amino ácidos, existen en las aldehído oxidasas proporcionadas LbotAOX1, EsemAOX1, CmedAOX1 y SinfAOX1?**



Existen 3 dominios estructurales principales en cada una de las aldehído oxidasas analizadas.

Se utilizó la herramienta batch web CD-Search tool en modo "Concise". Se contabilizaron las regiones conservadas independientes, agrupando las subregiones `Ald\_Xan\_moly\_bd` y `MocoBD\_2` como un solo dominio de unión a Molibdopterina. Las superfamilias que abarcan toda la secuencia (como `PLN02906`) no se contaron como dominios estructurales separados.



**2)	¿Cuál es el clado evolutivamente más distante entre las secuencias analizadas y el general de clados conformados? Justifique su respuesta.**



El clado evolutivamente más distante es el grupo de las Xantina Deshidrogenasas (XDH) compuesto por CcapXDH, CvicXDH, DpleXDH, BmorXDH y MrotXDH.

En el árbol filogenético, este clado se separa en la raíz (de forma basal) del resto de las secuencias, actuando como el grupo externo (outgroup). Esto indica que divergieron del ancestro común antes que el resto de las enzimas.

La rama que conecta a este clado con el resto del árbol presenta la mayor longitud evolutiva. Esto significa que acumularon una gran cantidad de cambios genéticos (sustituciones de aminoácidos) a lo largo de su historia evolutiva.

Al comparar solo las Aldehído Oxidasas (AOX), el clado más distante es el de los dípteros (AaegAOX, CquiAOX, AgamAOX y DmelAOX1-4), el cual se separa basalmente del gran grupo de los lepidópteros (Cmed, Ofur, Lbot, Sinf, Esem, etc.).



**3)	Describa qué herramientas bioinformáticas utilizó para analizar y responder a las preguntas anteriores y para qué las utilizó.** 



Terminal de Ubuntu

* Como entorno de trabajo principal. Permitió ejecutar comandos de Linux, gestionar archivos (copiar, mover, concatenar), limpiar secuencias y ejecutar herramientas bioinformáticas de línea de comandos.



EMBOSS Transeq (Online)

* Traducción de secuencias nucleotídicas a proteicas. Se utilizó específicamente para traducir la secuencia de \*Pxyl\* (`Pxyl\_nt.fasta`) en sus 6 marcos de lectura, permitiendo seleccionar la secuencia correcta de aminoácidos (`Pxyl\_aa.fasta`).



ClustalW

* Alineamiento Múltiple de Secuencias (MSA). Se utilizó para alinear todas las secuencias de AOXs y XDHs (`AOXs\_all.fasta`), generando una matriz con gaps (`-`) que refleja las regiones conservadas y variables.



MEGA 11

* Análisis filogenético. Se utilizó para importar el alineamiento, buscar el mejor modelo evolutivo (Maximum Likelihood) y construir el árbol filogenético mediante el método de Neighbor-Joining con 100 réplicas de Bootstrap.



FigTree

* Visualización y análisis del árbol filogenético. Permitió abrir el archivo Newick (`arbol.nwk`), colorear los clados y medir las longitudes de rama para identificar el clado evolutivamente más distante.





Batch Web CD-Search Tool

* Anotación funcional y estructural. Se utilizó para analizar las secuencias de LbotAOX1, EsemAOX1, CmedAOX1 y SinfAOX1, identificando y contando sus dominios conservados (Ferredoxina, FAD-binding, Molybdopterin-binding).





Git y GitHub

* Control de versiones y entrega. Permitió organizar los archivos en carpetas (`datos/`, `resultados/`, `figuras/`), registrar los cambios y subir el taller completo al repositorio remoto para su evaluación.







