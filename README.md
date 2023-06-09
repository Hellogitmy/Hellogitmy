- 👋 Hi, I’m @Hellogitmy
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Hellogitmy/Hellogitmy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---def scrabble_score(word):

    letter_values = {

        'a': 1, 'b': 3, 'c': 3, 'd': 2, 'e': 1, 'f': 4, 'g': 2, 'h': 4,

        'i': 1, 'j': 8, 'k': 5, 'l': 1, 'm': 3, 'n': 1, 'o': 1, 'p': 3,

        'q': 10, 'r': 1, 's': 1, 't': 1, 'u': 1, 'v': 4, 'w': 4, 'x': 8,

        'y': 4, 'z': 10

    }

    score = 0

    for letter in word:

        letter = letter.lower()

        score += letter_values.get(letter, 0)

    return score

# Test the function

word = input("Enter a word: ")

score = scrabble_score(word)

print("Scrabble score of", word, "is", score)
