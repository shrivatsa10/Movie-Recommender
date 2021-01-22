# Movie Recommender App
> This is a movie recommender application made using python and flask. It uses cosine similarity to create a matrix of similar movies and recommend movies based on the input.

![NPM Version][npm-image]
![Build Status][travis-image]
![Downloads Stats][npm-downloads]

[![header.png](https://i.postimg.cc/8zYcG9kX/header.png)](https://postimg.cc/18pscWqD)
[![header2.png](https://i.postimg.cc/bNJqvgB7/header2.png)](https://postimg.cc/9zv68dVb)

## Use

You can use this application to get a list of movies to watch whenever you feel like you are running out of options!

My application is live at: https://gbc-movie.herokuapp.com/


## Cosine Similarity

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

[![header3.png](https://i.postimg.cc/ZKcvGwyX/header3.png)](https://postimg.cc/QHFM5kmq)

<!-- Markdown link & img dfn's -->
[npm-image]: https://camo.githubusercontent.com/1c502d149c62da4bd1055404c29743154b7bdd316aab0d466025751c2df7e163/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e382d626c756576696f6c6574
[npm-downloads]: https://camo.githubusercontent.com/a8256d965b9ade271a5aa6fffecc3b4564a0ede3c8a77287b1de5310fece95da/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4672616d65776f726b2d466c61736b2d726564
[travis-image]: https://camo.githubusercontent.com/0b62a236c961e03fda7bc31de5e286161319fed1b9bfa162e825ad9d7e059e4f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f46726f6e74656e642d48544d4c2f4353532f4a532d677265656e