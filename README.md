# Bayesian Weather Prediction

## About the Project

This project is a simple **probabilistic AI program** developed using Python.

It uses **Bayes' Theorem** to predict whether it is likely to rain when the sky is cloudy.

## Dataset

The program uses a small dataset of 20 days.

* Total Days = 20
* Rain = 8
* Not Rain = 12
* Cloudy among Rainy Days = 7
* Cloudy among Non-Rainy Days = 3

## Probabilities Calculated

The program calculates:

* P(Rain)
* P(Not Rain)
* P(Cloudy | Rain)
* P(Cloudy | Not Rain)
* P(Rain | Cloudy)
* P(Not Rain | Cloudy)

## Algorithm Used

**Bayes' Theorem**

Bayes' Theorem is used to find the probability of rain when the sky is cloudy.

```text
P(Rain | Cloudy)
=
P(Cloudy | Rain) × P(Rain)
---------------------------
P(Cloudy)
```

The two final probabilities are compared to predict the weather.

## Technologies Used

* Python

## Sample Output

```text
BAYESIAN WEATHER PREDICTION
---------------------------
P(Rain) = 0.4
P(Not Rain) = 0.6
P(Cloudy | Rain) = 0.88
P(Cloudy | Not Rain) = 0.25
P(Rain | Cloudy) = 0.82
P(Not Rain | Cloudy) = 0.18
Predicted Weather = Rain
```

## Conclusion

This project demonstrates how probability and Bayes' Theorem can be used in AI to make a simple weather prediction based on available data.
