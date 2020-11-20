# Real Estate Price Prediction Model
> A Simple real estate price prediction model built using Linear Regression on real estate prices dataset of Bangalore from Kaggle.Linear Regression is applied for finding the estimated prices in different locations.

### Back End
* Uses Flask Server for handling HTTP requests. The Linear Regression Model is saved as a pickle file and then used to make predictions. The data is sent in reponse as JSON which is fetched via jquery and displayed on the client side

### Front End
* Uses HTML and CSS templates for the front end of the application 

```python server.py``` from the ```server``` directory from the server directory to start the flask server on your localhost

Note : This is a static model and uses a particular dataset for making predictions. It does not take into consideration any volatilities or changes in the price of the properties or external non measurable factors.
