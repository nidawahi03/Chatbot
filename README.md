# chatbot
def chatbot():
    print("Hello! I'm ChatBot. Type 'quit' to exit.")
    
    while True:
        user_input = input("You: ").lower()

        if user_input == 'quit':
            print("ChatBot: Goodbye!")
            break
        elif 'hello' in user_input or 'hi' in user_input:
            print("ChatBot: Hi there! How can I help you today?")
        elif 'how are you' in user_input:
            print("ChatBot: I'm just a bunch of code, but thanks for asking!")
        elif 'what is your name' in user_input:
            print("ChatBot: I'm called ChatBot. Nice to meet you!")
        elif 'help' in user_input:
            print("ChatBot: Sure! What do you need help with?")
        else:
            print("ChatBot: I'm not sure how to respond to that.")

if __name__ == "__main__":
    chatbot()
