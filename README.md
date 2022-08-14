<p align="center"> 
  <img src="logo.png.png" align="" alt="Logo">
</p>
 
<h1 align="center">FakeNewsify</h1> 

<p align="center">
A web app geared towards disclosing real vs fake news articles/sources while visually representing them
</p>

<p align="center">
A link to a small YouTube demo can be found here: <a href="https://www.youtube.com/watch?v=rbDgyr0pr6o" target="_blank">youtube.com/watch?v=rbDgyr0pr6o</a>
</p>

<p align="center">
The app is currently deployed to heroku, you can check it out here: <a href="https://fakenewsify.herokuapp.com" target="_blank">fakenewsify.herokuapp.com</a>
</p>

## Setup

#### Clone

```
git clone https://github.com/aahmad4/FakeNewsify
```

#### Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.

```bash
pip install -r requirements.txt
```

#### Usage
```
cd FakeNewsify
```
First make sure you download NLTK properly. Run these in your terminal and click `download` when the popup shows. 
```
python
>>> import nltk
>>> nltk.download()
```
Run app.py
```
python app.py
```
Then go to 
```
http://127.0.0.1:5000/
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
