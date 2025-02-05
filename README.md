# Word-Counter
def count_words(text):
    text = text.strip()           
    # Removes the white leading and trailing spaces
    words = text.split()         
    # Separate the text into words (each word becomes an element)
    return len(words)             
    # Returns the number of elements in the list "words"
    text = input("Enter the text: ")   
    # Accepting input from user
    word_count = count_words(text)     
  # Calling the function
 print("The number of words in the text is:", word_count)
