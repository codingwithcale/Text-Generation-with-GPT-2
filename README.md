# Text Generator Using GPT-2

This project is a Python-based text generator that leverages the power of the GPT-2 model from Hugging Face's `transformers` library. It allows users to input a text prompt and receive AI-generated continuations, making it a great tool for creative writing, brainstorming, or exploring the capabilities of machine learning.

## Features
- Generate AI-driven text based on user-provided prompts.
- Customize the output length and number of variations.
- Easy to use with a command-line interface.

## Requirements
- Python 3.7 or higher
- `transformers` library (Install using `pip install transformers`)

## Installation
1. Clone the repository or download the `text_generator.py` file:
   ```bash
   git clone https://github.com/your-username/text-generator.git
   cd text-generator
   ```

2. Install the required library:
   ```bash
   pip install transformers
   ```

## Usage
1. Run the script:
   ```bash
   python text_generator.py
   ```

2. Follow the prompts:
   - Enter a text prompt for the AI to generate text.
   - Specify the maximum length for the generated text (default is 50).
   - Specify the number of variations to generate (default is 1).

3. View the AI-generated text.

### Example

**Input**:
```
Enter a prompt for the AI to generate text: Once upon a time in a futuristic city
Enter the maximum length for the generated text (default 50): 100
Enter the number of sequences to generate (default 1): 2
```

**Output**:
```
Generated Text:

Sequence 1:
Once upon a time in a futuristic city, a young inventor named Maya created a machine that could manipulate time itself. She...

Sequence 2:
Once upon a time in a futuristic city, robots and humans coexisted peacefully, until one day...
```

## Customization
You can modify the following parameters in the code:
- `max_length`: Set the maximum length for the generated text.
- `num_return_sequences`: Specify the number of generated text sequences.
