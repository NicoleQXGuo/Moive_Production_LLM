We used few-shot prompting by adding context, roles and rules. Achieved 96% accuracy after iterative updates. Then built a machine learning model for box office prediction, involving preprocessing, feature engineering, hyperparameter tuning, and ensemble. The final model achieved an RMSE of 1.1.

Finally, we implemented similarity search to connect front-end with back-end using cosine similarity. Backend retrieves movies most similar to input from the database, feeds their features into the prediction model, and outputs predicted box office results and casting recommendation list on the UI.

You can input their movie script draft, and our chatbot will provide you with box office prediction, budget prediction and recommended casts.
