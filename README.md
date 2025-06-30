# Diabetics Prediction

This is a simple Diabetics Prediction project featuring a Flask web app and a trained machine learning model. The app provides a user-friendly web interface to predict the likelihood of diabetes based on user input.

## Features

- Machine learning model for diabetes prediction
- Web application using Flask
- Jupyter Notebook for model training and evaluation
- Clean and interactive HTML frontend

<## Demo>

<!-- Optionally add a screenshot here -->
<!-- ![Demo Screenshot](screenshot.png) -->

## Tech Stack

- **Jupyter Notebook** (for model development & training)
- **Python** (scikit-learn, pandas, etc.)
- **Flask** (web framework)
- **HTML** (frontend interface)

## Getting Started

### Prerequisites

- Python 3.x
- pip

### Installation

1. **Clone this repository**
    ```bash
    git clone https://github.com/GirishSonune/Diabetics-Prediction.git
    cd Diabetics-Prediction
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```
    *If `requirements.txt` is missing, install Flask, pandas, scikit-learn manually.*

3. **Train the Model (optional)**
    - Open and run the Jupyter Notebook to train and export the model.

4. **Run the Flask App**
    ```bash
    python app.py
    ```
    - Visit `http://127.0.0.1:5000/` in your web browser.

## Usage

- Fill in the required medical information in the web form.
- Click submit to receive your diabetes prediction.

## Project Structure
```bash
├── app.py                  # Flask web application
├── model.pkl               # Trained ML model (generated after training)
├── templates/
│   └── index.html          # Web interface
├── Diabetics_Prediction.ipynb  # Jupyter Notebook for model development
├── requirements.txt        # Python dependencies
└── README.md
```


## Contributing

Contributions are welcome!  
Open an issue or submit a pull request for suggestions or improvements.

## License

This project is licensed under the MIT License.

## Contact

For questions, contact [Girish Sonune](https://github.com/GirishSonune).
