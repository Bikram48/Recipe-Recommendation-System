# Recipe Recommender System

## Overview

The Recipe Recommender System is an NLP-based application that generates food recipes based on a list of input ingredients. The system is powered by a fine-tuned BART-base model trained on the RecipeNLG dataset. To make it accessible and user-friendly, we’ve integrated the functionality into a Telegram bot. Users can simply input ingredients into the bot and receive a detailed recipe in response.

---

## Getting Started

### Prerequisites

Before running the program, ensure you have the following:

- Python 3.x
- Google Colab account (recommended for running the model)
- Telegram Bot Token (for bot deployment)

---

### Steps to Run the Program

1. **Clone the Repository**  
   Clone this repository to your local system using the command:

   ```bash
   git clone https://github.com/Bikram48/Recipe-Recommendation-System.git

   ```

2. **Navigate to the Project Directory**
   ```bash
   cd Recipe-Recommendation-System
   ```
3. **Run the Jupyter Notebook in Google Colab**
   - Open the Google Colab.
   - Upload the notebook file from the repository to Colab.
   - Change the runtime to GPU:
     - Go to `Runtime > Change runtime type > Select GPU`.

Dataset Link - https://www.kaggle.com/datasets/paultimothymooney/recipenlg  
Colab Link - https://colab.research.google.com/drive/1KeTPg8Y0OhR2qNeQkEH3NTkU0yY82Qoo?usp=sharing  
Trained Model Link - https://drive.google.com/drive/folders/119u1MTvJ-dfcWHaO99Itz4lXMtxPmdFH?usp=sharing
