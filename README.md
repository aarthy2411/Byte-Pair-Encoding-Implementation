
# Byte Pair Encoding (BPE) Implementation

A Python implementation of the **Byte Pair Encoding (BPE)** algorithm from scratch. This project demonstrates how BPE works by iteratively merging the most frequent pairs of characters or bytes to create an efficient vocabulary for text tokenization.

Byte Pair Encoding is one of the most widely used tokenization techniques in modern Natural Language Processing (NLP) and Large Language Models (LLMs) such as GPT, RoBERTa, and BART.

---

##  Project Overview

This project aims to provide a simple and educational implementation of the Byte Pair Encoding algorithm. It explains how raw text is converted into meaningful subword tokens by repeatedly merging the most frequent adjacent symbol pairs.

The implementation is designed for students, beginners, and developers who want to understand the internal working of tokenization before using advanced NLP libraries.

---

##  Objectives

- Implement the Byte Pair Encoding algorithm from scratch.
- Learn how modern tokenizers generate subword vocabularies.
- Understand token merging and vocabulary creation.
- Demonstrate text encoding using BPE.
- Provide a beginner-friendly implementation without relying on external NLP libraries.

---

##  Features

- Pure Python implementation
- Easy-to-read and well-commented code
- Frequency-based pair merging
- Vocabulary generation
- Text tokenization
- Modular and reusable code

---

##  Technologies Used

- Python 3.x
- Standard Python Libraries
- Jupyter Notebook

---

##  Project Structure

```
Byte-Pair-Encoding-Implementation/
│
├── bpe.py             
├── input.txt           
├── output.txt          
├── README.md           
└── requirements.txt    
```

---

##  How It Works

The Byte Pair Encoding algorithm follows these steps:

1. Read the input text.
2. Split the text into characters or bytes.
3. Count the frequency of adjacent symbol pairs.
4. Identify the most frequent pair.
5. Merge that pair into a new token.
6. Update the vocabulary.
7. Repeat the process until the desired vocabulary size is reached.
8. Encode the text using the generated vocabulary.

---    
**System WorkFlow**
```
            Start
               │
               ▼
      Read Input Text
               │
               ▼
 Split Text into Individual Characters
               │
               ▼
 Count Frequency of Adjacent Symbol Pairs
               │
               ▼
 Find the Most Frequent Pair
               │
               ▼
 Merge the Selected Pair
               │
               ▼
 Update Vocabulary and Replace Pairs
               │
               ▼
 Check Vocabulary Size / Merge Limit
               │
      ┌────────┴────────┐
      │                 │
     No                Yes
      │                 │
      ▼                 ▼
 Repeat Merge      Generate Final
    Process        Vocabulary & Tokens
                         │
                         ▼
                  Display Encoded Output
                         │
                         ▼
                        End
```


##  Example

### Input

```
low lower newest widest
```

### Generated Merges

```
lo
low
er
est
```

### Output Tokens

```
low
lower
new
est
wid
est
```

---

##  Applications

Byte Pair Encoding is commonly used in:

- Natural Language Processing (NLP)
- Large Language Models (LLMs)
- Machine Translation
- Text Compression
- Chatbots
- Question Answering Systems
- Text Generation
- Information Retrieval

---

##  Future Enhancements

- Byte-level BPE implementation
- Interactive command-line interface
- Graphical visualization of merge operations
- Vocabulary export feature
- Support for larger datasets
- Performance optimization
- Integration with machine learning workflows

---



##  License

This project is intended for educational and learning purposes.

---

##  Author

**Aarthy.V**    
B.Sc.Computer Science with Artificial Intelligence
