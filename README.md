# Superhero-Name-Generator

This project is a guided implementation of a neural network trained on a dataset of superhero names to generate new, similar names. With over 9000 names from various comics, TV shows, and movies, the model learns to predict the next character in a sequence, gradually building new superhero names.

## Implementation:

-- Utilizes Python for programming
-- TensorFlow for building and training the neural network

**How to Use:**

1. **Clone the Repository:**
   - Clone the repository to your local machine using the following command:
     ```
     git clone https://github.com/tmittala/superhero-name-generator.git
     ```

2. **Navigate to the Notebook:**
   - Open the `Superhero_Name_Generator_Learner.ipynb` notebook in Jupyter Notebook or Google Colab.

3. **Run the Notebook:**
   - Execute all cells in the notebook to load the dataset, build the model, and train it on the superhero names.

4. **Generate New Superhero Names:**
   - To generate new superhero names, locate the cell containing the `generate_names` function.
   - Enter a seed input (e.g., a single character or a short sequence of characters) inside the function, like so:
     ```python
     generate_names('seed')
     ```
   - Run the cell to generate new superhero names based on the provided seed. Repeat this step with different seeds to explore a variety of generated names.
