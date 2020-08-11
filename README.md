# Emojify! 

Have you ever wanted to make your text messages more expressive? This emojifier app will help you do that. 
So rather than writing:
>"Congratulations on the promotion! Let's get coffee and talk. Love you!"   

The emojifier can automatically turn this into:
>"Congratulations on the promotion! 👍 Let's get coffee and talk. ☕️ Love you! ❤️"

This is very tiny dataset where:
- training dataset contains 132 sentences (strings) & testing dataset contains 56 sentences.
- Y contains an integer label between 0 and 4 corresponding to an emoji for each sentence.

<img src="images/data_set.png" style="width:700px;height:300px;"><caption><center>EMOJISET - a classification problem with 5 classes.</center></caption>

There are 2 parts to this repo.<br>
Emojify.ipynb contains the implementation of basic model. <br>
Emojify_LSTM.ipynb contains the implementation of LSTM model for converting text to more expressive form.
