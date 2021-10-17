<h1> Classify fruits and check their freshness </h1>
 
<h2> Description</h2>

I had made an interactive web app so as to classify fruits into :

- Apple
- Banana
- Orange


Also it tells whether the fruit is fresh/rotten and to implement this webapp we had used Flask (a framework of Python), which uses a convolution neural network on the back end to perform the above classification.
<br>
<h2> LIVE LINK : https://carsifythepredictor.herokuapp.com/ </h2>
<br>
 <h2>Model</h2>
<br>

The model used is Random Forest.
(https://github.com/yashrajjain726/Carsify-The-Car-Price-Predictor/blob/master/random_forest_model.pkl)
<br><br>
<h2> Dataset for training</h2>
The dataset used for training and evaluating the model: (https://github.com/Vipul1947/Car_price_predictor_vipul/blob/main/data/car%20data.csv). The obtained model has achieved 99% accuracy on the test set.
<br>
<br>
<h2> FLOW CHART </h2>

<br>
<h2> Dependencies</h2>

For this project, the following tools were used:
- Randome Forest for building and training the model
- [Numpy](https://numpy.org/) for working with arrays
- [Matplotlib](https://matplotlib.org/) for visualizing the data
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) for implementing the server side
- HTML5, CSS3, JavaScript on the front-end.
<br><br>
<h2>IO Screenshots</h2>


<br>

<h2> Install and run on local host</h2>

<h4>To install and run local host:</h4>

```bash
git clone https://github.com/Vipul1947/Car_price_predictor_vipul.git
cd Car_price_predictor_vipul
pip install -r requirements.txt
python app.py
```
