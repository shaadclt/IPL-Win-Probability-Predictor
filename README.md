# IPL Win Probability Predictor

The IPL Win Probability Predictor is a web application built using Streamlit. It uses a machine learning model to predict the probability of a team winning an IPL match based on various factors such as batting team, bowling team, host city, target, score, overs completed, and wickets.

## Getting Started

To run the IPL Win Predictor locally, follow these steps:

1. Clone the repository: `git clone https://github.com/shaadclt/Ipl-Win-Probability-Predictor.git`
2. Navigate to the project directory: `cd Ipl-Win-Probability-Predictor`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the application: `streamlit run app.py`

## Usage

1. Select the batting team from the dropdown menu.
2. Select the bowling team from the dropdown menu.
3. Select the host city from the dropdown menu.
4. Enter the target score.
5. Enter the current score, overs completed, and wickets out.
6. Click on the "Predict Probability" button to see the predicted win probability for each team.

## Model

The IPL Win Probability Predictor uses a pre-trained machine learning model that has been trained on historical IPL match data. The model is loaded using pickle and predicts the win probability based on the input provided.

## Dataset

The model has been trained on a dataset that includes information about IPL matches, such as teams, cities, scores, and other relevant features. Unfortunately, the dataset is not provided in this repository, but you can create your own dataset or use publicly available IPL match datasets for training your own model.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request. Make sure to follow the existing code style and guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or inquiries, please feel free to reach out to [shaadclt@gmail.com].

---

Thank you for using the IPL Win Predictor! Have fun predicting the outcomes of IPL matches and enjoy the cricket season!
