# AutoMPG Machine Learning Project Description

Our work will be split into 4 major parts, majorly:

1. Exploration and Visualization of data using pandas and seaborn packages (main purpose of the current notebook)

2. Building, evaluating and tuning different regression models using scikit learn package (next notebook "AutoMPG_Comparing_ML_Models")

3. Building, evaluating and tuning a simple deep learning regression models using Keras sequential package ( notebook "AutoMPG_Keras_DNN_Model")

4. Exploring MLFlow and configuring it to automate our experiments (notebook AutoMPG_MLFlow_AutomatedExperiments)

# About the dataset

### AUTOMPG: Mileage per gallon performances of various cars

The data is technical specification of cars. The dataset is downloaded from UCI Machine Learning Repository. It concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes." (Quinlan, 1993)

#### Source Origin: 
This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University. The dataset was used in the 1983 American Statistical Association Exposition.

#### Attribute Information

    - mpg: continuous
    - cylinders: multi-valued discrete
    - displacement: continuous
    - horsepower: continuous
    - weight: continuous
    - acceleration: continuous
    - model year: multi-valued discrete
    - origin: multi-valued discrete
    - car name: string (unique for each instance)

#### Key Points about MPG and how values could be interpreted

<p>MPG stands for "Miles Per Gallon." It is a measure of fuel efficiency used primarily in the United States to indicate how many miles a vehicle can travel on one gallon of fuel. The higher the MPG value, the more fuel-efficient the vehicle is, meaning it can travel further on less fuel.

    - **Miles** : Represents the distance traveled.
    - Per Gallon : Represents the amount of fuel used.
    - Calculation : If a car has an MPG of 30, it means that the car can travel 30 miles on one gallon of fuel.
    - Importance :
        - Fuel Efficiency: Higher MPG values indicate better fuel efficiency, which can save money on fuel costs and is better for the environment due to reduced emissions.
        - Cost-Effectiveness: Vehicles with higher MPG ratings are generally cheaper to operate over time.
        - Environmental Impact: More fuel-efficient vehicles typically produce fewer greenhouse gas emissions. </p>



