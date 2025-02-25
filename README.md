# Data Analysis with Python

Welcome to **Data Analysis with Python**! This project contains Jupyter notebooks designed to teach and demonstrate how to effectively use Python for data analysis. Topics covered include data cleaning, exploratory data analysis, data visualization, and more, using powerful Python libraries like Pandas, NumPy, and Matplotlib.

## Contents

- **Notebooks**: A series of Jupyter notebooks guiding you through various aspects of data analysis with Python.
- **Environment setup**: Guidance for running these notebooks in multiple environments (locally, Codespaces, and Google Colab).

## Running the Jupyter Notebooks

You can run the notebooks in several ways, depending on your preferences and setup:

### 1. Running Locally

To run the notebooks locally, you will need to create a virtual environment and install the necessary dependencies.

1. Clone the repository:
   ```sh
   git clone git@github.com:mattharrison/CS65.git
   cd CS65
   ```

2. Set up the environment using `uv`:

   Mac/Linux:
   ```sh
   $ curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
   Windows:
   ```cmd
   > powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
   ```

   The run:
   ```
   uv sync
   ```

   The above commands will create a virtual environment, activate it, and install dependencies.

4. Start Jupyter Notebook:
   ```sh
   uv run jupyter notebook
   ```

### 2. Running on GitHub Codespaces

GitHub Codespaces allows you to run this project entirely in the cloud without needing to set up a local environment.

1. Open the GitHub repository in your browser.
2. Click the **Code** button and select **Open with Codespaces**.
3. After the Codespace launches, wait for it to install the environment.
4. Click on the notebook and select the local kernel.

The project is pre-configured to install the necessary dependencies when the Codespace is first created.

### 3. Running on Google Colab

You can also run the notebooks on Google Colab, which provides free GPU/TPU resources for faster computations.

1. Open the repository on GitHub.
2. Navigate to the desired Jupyter notebook file (ending in `.ipynb`).
3. Update the domain from `github.com` to `githubtocolab.com`
4. Once in Colab, you may need to run the first cell to install any required dependencies.

## Dependencies

This project uses Python 3.9+ and relies on the following main libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

To see the complete list of dependencies, please check the `pyproject.toml` file.

## Suggested Reading

To deepen your understanding of Python for data analysis, we recommend the following books:

- [*Learning Python for Data*](https://store.metasnake.com/learningpy): This book provides a comprehensive introduction to Python, with a focus on its applications in data analysis. It covers Python fundamentals, essential libraries, and practical examples to help you get started with data-driven projects.

- [*Effective Pandas 2*](https://store.metasnake.com/effective-pandas-book): A guide to mastering data manipulation and analysis with Pandas. This book focuses on efficient workflows, advanced features, and best practices for using Pandas to analyze data

- [*Effective Visualization*](https://store.metasnake.com/effective-viz): Learn to apply the CLEAR process and tell stories with your Python plots.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have suggestions, improvements, or additional notebooks to add.

## License

This project is licensed under the MIT License. 

## Contact

If you have any questions, feel free to reach out or open an issue on the repository.

