# TV-Show-and-Movies-Recommendation-Project
![Collage](https://i.redd.it/128uj78z58m01.jpg)

**TV Show and Movies Recommendation Project by Content-Based Filtering.**

![Content-Based Filtereing](https://miro.medium.com/max/625/1*BME1JjIlBEAI9BV5pOO5Mg.png)


This Project uses cosine-similarity to recommend movies and tv-shows to the user.

![Cosine Based-Similarity](https://wikimedia.org/api/rest_v1/media/math/render/svg/1d94e5903f7936d3c131e040ef2c51b473dd071d)
![Cosine Based-Similarity](https://www.oreilly.com/library/view/statistics-for-machine/9781788295758/assets/2b4a7a82-ad4c-4b2a-b808-e423a334de6f.png)

Why cosine-similarity?
Cosine similarity is generally used as a metric for measuring distance when the magnitude of the vectors does not matter. This happens for example when working with text data represented by word counts(as in this project for the column combined features).
The Combined Features refer to genres+actors+directors for Movie and genres+actors(for simplicity as many tv shows have different director for many episodes) for TV Shows.
When plotted on a multi-dimensional space, where each dimension corresponds to a combined feature(in this project), the cosine similarity captures the orientation (the angle) of the combined features and not the magnitude.

To calculate similarity using angle, you need a function that returns a higher similarity or smaller distance for a lower angle and a lower similarity or larger distance for a higher angle.
The cosine of an angle is a function that decreases from 1 to -1 as the angle increases from 0 to 180.
The cosine similarity is advantageous because even if the two similar combined features are far apart by the Euclidean distance because of the size, they could still have a smaller angle between them. Smaller the angle, higher the similarity.
![Eucledian](https://files.realpython.com/media/cosine-similarity.76bcd5413eb8.jpg)


