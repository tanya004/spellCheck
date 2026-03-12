\# 🔤 Spell Checker



> A fast, dictionary-based spell checker and word suggestion system built in C++.



\---



\## ✦ What it does



Ever mistyped a word and wished something would catch it? That's exactly what this does.



This program takes a word as input, checks it against a large dictionary, and if it's wrong — suggests the closest correct alternatives. Built entirely in C++ with a focus on efficiency and clean data structures.



\---



\## ✦ How it works



The core of this project is a \*\*Trie (prefix tree)\*\* — a data structure that makes word lookups blazing fast compared to scanning through a list.



```

Input word → Trie lookup → Found? ✓ Correct

&#x20;                        → Not found? → Generate suggestions → Output closest matches

```



\- \*\*Trie data structure\*\* for O(m) word lookup (m = word length)

\- \*\*File I/O\*\* to load and process large dictionary datasets

\- \*\*String manipulation\*\* to generate and rank suggestions

\- \*\*STL\*\* used throughout for clean, efficient code



\---



\## ✦ Features



\- ✅ Validates if a word is spelled correctly

\- 💡 Suggests similar words when spelling is wrong

\- ⚡ Fast prefix-based search using Trie

\- 📂 Loads dictionary from external file

\- 🧩 Modular, well-structured codebase



\---



\## ✦ Tech Stack



!\[C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge\&logo=c%2B%2B\&logoColor=white)



\- Language: \*\*C++\*\*

\- Data Structure: \*\*Trie (Prefix Tree)\*\*

\- Concepts: \*\*DSA, File I/O, String Algorithms, STL, Memory Management\*\*



\---



\## ✦ Getting Started



\### Prerequisites

\- A C++ compiler (g++ recommended)



\### Run it



```bash

\# Clone the repo

git clone https://github.com/tanya004/spellCheck.git

cd spellCheck/spellChecker



\# Compile

g++ -o spellchecker main.cpp



\# Run

./spellchecker

```



\---



\## ✦ Project Structure



```

spellCheck/

└── spellChecker/

&#x20;   ├── main.cpp          # Entry point

&#x20;   ├── trie.cpp/.h       # Trie implementation

&#x20;   └── dictionary.txt    # Word dataset

```



\---



\## ✦ Author



Made with way too much coffee ☕ by \*\*\[Tanya Singh](https://github.com/tanya004)\*\*

