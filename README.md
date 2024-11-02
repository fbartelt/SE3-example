# SE(3) Vector Field Implementation

This repository provides a Python implementation and detailed explanation of the methodology for generating vector fields on the special Euclidean group, SE(3), as described in our paper, *"Constructive Vector Fields for Path Following in Matrix Lie Groups"* (see Section 4).

## Getting Started

### Running the Notebook

To view and run the provided notebook (`SE3example.ipynb`), you have two main options: using Google Colab or running it locally.

#### Option 1: Running on Google Colab

1. **Upload to Colab**: You can upload the notebook directly to Google Colab. Simply navigate to [Google Colab](https://colab.research.google.com/), select "File" > "Upload notebook," and choose `SE3example.ipynb` from your files.
2. **Install Requirements**: Once the notebook is open, run the initial cells to install any necessary libraries, if not already available in Colab.
3. **Execute Cells**: Follow along with each cell to see the methodology in action.

#### Option 2: Running Locally

1. **Clone the Repository**: First, download or clone this repository:

   ```bash
   git clone https://github.com/fbartelt/SE3-example.git
   ```

2. **Install Dependencies**: Once the notebook is open, you can run the initial cells to automatically install any necessary libraries. Alternatively, you can install the required packages manually by opening a terminal in the repository folder and using `pip`:

   ```bash
   pip install numpy scipy plotly
   ```

    This will install the essential packages: `numpy`, `scipy` and `plotly`

3. **Run the Notebook**: Open Jupyter Notebook by running:

    ```bash
    jupyter notebook SE3example.ipynb
    ```

4. **Execute Cells**: Follow along with each cell to see the methodology in action.

## 