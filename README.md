
# Health Hub 

The healthcare recommendation system aims to provide personalized guidance by leveraging NLP and pre-trained language models like Mistral. It analyzes user-reported symptoms to generate tailored recommendations for suitable healthcare providers, beneficial food items, and corresponding recipes, promoting a holistic approach to well-being through fine-tuning powerful models on relevant healthcare data.


## Installation and Setup

### 1. Clone the repository:
    git clone https://github.com/nikitakanodia/Health-Hub_GGH-2024.git

### 2. Navigate to the project directory:
    cd Health-Hub_GGH-2024

### 3. Create a new virtual environment and activate it:
    python -m venv env
    source env/bin/activate #### On Windows, use `env\Scripts\activate`

### 4. Install the required dependencies:
    pip install -r requirements.txt

### 5. Model 
    The pre-trained Mistral model weights are included in the provided Jupyter notebook file. If you need to download the model separately, you can find the instructions for downloading the model in the official Anthropic documentation.

### 6. Dataset
    place datasets in 'data' directory
## Usage
    1. Start the application
        python app.py
    2. Access the application through CLI
    3. Input ingredients
    4. System will analyse them and suggest the recipe


## API and Libraries

### 1. Mistral
    The pre-trained language model developed by Anthropic

### 2. spaCy
    A popular NLP library for Python, used for text preprocessing tasks.

### 3. bitsandbytes
    A library for enabling efficient training and inference of large language models through quantization and other techniques.

### 4. simpletransformers
    A library providing a high-level interface for fine-tuning and evaluating pre-trained language models.