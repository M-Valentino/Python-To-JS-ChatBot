# Python-To-JS-ChatBot

This is a simple program that trains a simple linear AI chatbot model. This model is then exported to JSON and ran using JavaScript. Like 98% of this code was made by ChatGPT lol.

## Running
1. Edit the inputs and outputs in `training.csv` file to your liking.
2. First run the Jupyter Notebok. (You might have to install numpy, pandas, sklearn, or nltk).
3. You will get a `vectorizer.json` and a `model.json`. These files are fetched in `chatBot.html`.
4. Apply an origin to `chatBot.html` and open the file. If you don't do this, you will get CORS errors. You can achieve this by running `npx http-server --cors` if you have Node.js
