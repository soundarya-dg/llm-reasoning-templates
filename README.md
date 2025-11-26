# Prompting Techniques with Groq API

This project showcases various prompting techniques for large language models using the Groq API. Each technique is explained and implemented in a separate notebook cell, making it easy to understand and experiment with different approaches.

## Prompting Techniques

1. **Zero-Shot Prompting** - Direct task execution without examples
2. **One-Shot Prompting** - Learning from a single example
3. **Few-Shot Prompting** - Learning from multiple examples
4. **Role Prompting** - Assigning specific roles to the model
5. **Step-based Prompting** - Sequential logical reasoning
6. **Chain-of-Thought Prompting** - Explicit reasoning process
7. **Step-back Prompting** - Big-picture analysis first
8. **Self-Correction Prompting** - Self-review and improvement
9. **Deliberate Reasoning Prompting** - Multiple viewpoint consideration
10. **DSP (Directional Stimulus Prompting)** - Guided reasoning patterns
11. **ReAct Prompting** - Separating thought and action

## Prerequisites

- Python 3.9 or higher
- Jupyter Notebook or JupyterLab
- A Groq API key (free tier available)

## Configuration & Installation

1. **Get your Groq API key:**
   - Visit [Groq Console](https://console.groq.com/)
   - Sign up for a free account or log in
   - Navigate to API Keys section
   - Create a new API key

2. **Create a `.env` file:**
   
   In the project root directory, create a file named `.env`. Open the `.env` file and add:
   ```
   GROQ_API_KEY=your_actual_api_key_here
   ```
   
   Replace `your_actual_api_key_here` with the API key you obtained from Groq Console.

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open the notebook:**
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - In your browser, navigate to and open `prompting_techniques.ipynb`

5. **Run the cells:**
   - Begin with the first cell (Import Libraries)
   - Run the second cell to load your API key and initialize the Groq client
   - Execute any of the prompting technique cells
   - Each cell will prompt you for input and display the generated output

## Project Structure

```
groq/
├── prompting_techniques.ipynb    # Main notebook with all techniques
├── requirements.txt              # Python dependencies
├── .env                          # API key configuration (create this)
├── README.md                     
```
