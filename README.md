

# Penguin Species Predictor


Penguin Species Predictor is a Python application built with the tkinter GUI library that allows users to predict the species of a penguin based on its bill length, bill depth, and flipper length. It uses a pre-trained Random Forest Classifier for prediction.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine.

2. Install the required dependencies. You may need to install Python and the following Python libraries if you haven't already:

   - tkinter
   - PIL (Pillow)
   - pandas
   - scikit-learn
   - joblib

   You can install these libraries using pip:

```
pip install tkinter pillow pandas scikit-learn joblib
```

3. Place your dataset CSV file (e.g., 'Penguins.csv') in the repository directory.

4. Run the application by executing the main script:

```
python main.py
```

## Usage

1. Launch the application by running `main.py`.

2. The main screen displays a brief introduction to penguins and allows users to scroll through the text.

3. Click the "LOG IN" button to access the login screen.

4. Enter the following credentials to log in:
   - E-MAIL: ml@gmail.com
   - PASSWORD: 123

   You can change the credentials in the code.

5. After successful login, you will be directed to the penguin species prediction screen. Enter the bill length, bill depth, and flipper length, and click "CLICK TO PREDICT."

6. The predicted penguin species will be displayed on the screen.

7. To exit the application, close the main window.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a Pull Request from your fork to the main repository.

We welcome contributions and bug reports!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

