# Analyze and Generate AI

This program will read the data.txt file and analyze the words in that or it will use those data to optimize itself depending on the version. Then it will make some assumptions based on that data. After this process you can use this program to generate more words like those in data.txt file.

- basic_frequency.ipynb: Basic frequency table version, coded by using python and pytorch. This aproach is based on the char bigrams of the data.txt words. In this approach we get the words in data.txt file and then we create frequency table of the bigrams based on those words. Then we create words using that data.
- basic_neural_network.ipynb: Basic neural network version, coded by using python and pytorch. This is based on creating a basic neural network with just one layer. Then we use Gradient Descent algorithm to optimize our neural network to get better results. In this case we are using data.txt file to test our optimization results and creating our character library. 

Interestingly enough, if you use same seeds in both models and optimize this neural network to a point that Loss changes only so slightly, they generate exact same words. You check to see that by looking the outputs of these models.

- mlp_neural_network.ipynb: Still in progress...