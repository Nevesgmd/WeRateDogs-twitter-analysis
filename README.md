# Wrangling and Analyzing Data From WeRateDogs Twitter Page

This project was developed for the Udacity Data Analyst Nanodegree in order to prove the understanding of the 
topics covered in the Data Wrangling module. 

# Table of Contents
1. [Provided Data](#data)
2. [Prerequisites to contribute](#requisites)
3. [How to visualize the study](#visualize)
4. [License](#license)


<a name="data"></a>
## Provided Data
Three pieces of data were gathered initially for the development of the project:  

1. **Enhanced Twitter Archive** (given `.csv` file --> [data/twitter-archive-enhanced.csv](data/twitter-archive-enhanced.csv))
> "The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356)."
2. **Additional Data via the Twitter API** (gathered using [Tweepy](#https://www.tweepy.org/) --> [data/tweet-json.txt](data/tweet-json.txt))
> "Back to the basic-ness of Twitter archives: retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered by anyone from Twitter's API. Well, "anyone" who has access to data for the 3000 most recent tweets, at least. "
3. **Image Predictions File** (stored in Udacity servers --> [data/image-predictions.tsv](data/image-predictions.tsv))
>"One more cool thing: I ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images)."

<a name="requisites"></a>
## Prerequisites to contribute
The data extracted from the Twitter API is in the data folder (just make sure you don't overwrite `tweet-json.txt`), but if you want to access it directly from Twitter you must have an account with [developer account authorization](https://developer.twitter.com/en/apply-for-access). As soon as you have authorization, Twitter will send you API keys that you need.

After downloading/clonning all the files present in this repository, you must choose between one of the following methods. Choose wisely ;)

### Method 1
If you want to contribute, this project requires **Python 3** and its following libraries installed:

* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Tweepy](https://www.tweepy.org/)

Besides, you also need to install a software to use [Jupyter Notebook](https://jupyter.org/).  
I recommend downloading [Anaconda](https://www.anaconda.com/) (Python distribution), which already has all the necessary modules and Jupyter Notebook installed.

### Method 2
You can also decide to use [Google Colab](https://colab.research.google.com/), in this case, all you have to do is open the notebook (`.ipynb` file) on Google Colab with your account and install [Tweepy](https://www.tweepy.org/).  
You can find help to install libraries in Google Colab [here](https://stackoverflow.com/questions/51342408/how-do-i-install-python-packages-in-googles-colab).

<a name="visualize"></a>
## How to visualize the study
You can just download the this repository and open the `.html` files on your browser.

<a name="license"></a>
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


