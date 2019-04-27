# final-project

# PokePic

![Pokemon Banner](https://res.cloudinary.com/bbobba/image/upload/v1555160059/pkm-Banner.jpg)


## Project Description

Create a user interface (app/website) that allows the user to upload an image of a 1st generation Pokemon. The app will then return the name of the pokemon that most resembles the image (presumably the name of the Pokemon that was uploaded).

In the future, we would like the web application to also return an image of the Pokemon that most looks like the uploaded image, as well as the Pokemon’s statistics (i.e. combat power, strength, defense, attack, etc.)


## Inspiration

**Pokedex:** an electronic device designed to catalogue and provide information regarding the various species of Pokémon featured in the Pokémon video game, anime and manga series.


## Datasets


#### Model Testing & Training Images:
*   **Source:** Kaggle.com ([https://www.kaggle.com/thedagger/pokemon-generation-one](https://www.kaggle.com/thedagger/pokemon-generation-one)**)**
*   **Description:** This dataset includes over 10,000 images of first generation Pokemon, with between 50 and 90 images for each of the 151 Pokemon. The dataset is organized into 151 folders, one for each pokemon. Each folder contains 50 - 60 images for the corresponding Pokemon.
*   **Extraction method: **We downloaded a .zip file of the complete dataset from kaggle.com.


#### Pokemon Statistics Data (for future web application results):
*   **Source: **Kaggle.com ([https://www.kaggle.com/abcsds/pokemon](https://www.kaggle.com/abcsds/pokemon)**)**
*   **Description:** This dataset includes information for 151 gen 1 Pokemon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed. These are the raw attributes that are used for calculating how much damage an attack will do in the games. The data for this table was originally acquired from pokemon.com, pokemondb, Bulbapedia. 
*   **Extraction method:** We first filtered the kaggle dataset to include gen 1 Pokemon only, then downloaded a .csv file of the filtered data. 


#### Pokemon Profile Images (for future web application results):
*   **Source: **Giantbomb.com ([https://www.giantbomb.com/profile/wakka/lists/the-150-original-pokemon/59579/](https://www.giantbomb.com/profile/wakka/lists/the-150-original-pokemon/59579/)**)**
*   **Description:** This dataset includes 151 images, one for each gen 1 Pokemon.
*   **Extraction method:** We downloaded each image directly from the website and saved them in a local directory. 


## Prerequisites

*   Anaconda Jupyter Notebook
*   Python 2.7 (or higher)
*   Dependencies:
    *   Keras
    *   Numpy
    *   Argparse
    *   Imutils
    *   Pickle
    *   Cv2
    *   Os
    *   Matplotlib
    *   Pandas
    *   Sklearn
    *   Pyimageearch
    *   Random
    *   skimage


## Authors

* **Becky Bobba** - [bbobba](https://github.com/bbobba) 

* **Delayna Bradshaw** - [delaynabradshaw](https://github.com/delaynabradshaw)

* **Kelly Blumhagen** - [kellyblumhagen](https://github.com/kellyblumhagen)

* **Tito Odunsi** - [TitoOdunsi](https://github.com/TitoOdunsi)


## Acknowledgments

Citations to references, websites, blog posts, and external sources of information:

* Alberto Barradas ([https://www.kaggle.com/abcsds](https://www.kaggle.com/abcsds)) - Kaggle ‘Pokemon with Stats’ dataset 

* Harshit Dwivedi ([https://www.kaggle.com/thedagger](https://www.kaggle.com/thedagger)) - Kaggle “Pokemon Generation One” dataset

* Adrian Rosebrock - [jrosebr1]([https://github.com/jrosebr1](https://github.com/jrosebr1))

* This project was completed at the UT of Texas Data & Visualization Bootcamp
