# SYTHETIC-DATA-GENERATION-USING-GAN-S
"Engineered a privacy-preserving Generative AI solution using CTGAN/WGAN to synthesize high-fidelity operational data for SCADA systems, enabling robust anomaly detection research."
Synthetic Data Generation for SCADA Systems (CTGAN/WGAN)
This project solves the challenge of generating high-fidelity, production-ready data for security analysis when real operational data is too sensitive to share.

1. Problem Statement 
Critical infrastructure, managed by SCADA systems, produces highly sensitive data required for cybersecurity research and anomaly detection model training. Due to stringent operational privacy and national security concerns, this data cannot be shared publicly. This creates a severe research bottleneck, as developers lack the large, diverse, and realistic datasets needed to build and validate new security products.

2. Technical Solution 
We engineered a sophisticated deep generative model combining CTGAN (Conditional Tabular Generative Adversarial Network) and WGAN (Wasserstein GAN) architectures. This model learns the complex multivariate statistical and temporal dependencies within SCADA data, allowing it to produce large volumes of synthetic data that accurately mimics the real system's behavior, thereby ensuring high fidelity without compromising privacy.

3. Business Case 
The solution enables risk mitigation and product commercialization. By generating safe, non-sensitive data, the project allows security firms, external researchers, and internal teams to develop and rigorously test high-accuracy anomaly detection models against realistic scenarios. This accelerates the development of commercial cybersecurity products and improves infrastructure resilience.



# Synthetic Data Generation with a Hybrid GAN

Ever needed more data to train a machine learning model but couldn't get it? This project is a little showcase of how we can create realistic, synthetic (aka "fake") data using a cool mix of two AI techniques: **CTGAN** and **WGAN**.

We're pretending we have data from industrial machines (temperature, pressure, etc.) and we want to create more of it, maybe to train a model that predicts when a machine might fail.

### What's Inside?

* **`synthetic_data_generation.ipynb`**: This is where all the magic happens! It's a Jupyter Notebook that walks you through the whole process, from creating our initial "real" data to training two different GANs and visualizing the results.
* **`requirements.txt`**: A simple list of the Python libraries you'll need to run the notebook.

### How to Run It

It's pretty straightforward. You'll need Python and Pip installed.

1.  **Clone this repo:**
    ```bash
    git clone <repository-url>
    cd Synthetic_Data_Showcase
    ```

2.  **Set up a virtual environment (always a good idea!):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install the necessary libraries:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch Jupyter and have fun!**
    ```bash
    jupyter notebook
    ```
    Now, just open `synthetic_data_generation.ipynb` and run the cells from top to bottom. Enjoy the show!
