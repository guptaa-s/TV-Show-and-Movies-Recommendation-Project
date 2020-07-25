# TV-Show-and-Movies-Recommendation-Project
![Collage](https://i.redd.it/128uj78z58m01.jpg)

**TV Show and Movies Recommendation Project by Content-Based Filtering.**

![Content-Based Filtereing](https://miro.medium.com/max/625/1*BME1JjIlBEAI9BV5pOO5Mg.png)


This Project uses cosine-similarity to recommend movies and tv-shows to the user.

![Cosine Based-Similarity](https://wikimedia.org/api/rest_v1/media/math/render/svg/1d94e5903f7936d3c131e040ef2c51b473dd071d)
![Cosine Based-Similarity](https://www.oreilly.com/library/view/statistics-for-machine/9781788295758/assets/2b4a7a82-ad4c-4b2a-b808-e423a334de6f.png)

Why cosine-similarity?
To calculate similarity using angle, you need a function that returns a higher similarity or smaller distance for a lower angle and a lower similarity or larger distance for a higher angle.
The cosine of an angle is a function that decreases from 1 to -1 as the angle increases from 0 to 180.
So, what can you use to identify such patterns that Euclidean distance cannot? Can the angle between the lines joining the points to the origin be used to make a decision? You can take a look at the angle between the lines joining the origin of the graph to the respective points as shown:

![Eucledian](https://files.realpython.com/media/cosine-similarity.76bcd5413eb8.jpg)


