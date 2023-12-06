# Spelling-Checker-NLP
Spelling Correction System using Edit Distance and Probability-Based Suggestions.

The main components of the code are as follows:

1. **Reading the Corpus:**
   - The `read_corpus` function reads a text file containing a corpus, tokenizes it into words, and converts them to lowercase.

2. **Basic Corpus Statistics:**
   - The total number of words and the number of unique words in the corpus are printed.

3. **Word Frequency:**
   - The frequency of a specific word (e.g., "the") is printed.

4. **Probability of Words:**
   - The probability of each word in the corpus is calculated based on its frequency.

5. **Edit Operations:**
   - Functions are defined for various edit operations on words, such as deletion, swapping, replacement, and insertion.

6. **Edit Distance:**
   - Functions `edit_dist1` and `edit_dist2` generate unique words at edit distances 1 and 2 from a given word.

7. **Spelling Correction:**
   - The `correct_spelling` function suggests corrections for misspelled words based on edit distances and word probabilities.

8. **Spelling Checker Class:**
   - The `spelling_Checker` class is defined to encapsulate the spelling checking functionality.
   - It initializes with a corpus file, computes word probabilities, and provides methods for checking the spelling of a word.

9. **Usage Example:**
   - An instance of the `spelling_Checker` class is created using a specific corpus file.

10. **Spellchecking:**
   - The `check` method of the `spelling_Checker` class is used to check the spelling of a given word, providing suggestions ranked by probability.

Overall, this code serves as a basic spelling correction system that suggests corrections for misspelled words based on edit distances and word probabilities from a given corpus. The code utilizes the NumPy library for array operations.
