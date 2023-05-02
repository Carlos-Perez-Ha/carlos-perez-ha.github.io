## Cartogram

- **Técnica**: Cartograma.
- **Usos**: Se utiliza para distorsionar las regiones de un mapa, en función de una variable cuantitativa. Es muy útil para resolver el sesgo que puede producir la diferencia de la muestra entre las regiones.
- **Tipo de dato utilizado**: Turistas por CCAA. Los datos provienen de [datos.gob.es](https://datos.gob.es/es/catalogo/ea0010587-numero-de-turistas-pernoctaciones-y-duracion-media-por-ccaa-de-destino-desglosados-por-continente-y-pais-de-residencia-identificador-api-52046). 
- **Herramienta**: He utilizado las librerías cartogram y mapSpain, además de ppplot. La librería mapSpain permite obtener objetos Simple Feature geemétricas, que representan las CCAA. Los datpos de los turstas por CCAA, son datos cuantitativos, que se transforman a escala log10, para no deformar demasiado el mapa.

### Visualización

![Cartogram](/cartogram.svg)

## Dendrogram

- Técnica: Dendrograma
- Usos: Se utiliza para representar una estructura jerarquica.
- Tipo de datos utilizado: Felinos en peligro de extinción de [Rawgraphs.io](https://github.com/rawgraphs/rawgraphs-app/blob/master/public/sample-datasets/Dendrogram%20-%20Felidae%20classification.tsv)
- Herramienta: [Rawgraphics.com](https://www.rawgraphs.io/)

### Felinos en peligro de extinción
#### (Clasificados jerárquicamente)
![Dendrogram](/Felinos_Dendrogram.svg)

## BeeSwarm

- Técnica: BeeSwarm
- Usos: Se utiliza para representar la distribución de un conjunto de datos, mitigando el solapamiento que se puede producit en los datos.
- Tipo de datos utilizado: Los tiros de Kobe Bryant de [Rawgraphs.io](https://github.com/rawgraphs/rawgraphs-app/blob/master/public/sample-datasets/Hexbin%20-%20basketball%20shots.tsv)
- Herramienta: [Rawgraphics.com](https://www.rawgraphs.io/)

### Visualización

![BeeSwarm](/beeswarm.svg)
