# Used Car Prediction
## What Drives the Price of a Used Car?

by Murat Tulca

jupyter notebook:
https://github.com/spybart/used_car_prediction/blob/main/used_car_prediction.ipynb

## Goal: Understand what factors make a used car more or less expensive.

### Results of used car dataset investigation:

Having evaluated multiple models, we have seen that `RandomForestRegressor()` performed the best for this task.

Using our best model, we are able to determine the level of impact each feature has on the price:
* We can see that `year` is the most impactful feature in determining the price of a used car
* Features with medium impact on a used car include `odometer`, `manufacturer`, `model`, and `fuel`
* The rest of the features  (`transmission`, `region`, `state`, `title_status`) have little impact on the price of a used car

Using our model, we are able to accurately and fairly price used cars. We are also able to optimize our used car inventory by keeping the ones that sell at a higher price and getting rid of the ones that sell at a lower price.
