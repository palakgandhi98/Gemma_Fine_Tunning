# Gemma Fine-Tuning 🔧

This project showcases how to fine-tune a language model using Google's Gemma model. The notebook includes steps for loading the model, tokenizing text, and fine-tuning it with the `peft` and `trl` libraries. 📚💻

## Table of Contents

- [Gemma Fine-Tuning 🔧](#gemma-fine-tuning-)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License 📜](#license-)
  - [Acknowledgments 🙏](#acknowledgments-)
  - [Contact 📧](#contact-)

## Prerequisites

Before starting, ensure you have the following:

- Python 3.7 🐍
- Access to Google Colab or a local Jupyter Notebook environment 📓
- A valid Hugging Face token for model access 🔐

## Installation

To run the notebook, you need to install the required libraries. Execute the following commands in a Jupyter Notebook cell:

```python
!pip3 install -q -U bitsandbytes==0.42.0
!pip3 install -q -U peft==0.8.2
!pip3 install -q -U trl==0.7.10
!pip3 install -q -U accelerate==0.27.1
!pip3 install -q -U datasets==2.17.0
!pip3 install -q -U transformers==4.38.0
```

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/palakgandhi98/Gemma_Fine_Tunning.git
   cd Gemma_Fine_Tunning
   ```

2. **Open the Notebook:**

   - If you are using Google Colab, you can open the notebook directly by clicking [here](https://colab.research.google.com/github/palakgandhi98/Gemma_Fine_Tunning/blob/main/Gemma_FineTunning.ipynb).
   - If you are using a local Jupyter Notebook environment, open the `Gemma_FineTunning.ipynb` file.

3. **Set Up Environment Variables:**

   Ensure you set your Hugging Face token as an environment variable:

   ```python
   import os
   from google.colab import userdata

   os.environ["HF_TOKEN"] = userdata.get('HF_TOKEN')
   ```

4. **Run the Notebook:**

   Follow the steps outlined in the notebook to load the model, tokenize text, and fine-tune it. The notebook includes:

   - Loading the Gemma model with 4-bit quantization. 🚀
   - Tokenizing sample text. 📝
   - Fine-tuning the model using the `Abirate/english_quotes` dataset. 📊
   - Generating text using the fine-tuned model. 📖

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request. 🤝

## License 📜

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
Distributed under the GPL-3.0 License. See `LICENSE` for more information.

## Acknowledgments 🙏

- Thanks to the developers of Streamlit and LangChain for their amazing libraries. 🌟
- Special thanks to the LLAMA2 model developers for their groundbreaking work. 🚀

## Contact 📧

- [![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff)](https://www.github.com/palakgandhi98)
- [![LinkedIn](https://img.shields.io/badge/Linkedin-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/palakgandhi98)

Let's build something amazing together! 🌟🚀
