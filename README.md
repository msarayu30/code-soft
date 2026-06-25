print("Welcome to ChatBot")
print("Type 'bye' to exit.")

while True:

    user = input("You: ").lower()

    if user == "hi":
        print("Bot: Hello!")

    elif user == "hello":
        print("Bot: Hi!")

    elif user == "how are you":
        print("Bot: I am fine.")

    elif user == "your name":
        print("Bot: I am RuleBot.")

    elif user == "bye":
        print("Bot: Goodbye!")
        break

    else:
        print("Bot: Sorry, I don't understand.")
