# Personalized Real Estate Agent

This is a project for the Udacity Artificial Intelligence Nanodegree. The goal of this project is to create a personalized real estate agent that uses AI techniques to help buyers find properties that match their preferences.

## Features
- A TXT file with 10 examples of Home descriptions: **Listings(.txt)**.
- A IPYNB file with step by step development called **HomeMatch_V2.ipynb**:
  - Generating realistic real estate listings using a Large Language Model (LLM).
  - Storing listing embeddings in a vector database.
  - Semantic search of listings based on buyer preferences.
  - Augmenting listing descriptions based on buyer preferences.
- A IPYNB file with final demo app with some adaptations to deployment environment called **home_match_app.ipynb**.
  - Run the application.  

## How to Run

1. Clone this repository to your local machine.
2. Make sure you have the necessary dependencies installed (listed in the requirements.txt file).
3. Run the main project file, for example, `main.py`.
4. Follow the instructions provided in the terminal to interact with the real estate agent.
5. Put your OpenAI Key to execute chatbot functions on **HomeMatch_V2.ipynb** and **home_match_app.ipynb**: os.environ['OPENAI_API_KEY']='PUT YOUR API KEY HERE'
6. Substitute URL on "loader = CSVLoader(**"/content/df_home_match.csv"**)" in **home_match_app.ipynb** to **Listings(.txt)** converted csv or take "Listings(.csv) instead".

## Prerequisites and Dependencies

- Python 3.7 or higher
- XYZ Library (version X.X.X)
- ...

## Contribution

This project was developed as part of the Udacity Artificial Intelligence Nanodegree, so external contributions are not expected. However, feel free to explore the code and adapt it to your own needs.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
