# Cookie-crafter-with-GA
A creative cookie generator powered by genetic algorithms.

## Computational Creativity Assignment 2, Leiden University November 2023
By Lin He, Lily Kientz, Ruilin Ma


## SETTING UP:
To set up the Poem-generator you first have to upload the 'FinalCC2_G20.ipynb' to Google Colab.

Open 'FinalCC2_G20.ipynb' and run the topmost two code blocks to install and import the correct packages.


## GENERATING MODEL:
To generate the model, first run the following code blocks from top to bottom: 'Gather recipes', and 'Create knowledge base'. 

After this, you can run the implement recipe generator from top to bottom to create the model.


## GENERATING COOKIE RECIPES:
After having generated a model, you can run the 'run recipe generator' code blocks. 

First, choose and run the code blocks that define how many generations the model runs. More generations lead to a more stable but more generic cookie, while the fewer does the contrary. You can also change one of these numbers according to your liking.

Next, run the final code block. This will run the model and create a cookie recipe!

*An additional code block exists to show how nutrition estimation is achieved. This is not part of the generation process. In order to do that, you need to manually calculate the amount of each components and put them in accordingly. It is for showing purpose only and the amount may not be the case that the recipe generated shows.*
