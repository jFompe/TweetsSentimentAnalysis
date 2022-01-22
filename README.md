# Tweets Sentiment Analysis

The code is in R Markdown format, to run it just download the nlp.Rmd and open it with RStudio.
Once opened, not much configuration should be needed before being able to run the code.

### Steps for TWitter API
For retrieving the tweets from Twitter's API, it will be necessary to create a developer account in https://developer.twitter.com/en.
Once created, it is necessary to create an application in order to obtain an API key and secret.
Then, these are used to obtain a token and token secret inside the same platform.

After getting the 4 keys, they should be substituted in the key, secred, access_token and acces_secret variables respectively.
Then, the lines for the create_token call should be uncommented.

### Actually running the code
Once this is done, the program can be run and similar results to the ones in the memory should be obtained (Take into account that the tweets you get will be different to the ones I got).

To finally run the code, the shortcut Ctrl+Alt+R can be used to run all the chunks in the file, or they can also be ran individually.

### Change topic of analysis
A similar analysis can be done for different topics by simply changing the HASHTAG,LANG or VERIFIED_ONLY variables and rerunning the code.


### View results
If you just want to see the initial results without running the code yourself, you can just download the nlp.html file and open it with any browser.
