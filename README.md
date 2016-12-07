# biomet-partials

Todo:

Goal: Given a model that takes in multiple predictors, see how one predictor affects the output of the model.

Task:
Start with 2 predictors PPFD_IN and TA. Train a model that captures the relationship between PPFD_IN and TA; in essence,
train a model that predicts TA from PPFD_IN and vice-versa.

In addition, train another model that uses PPFD_IN and TA to predict FC. Now, randomly sample points from the first model, by
inserting PPFD_IN values and getting TA values, or vice-versa, and inserting them in the 2nd model, and seeing the predicted
FC.
