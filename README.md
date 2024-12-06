# Patch Attack Demo

This project demonstrates the implementation of Patch Attack on a deep learning model using the CIFAR-10 dataset. The notebook includes model training, adding patch-based triggers, and evaluating the model performance under adversarial conditions.

## Prerequisites

- Python 3.7 or higher
- CUDA-compatible GPU (optional but recommended)

## Installation Instructions

1. **Clone the Repository**
   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Create a Virtual Environment (Optional)**
   It is recommended to use a virtual environment to manage dependencies.
   ```sh
   python -m venv backdoor_env
   source backdoor_env/bin/activate  # On Windows, use `backdoor_env\Scripts\activate`
   ```

3. **Install Dependencies**
   Install the required Python libraries using the following command:
   ```sh
   pip install torch torchvision numpy matplotlib tqdm
   ```

## How to Run

1. **Start the Jupyter Notebook**
   ```sh
   jupyter notebook
   ```

2. **Open the Notebook**
   Open the provided notebook (`Backdoor Attacks (1).ipynb`) in your browser.

3. **Run the Notebook Cells**
   - Make sure to run each cell in sequence.
   - Training can take some time, especially if using a CPU. It is recommended to use a GPU if available.

## File Structure

- `Backdoor Attacks.ipynb`: The main notebook that demonstrates the backdoor attack process.

## Dependencies

- **PyTorch**: For defining and training deep learning models.
- **Torchvision**: To access and transform the CIFAR-10 dataset.
- **Numpy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **Tqdm**: For visualizing training progress with progress bars.

## Important Notes

- The project uses a backdoor attack mechanism where a small patch is applied to images in order to fool the trained model.
- The notebook demonstrates both training a clean model and then retraining it with poisoned data.
- For reproducibility, seeds are set to ensure consistent results.

## Example Usage

- Run the entire notebook to visualize the effect of backdoor attacks on the model.
- Experiment with different patch sizes and pixel values to observe their impact on the model's accuracy.


