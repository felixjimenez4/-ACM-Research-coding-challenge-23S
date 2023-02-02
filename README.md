# ACM Research coding challenge (Spring 2023)

![image](https://user-images.githubusercontent.com/72369124/211179527-0ee60624-2794-4e13-bf7f-f88b5c950e44.png)


This semester's challenge is especially open-ended. [Please refer to this dataset](https://www.kaggle.com/datasets/deepu1109/star-dataset) on Kaggle called "Star dataset to predict star types".  It contains information about 240 stars and various properties taken from "Stars and Galaxies" by Seeds and Backman. Each row contains 7 pieces of information about a star, such as its temperature, luminosity, radius, absolute magnitude, star type, star color, and spectral class.

Please note that the star type, denoted as integers, are translated as the following:
- Brown Dwarf -> Star Type = 0
- Red Dwarf -> Star Type = 1
- White Dwarf -> Star Type = 2
- Main Sequence -> Star Type = 3
- Supergiant -> Star Type = 4
- Hypergiant -> Star Type = 5

---

## INSTRUCTIONS: Please read this carefully, do not skim this!

### Here's the coding challenge: **What can you do with all of this data?** Yes, this is an **OPEN-ENDED** question and your answer should be a brief report, showcasing your skills. Can you find a pattern, answer a question, or create a visualization? In case nothing comes to mind, here are some ideas, with varying complexity:

- What is the most common star type in the data?
- What common patterns do you notice between any two properties? Ex: Is there a relationship between the star color and temperature?
- What properties are the most influential in classifying a star's type?
- Can you make a similar graph as the one shown in Kaggle to showcase the data as a Hertzsprung-Russell Diagram?
- Train a machine learning model to then predict the star type of a row of data (without the star type field) and find the model's accuracy.
Bonus: Can you find the row of data that most closely resembles our star, the Sun?


# Common patterns
Some of the common patters i saw was the trend to bring bigger in brighter after each star type
there was one notable exception to this and it was the type 2 star.