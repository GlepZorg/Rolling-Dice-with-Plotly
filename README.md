# Interactive Visualizations with Plotly

In this project, I use Plotly to produce interactive visualizations. Plotly is particularly useful for creating visualizations that will be displayed in a browser, as the visualizations automatically scale to fit the viewer’s screen. These visualizations are interactive; when users hover over certain elements, information about those elements is highlighted. I will build our initial visualization using Plotly Express, a subset of Plotly that focuses on generating plots with minimal code. Once the plot is verified, I customized the output.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Introduction

In this project, I analyze the results of rolling dice using Plotly to create interactive visualizations. By generating a dataset representing dice rolls, I can determine which numbers are most likely to occur. This project helps model games involving dice and applies to any game of chance, such as card games. The core ideas also relate to many real-world situations where randomness plays a significant factor.

## Features

- Generate interactive visualizations with Plotly.
- Analyze the results of rolling dice to determine probabilities.
- Customize visualizations for better clarity and aesthetics.
- Utilize Plotly Express for quick and efficient plotting.

## Installation

To get started with the Interactive Visualizations with Plotly project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/plotly-visualizations.git
   ```

2. Navigate to the project directory:

   ```bash
   cd plotly-visualizations
   ```

3. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the project and generate the interactive visualizations, use the following command:

```bash
python plot_dice_rolls.py
```

The resulting visualization will be displayed in your web browser, showing the interactive plot of dice roll results.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License.

## Credits

The Interactive Visualizations with Plotly project was created by Alexis Gonzalez. Special thanks to Eric Matthes for his book "Python Crash Course," which provided the foundation for this project.
