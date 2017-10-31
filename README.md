# Bioinformática-Solemne-2-(BIT120)

# Nombre: Byron Guzmán Marín


# Parte I: Metagenómica, Metranscriptómica y Microbioma humano

__1.Usted trabaja como asistente de investigación en el Centro de Bioinformática y Biología Integrativa de la Universidad Andrés Bello. Su jefe le asigna un proyecto de alta prioridad: se le indica que, en el refrigerador (a -20ªC), usted encontrará un tubo eppendorf que contiene ADN aislado desde una muestra fecal proveniente de un paciente, cuya identidad desconoce (no es importante). El paciente presenta claros síntomas de una infección bacteriana intestinal, pero no se ha podido identificar la identidad del patógeno responsable mediante el método tradicional de cultivo en placas de Petri. Disponiendo usted de una muestra de ADN total aislado de una muestra de heces del paciente, describa de forma breve y precisa su plan de trabajo, paso a paso, para responder a la siguiente pregunta: ¿Qué bacterias están presentes en la muestra?__


Para identificar las bacterias que están presentes en la muestra optaria por metataxonomica utilizando  amplicon sequencing, ya que esté muestra los perfiles taxonómicos, en cambio no utilizaría shotgun sequencing,ya que no se conoce el organismo, en tanto para realizar la investigación me enfocaría  en el gen 16S. Por otro  lado para analizar los contigs (datos) de la muestra haria un análisis por referencia, debido que al utilizar el gen 16S este tiene regiones conservadas y regiones variables  que son unicas de cada especie siendo esto útil para reconocerla (bacteria), despues de las secuencias obtenidas y marcadas, seguidamente se tomaría  cada secuencia y se realizaria un alineamiento en blast con el fin de determinar la identidad de la muestra.

__2. Siguiendo con la situación planteada en el enunciado anterior (1). Usted ya tiene los resultados de su trabajo, es decir, usted sabe qué bacterias están presentes en la muestra. De acuerdo a sus hallazgos, ¿bajo qué criterios usted indicaría a una de las bacterias como el patógeno y por qué?__

Como ya se conoce los organismos que se encuentran en la muestra, se elegirá el que tiene más abundancia en la muestra (OTUs), es decir el que presente mayor abundancia relativa en la muestra, llegando a deducir  que si este se encuentra presente mayormente en la muestra puede conllevar a una alta probalilidad de que  sea el causante de la enfermedad, es decir que pertenezca a una bacteria patógena, por ende como ya se conoce el organismo (bacterias), se  realizaría un shotgun sequencing para identificar su secuencia, luego haría  un ensamblaje de novo, con la finalidad de obtener mayor información taxonómica de la especie y tener su secuenciación completa, luego procedería a comparar con una base de datos (NCBI) para realizar una filogenia y luego ver los organismos que se encuentran cercanos evolutivamente para establecer una relación de patogenicidad, osea, si existe un organismo, cercano evolutivamente al que elegimos como posible patógeno, y este posea factores de patogenicidad, por ejemplo que posea una adhesina bacteriana como es el caso del antigeno O en el que es super variable y al ser una adhesina podría permitir que un grupo super selecto de bacterias interactuen con un grupo super selecto de receptores, permitiendo que la bacteria pueda no solamente  que le guste el ambiente, sino que pueda interactuar firmemente con determinadas adhesinas  y que no se la lleve el producto de lo que sea como es el caso de la boca que posee un flujo turbulento, conllevando  todo esto a que exista una gran posibilidad que el organismo que sospechamos que es el patógeno lo sea.




# Parte II. Proteínas y evolución

1.__Según lo visto en el laboratorio, en este caso requerirá caracterizar evolutivamente proteínas de la familia de isoprenyl synthetase (debe elegir al menos 5 proteínas distintas) determinando si ¿existe una relación evolutiva convergente o divergente entre ellas? y ¿porque?, para lo cual deberá utilizar las distintas herramientas como las bases de datos Uniprot, Prosite,Pfam, entre otras.__ 

Al momento de realizar la búsqueda “isoprenil synthetase” nos entregó 2 resultados, en el cual uno era polyprenyl synthetase y el otro isoprenyl diphosphate synthases, luego de una investigación más exhaustiva se comprendió que la isoprenyl diphosphate synthases era una subfamilia de la polyprenyl synthetase, por lo tanto la familia que buscamos es polyprenyl synthetase, por lo cual se utilizó este como  para el trabajo.
Para mayor seguridad cruse la información con las bases de datos de Pfam ,scop,ncbi (articulos cientificos) y UniProt. 
)Seleccione 5 proteínas de interés para generar el árbol filogenético, para lo cual en la misma página Pfam seleccione el índice arbol (trees)(1), en el cual me di cuenta que existe una relación entre el valor y la similitud entre secuencias, siendo 1,000 (uno) secuencias totalmente distintas y valores más cercanos a cero secuencias muy similares. Por otro lado como ya conocemos el código uniprot proporcionado por la pag Pfam, se accedio a uniprot, permitiendo este  acceder a la información de las 5 proteínas, en cuanto al nombre de las proteínas, tipo de organismo, gen, secuencia,  función, código Uniprot, entre otros. A continuación al recopilar información se procedió acceder  a Aling (2) dentro de uniprot con la finalidad realizar un árbol filogenético, paralelamente se utilizo  clustaw2 Phylogeny (3) con el proposito de obtener una segunda opinión de la estructura del arbol o su robustez, en cuanto a los resultados obtenidos por las 2 paginas (clustaw2 y uniprot) generaron arboles diferentes, en el cual con el cladograma de uniprot (4) podemos distinguir que una familia de secuencias de proteinas (G2MHH5,F7PNM1,D4GZT2) son cercanos evolutivamente y perteneciendo estos 3 a Archea, por otro lado B9TQA8 y E6WQZ5 correspondieron a distintos organismo (Eucarionte y Bacteria. En tanto  a sus estructuras al momento de analizar sus secuencias de proteinas(G2MHH5,F7PNM1,D4GZT2,B9TQA8, E6WQZ5) sufren unos pequeños cambios de aminoacidos (5), en donde las 2 últimas presentan más diferencia estructural en comparación a las primeras 3 sec de proteínas, por lo que se deduce que estos aminoácidos han sido cambiados por la naturaleza con el fin de modificar la estructura de la proteína, por otro lado clustaw2 (6) se  logra observar distancias evolutivas distintas, en el cual B9TQA8_RICCO  y E6WQZ5_PSEUU sus relaciones filogeneticas son muy distantes en comparación al resto (G2MHH5_9ARCH,F7PNM1_9EURY,D4GZT2_HALVD).

En tanto al obtener el alineamiento por uniprot se obtuvo un porcentaje de identidad del 15.294% y al  hacer click en propiedades de los aminoácidos donde dice similarity se observa que las primeras 3 sec de proteínas (G2MHH5,F7PNM1,D4GZT2) son muy similares, finalmente al recopilar toda la información de prosite, pfam e interpro se obtuvo que todas poseen 1 dominio  característico que corresponde a poliprenil sintetasa, finalmente se llega a concluir que estas 5 proteínas poseen una relación divergente, ya que poseen una función similar entre ellas (Proceso biológico: proceso biosintético isoprenoide), pero algunas de ellas pudieron especializarse y obtener nuevas funciones como es el caso de F7PNM1 que adquirio 3 funciones moleculares, además con lo aprendido en clases se sabe que los organismo utilizan la energía con el fin de  conservar estructuras importantes entre estas  que les permitan ser de un aporte para la supervivencia. 

En resumen las razones de los programas utilizados para la investigación son los siguientes; se utilizo Pfam ya que este al ser una base de datos de familias de proteinas lo utilizamos para obtener informacion de la familia que se nos otorgo en la pregunta y tambien obtener informacion relacionada con la formacion del arbol ¨obtencion de secuencias´´, analisis de relación de datos; también se utilizo interprot ya que este unifica multiple bases de datos y sitios funcionales incluyendo Prosite, Pfam; otra herramienta utilizada fue Uniprot, en donde generalmente se utiliza para realizar un blast entre las secuencias para poder obtener una idea de un arbol filogenetico y asi mismo obtener información biologica de las 5 proteinas; finalmente la otra herramienta utilizada fue clustaw2, ya que esta es una herramienta bioinformatica con mayor precisión al momento de generar arboles filogeneticos.



__Artículos NCBI arrojados al buscar proteínas de la familia isoprenyl synthetase__

1) https://www.ncbi.nlm.nih.gov/pubmed/1303794?dopt=Abstract

2) https://www.ncbi.nlm.nih.gov/pubmed/1826006?dopt=Abstract

3) https://www.ncbi.nlm.nih.gov/pubmed/2089044?dopt=Abstract



__Links de imágenes__

(1) https://www.dropbox.com/s/yf3ym10pwfiddxz/Captura%20de%20pantalla%202017-10-31%20a%20la%28s%29%2000.55.29.png?dl=0

(2) https://www.dropbox.com/s/ncho02rmrl0jxqg/Captura%20de%20pantalla%202017-10-31%20a%20la%28s%29%2001.04.40.png?dl=0

(3) https://www.dropbox.com/s/d3rh43jgox34i4p/Captura%20de%20pantalla%202017-10-31%20a%20la%28s%29%2001.08.09.png?dl=0

(4) https://www.dropbox.com/s/nmh60evclmrl1ld/Captura%20de%20pantalla%202017-10-31%20a%20la%28s%29%2001.10.49.png?dl=0

(5) https://www.dropbox.com/s/wdrqbvgdr72o1fz/Captura%20de%20pantalla%202017-10-31%20a%20la%28s%29%2001.13.18.png?dl=0

(6) https://www.dropbox.com/s/0j5gbjwie4km5ux/Captura%20de%20pantalla%202017-10-31%20a%20la%28s%29%2001.15.39.png?dl=0

__Tabla con información biológica de las 5 proteínas investigadas:__ https://www.dropbox.com/s/0eiabmhn3m6cxzx/Captura%20de%20pantalla%202017-10-31%20a%20la%28s%29%2002.30.57.png?dl=0

