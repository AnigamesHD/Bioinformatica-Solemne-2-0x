# Bioinformatica-Solemne-2-(BIT120)

# Nombre: Byron Guzmán Marín


# Parte 1: Metagenómica, Metranscriptómica y Microbioma humano

__1.Usted trabaja como asistente de investigación en el Centro de Bioinformática y Biología Integrativa de la Universidad Andrés Bello. Su jefe le asigna un proyecto de alta prioridad: se le indica que, en el refrigerador (a -20ªC), usted encontrará un tubo eppendorf que contiene ADN aislado desde una muestra fecal proveniente de un paciente, cuya identidad desconoce (no es importante). El paciente presenta claros síntomas de una infección bacteriana intestinal, pero no se ha podido identificar la identidad del patógeno responsable mediante el método tradicional de cultivo en placas de Petri. Disponiendo usted de una muestra de ADN total aislado de una muestra de heces del paciente, describa de forma breve y precisa su plan de trabajo, paso a paso, para responder a la siguiente pregunta: ¿Qué bacterias están presentes en la muestra?__


Para identificar las bacterias que están presentes en la muestra optaria por metataxonomica utilizando  amplicon sequencing, ya que esté muestra los perfiles taxonómicos, en cambio no utilizaría shotgun sequencing,ya que no se conoce el organismo, en tanto para realizar la investigación me enfocaría  en el gen 16S. Por otro  lado para analizar los contigs (datos) de la muestra haria un análisis por referencia, debido que al utilizar el gen 16S este tiene regiones conservadas y regiones variables  que son unicas de cada especie siendo esto útil para reconocerla (bacteria), despues de las secuencias obtenidas y marcadas, seguidamente se tomaría  cada secuencia y se realizaria un alineamiento en blast con el fin de determinar la identidad de la muestra.

__2. Siguiendo con la situación planteada en el enunciado anterior (1). Usted ya tiene los resultados de su trabajo, es decir, usted sabe qué bacterias están presentes en la muestra. De acuerdo a sus hallazgos, ¿bajo qué criterios usted indicaría a una de las bacterias como el patógeno y por qué?__

Como ya se conoce los organismos que se encuentran en la muestra, se elegirá el que tiene más abundancia en la muestra (OTUs), es decir el que presente mayor abundancia relativa en la muestra, llegando a deducir  que si este se encuentra presente mayormente en la muestra puede conllevar a una alta probalilidad de que  sea el causante de la enfermedad, es decir que pertenezca a una bacteria patógena, por ende como ya se conoce el organismo (bacterias), se  realizaría un shotgun sequencing para identificar su secuencia, luego haría  un ensamblaje de novo, con la finalidad de obtener mayor información taxonómica de la especie y tener su secuenciación completa, luego procedería a comparar con una base de datos (NCBI) para realizar una filogenia y luego ver los organismos que se encuentran cercanos evolutivamente para establecer una relación de patogenicidad, osea, si existe un organismo, cercano evolutivamente al que elegimos como posible patógeno, y este posea factores de patogenicidad, por ejemplo que posea una adhesina bacteriana como es el caso del antigeno O en el que es super variable y al ser una adhesina podría permitir que un grupo super selecto de bacterias interactuen con un grupo super selecto de receptores, permitiendo que la bacteria pueda no solamente  que le guste el ambiente, sino que pueda interactuar firmemente con determinadas adhesinas  y que no se la lleve el producto de lo que sea como es el caso de la boca que posee un flujo turbulento, conllevando  todo esto a que exista una gran posibilidad que el organismo que sospechamos que es el patógeno lo sea.




# Parte II. Proteínas y evolución

1.__Según lo visto en el laboratorio, en este caso requerirá caracterizar evolutivamente proteínas de la familia de isoprenyl synthetase (debe elegir al menos 5 proteínas distintas) determinando si ¿existe una relación evolutiva convergente o divergente entre ellas? y ¿porque?, para lo cual deberá utilizar las distintas herramientas como las bases de datos Uniprot, Prosite,Pfam, entre otras. 



Según lo visto en el laboratorio, en este caso requerirá caracterizar evolutivamente proteinas de la familia de isoprenyl synthetase (5 proteínas) determinando si ¿existe una relación convergente o divergente entre ellas? ¿porque?, para lo cual deberá utilizar las distintas herramientas como las bases de datos uniprot, prosite, pfam, entre otras.La evaluación de esta pregunta se asignará según la cantidad de herramientas utilizadas, determinando el porqué utilizó esta cantidad de herramientas, y la calidad de la discusión de los resultados obtenidos para inferir qué tipo  de relación evolutiva existe entre las proteínas seleccionadas

Respuesta: Primer lugar al buscar los isoprenil en en las bases de datos no se logra buscar en google luego buscamos en bases datos tales pfam el cual nos dio como resultado polyprenyl synt, al momento de buscar una familia de proteinas entonces debo buscar pfma entonces para estar más seguro busco, entonces asimilamos que la palabra iso puede ser isoform, buscamos en scop nos dio isoprenyl diphosphate synthases, por lo cual trabajamos con poliprenil sintetasa, de ncbi obtenimos 5 articulos de proteinas los cuales luego buscamos en ncbi




protein http://pfam.xfam.org/family/PF00348#tabview=tab5

https://www.rcsb.org/pdb/explore/explore.do?structureId=4gp1

http://www.uniprot.org/uniprot/H8GS93#family_and_domains

http://pfam.xfam.org/protein/H8GS93_DEIGI

http://www.rcsb.org/pdb/explore/explore.do?structureId=3n5j

https://www.ncbi.nlm.nih.gov/pubmed/1303794?dopt=Abstract

https://www.ncbi.nlm.nih.gov/pubmed/1826006?dopt=Abstract

https://www.ncbi.nlm.nih.gov/pubmed/2089044?dopt=Abstract

http://pfam.xfam.org/family/PF00348#tabview=tab5


