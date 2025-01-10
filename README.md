# Spelling Checker Program

This is a Python program with a graphical user interface (GUI) built using **Tkinter**. 
The program takes user input text, checks for spelling errors using **TextBlob**, and provides the corrected text.

## Features
- Accepts input text with potential spelling errors.
- Corrects spelling using the **TextBlob** library.
- Displays the corrected text in a separate field.
- Simple and user-friendly GUI created with **Tkinter**.

## How to Use
1. Install the required Python libraries:
   - **TextBlob**: Install it using `pip install textblob`.
   - You may also need to download TextBlob's corpora by running:
     ```python
     python -m textblob.download_corpora
     ```
2. Run the program in a Python interpreter.
3. Enter the text with incorrect spelling in the "Incorrect Spelling" field.
4. Click the **Done** button.
5. The corrected spelling will appear in the "Correct Spelling" field.

### Example
#### GUI Screenshot:
![image](https://github.com/user-attachments/assets/50a4268c-cb4b-4933-8eb0-6276eb5bde77)


#### Input:
```
wrang
```
#### Output:
```
wrong
```

