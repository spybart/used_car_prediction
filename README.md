# Practical Application Assignment 11.1
## What Drives the Price of a Car?

by Murat Tulca

jupyter notebook:
https://github.com/spybart/assignment_11_1/blob/main/used_car_prediction.ipynb

## Goal: Understand what factors make a car more or less expensive.

### Results of used car dataset investigation:

Having evaluated multiple models, we have seen that `RandomForestRegressor()` performed the best for this task.

Using our best model, we were able to determine the level of impact each feature on the price:
* We can see that `year` is the most impactful features in determining the price of a car.
* Features with medium impact on a car include `odometer`, `manufacturer`, `model`, and `fuel`
* The rest of the features  (`transmission`, `region`, `state`, `title_status`) have little impact on the price of a car

Using our model, we are able to accurately and fairly price used cars. We are also able to optimize our stock of used cars by keeping the ones that sell at a higher price, and get rid of the ones that will sell for a lower price.