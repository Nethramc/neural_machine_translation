# Real-Time Language Translation (NMT)

This is a simple **Streamlit-based application** for real-time language translation using **Neural Machine Translation (NMT)**.

## Features

- Supports **multiple language translations**.
- Uses a dataset for **quick lookups**.
- Falls back to **Hugging Face transformer models** if no dataset match is found.
- **Simple and user-friendly web interface** for easy interaction.

## Installation

To install the required dependencies, run:

```bash
pip install streamlit transformers torch pandas
```

## Run the App

To start the application, execute:

```bash
streamlit run app.py
```

## Files

- **app.py** - Main Streamlit app for language translation.
- **translation\_dataset.csv** - Preloaded dataset for multilingual translations.
- **README.md** - Project documentation.

## How It Works

1. **User Input**: The user enters text in one language.
2. **Model Processing**: The app checks the dataset for a quick lookup.
3. **Fallback to Transformer Model**: If no match is found, it uses a **Hugging Face NMT model** to generate translations.
4. **Output**: The translated text is displayed in the app.

## Technologies Used

- **Streamlit**: For building the user-friendly interface.
- **Hugging Face Transformers**: For real-time neural machine translation.
- **PyTorch**: For deep learning model execution.
- **Pandas**: For dataset handling.



