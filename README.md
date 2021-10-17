<h1> Know the Price Of your Car!!! </h1>
 
<h2> Description</h2>

I had made an interactive web app so as to predict the price of Car on the basis of following parameters.

- Purchase Year
- Showroom Price
- Kilometers driven
- No. Of Owners
- Fuel Type
- Dealership type
- Transmission type
<br>
<h2> LIVE LINK : https://carsifythepredictor.herokuapp.com/ </h2>
 
 <br>
 <h2>Model</h2>
<br>

The model used is Random Forest.
(https://github.com/Vipul1947/Car_price_predictor_vipul/blob/main/random_forest_model.pkl)
<br><br>
<h2> Dataset for training</h2>
The dataset used for training and evaluating the model: (https://github.com/Vipul1947/Car_price_predictor_vipul/blob/main/data/car%20data.csv). The obtained model has achieved 99% accuracy on the test set.
<br>
<br>
<h2> FLOW CHART </h2>

![WhatsApp Image 2021-10-17 at 18 53 32](https://user-images.githubusercontent.com/56962974/137629251-286e867d-22e1-4cdf-8526-6a6eb03f9c1f.jpeg)

<br>
<h2> Dependencies</h2>

For this project, the following tools were used:
- Random Forest for building and training the model
- [Numpy](https://numpy.org/) for working with arrays
- [Matplotlib](https://matplotlib.org/) for visualizing the data
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) for implementing the server side
- HTML5, CSS3, JavaScript on the front-end.
<br><br>
<h2>IO Screenshots</h2>

![image](https://user-images.githubusercontent.com/56962974/137628477-f3801363-f88f-4a0a-bacf-fd37e688ad07.png)

![image](https://user-images.githubusercontent.com/56962974/137628510-8f3b9244-fd3e-4575-a111-0ff256c1ecc8.png)

<br>

<h2> Install and run on local host</h2>

<h4>To install and run local host:</h4>

```bash
git clone https://github.com/Vipul1947/Car_price_predictor_vipul.git
cd Car_price_predictor_vipul
pip install -r requirements.txt
python app.py
```
