## Running the Notebook

1. Install Jupyter: `pip install jupyter`
2. Start Jupyter: `jupyter notebook`
3. Open `phi_detector.ipynb`
4. Add your Groq API key in the first cell
5. Run all cells

## Notebook Contents
- Setup and imports
- PHI detection system implementation
- Live demonstration with sample text
- Performance analysis and visualization

## Add a cell at the top of your notebook:

# Configuration - Replace with your actual API key
GROQ_API_KEY = "your_groq_api_key_here"

# Alternatively, use environment variable:
import os
GROQ_API_KEY = os.getenv('GROQ_API_KEY', 'your_key_here')
