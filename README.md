# Postulacion dinamica plataforma
* Nombre: Rodolfo Godoy Arteaga
## Objetivo: 
Parto de una problemática común para empresas como Google, Windows o navegadores web que recomiendan noticias a los usuarios. El problema que percibí en los datos (y que me llevó a esta posible problemática) es que las secciones no son consistentes, aunque la noticia sea la misma. Esto me llevó a explorar modelos no supervisados para categorizar adecuadamente los datos. Si se resolviera este problema con un buen modelo, se podría aplicar ciencia de datos para identificar nombres de categorías y predecir tendencias temporales (torneos de fútbol, votaciones, fiestas culturales, etc.).
## Resumen:
La idea principal fue clusterizar las noticias para encontrar categorias, para ello se ocupo un modelo preentrenado llamado **BERT** orignal de google, se ocupó su transformer a los datos y asi entrenar modelos analitocs (KMeans y HDBSCAN), además se utilizó la libreira BERTOPIC, asi entrenar un modelo no supervisado con una arquitectura ya construida, se acompañó con el modelo Kmeans. Luego se compararon resultados y se realizó un analisis exploratorio para poder seleccionar las categorias. El objetivo principal era además entrenar un moddelo supervisado para clasificar categorias y asi tener un codigo ya automatizado para nuevos datos y asi llevarlo a produccion, peor debido al tiempo y la calidad de los cluster, no se desarrollo esa idea.
## Agradecimientos:
Queria agredecerles por la oportunidad de realizar el test, no he tenido mucha expericia con este tipo de datos, fue un gran desafio y me entregó muchos aprendizajes. Gracias. Saludos
## Notas:
Desarrolle el test usando python en un notebook en google colab, algunos graficos interactivos no se logran apreciar en github.
