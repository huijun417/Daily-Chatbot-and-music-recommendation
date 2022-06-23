# Daily-Chatbot-and-music-recommendation


We explore chatbots: different
implementations, models and uses. In our work, we
have found that there are three approaches to
designing a chatbot. The first model is the naive
method where a model is trained on specific responses.
The second, the sequential model is more flexible than
the naive model but performs poorly. Finally we looked
into pre-trained models, particularly DialoGPT, which
is pre-trained on reddit discussion threads and is able
to perform the most humanlike conversation and has
the most flexibility in its use.



# CS263-Final-Project

## Dependencies

### Front End
We use React to implement the frontend. 
To install the dependencies, run:
```
npm install
```

The packages we used include:

### Back End

We use flask in the backend to interact with the frontend. 

Navigate into the api folder.

If you're on Mac, run the following:

```
$ python3 -m venv venv
$ source venv/bin/activate
```

If you're on Windows, run the following:

```
$ python -m venv venv
$ venv\Scripts\activate
```

Now you should be in the virtual environment. To install the dependencies, run:
```
pip install flask python-dotenv numpy nltk tensorflow torch transformers pysentimiento ibm_watson
```

Inside the api folder, create a file named .flaskenv and write the following:
```
FLASK_APP=api.py
FLASK_ENV=development
```

## Launch Website

### `yarn start`
yarn start command in the main directory start the frontend of our web application. 

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn start-api`
yarn start-api command in the main directory start the backend of our web application. 

You can interact with the frontend by webpage with our local database api/data.db

## Testing

### `python test.py`
In the api directory, you could run 'python test.py' and see the 13 unittest for backend in the 
terminal.
