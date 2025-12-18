# SIMD Packing in BGV/BFV FHE Schemes

This project contains the Python code and Jupyter notebooks associated with my article on [SIMD Packing in BGV/BFV FHE Schemes](https://ahmadalbadawi.com/posts/2025/12/simd-packing-bgv-bfv-fhe/).

## Description

The notebooks demonstrate the principles of SIMD (Single Instruction, Multiple Data) packing used in the BGV and BFV fully homomorphic encryption schemes.

- `poly_arithmetic_review.ipynb`: A review of the basic polynomial arithmetic.
- `bgv_bfv_poly_arithmetic.ipynb`: An illustration of SIMD packing for integer vector arithmetic in BGV and BFV schemes.

## Getting Started

### Prerequisites

- Python 3

### Installation

1.  Clone the repository or download the code.
2.  Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
3.  Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Notebooks

1.  Start the Jupyter server:
    ```bash
    jupyter notebook
    ```
2.  Open the `.ipynb` files in your browser to view and run the code.

## Tested Environment

This code was tested on the following system:

-   **Operating System:** Ubuntu 24.04
-   **Python version:** Python 3.13.5