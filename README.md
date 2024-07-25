# Algorithm: Read a Sentence

## Description

This algorithm reads a sentence from the user and performs the following tasks:

1. Calculates the length of the sentence.
2. Counts the number of words in the sentence.
3. Counts the number of vowels (a, e, i, o, u) in the sentence.

## Variables

- `sentence` (STRING): The input sentence provided by the user.
- `sentence_length` (INTEGER): Length of the input sentence.
- `spaces_count` (INTEGER): Number of spaces in the sentence.
- `word_count` (INTEGER): Number of words in the sentence.
- `vowel_count` (INTEGER): Number of vowels in the sentence.

## Steps

1. **Read the Sentence:**

   - Input the sentence from the user.

2. **Calculate Sentence Length:**

   - Use `sentence.length` to get the length of the sentence.

3. **Count the Number of Words:**

   - Iterate through each character of the sentence.
   - Increment `spaces_count` for each space found.
   - Calculate `word_count` as `spaces_count + 1`.

4. **Count the Number of Vowels:**

   - Iterate through each character of the sentence.
   - Increment `vowel_count` for each vowel found (a, e, i, o, u).

5. **Output Results:**
   - Print the `sentence_length`.
   - Print the `word_count`.
   - Print the `vowel_count`.

## Example

If the input sentence is:
