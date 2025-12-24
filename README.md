# Spell Checker and Dictionary Implementation 📝🔍

A C++ project that implements a spell-checker using efficient data structures to detect and correct common spelling errors.

## Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Implementation](#implementation)
* [Results](#results)
* [Future Work](#future-work)
* [License](#license)

## Project Overview

This project creates a spell-checker that can identify and correct common spelling mistakes using a hash table to store a dictionary of valid words. The spell checker can handle errors such as character swaps, insertions, deletions, and replacements.

Key components include:

* Efficient storage of dictionary words using a hash table.
* Spell-checking function capable of detecting common types of typos.
* Implementation in C++ with focus on performance and correctness.

## Features

* **Hash Table Dictionary:** Efficiently stores and searches a set of words.
* **Spell Check Function:** Checks spelling of a string and detects errors.
* **Error Handling:** Handles common misspellings including:

  * Swapping adjacent characters
  * Inserting a character
  * Deleting a character
  * Replacing a character

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/Spell-checker-and-dictionary-implementation-Data-Structures-and-Algorithms.git
cd Spell-checker-and-dictionary-implementation-Data-Structures-and-Algorithms

# Compile the C++ program
g++ Coding_Assignment_4_Q(1).cpp -o Coding_Assignment_4
```

## Usage

1. Run the spell checker:

```bash
./Coding_Assignment_4
```

2. Input a word or sentence to check spelling.
3. The program outputs suggestions or corrections for any detected spelling mistakes.
4. Edit the words.txt file to add or remove words

## Implementation

* **Data Structure:** Hash table for fast insertion and lookup of words.
* **Spell Checking Algorithm:** Compares input string with dictionary and applies transformations for common errors.
* **C++ Classes:** `SpellChecker` class encapsulates dictionary storage and spell-checking functionality.

## Results

* Successfully detects and suggests corrections for common misspellings.
* Efficient performance due to hash table-based dictionary.
* Handles multiple types of spelling errors in real-time.

## Future Work

* Extend to handle multi-word sentences with context-aware suggestions.
* Incorporate frequency-based ranking for suggested corrections.
* Add support for multiple languages and larger dictionaries.

## Citation

If you use this work, please cite:

```bibtex
@software{Spell-checker-and-dictionary-implementation-Data-Structures-and-Algorithms,
  author = {Shubhan Mital},
  title = {Spell checker and dictionary implementation Data Structures and Algorithms},
  year = {2025},
  url = https://github.com/Shubhanflash22/Spell-checker-and-dictionary-implementation-Data-Structures-and-Algorithms.git
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
