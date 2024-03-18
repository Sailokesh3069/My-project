# My-project
def count_words(text):
    # Split the text into words based on whitespace
    words = text.split()
    # Count the number of words
    word_count = len(words)
    return word_count

def main():
    # Prompt the user to enter a sentence or paragraph
    user_input = input("Enter a sentence or paragraph: ")

    # Check if the input is empty
    if not user_input.strip():
        print("Error: Empty input. Please enter some text.")
        return

    # Call the function to count words
    words_count = count_words(user_input)

    # Display the word count
    print("Word count:", words_count)

if _name_ == "_main_":
    main()

https://github.com/Sailokesh3069/My-project/assets/162870856/2da6e83c-a391-4798-8aa7-68c38f7fcdad

