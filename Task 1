class RuleBasedChatbot:
    def __init__(self):
        self.rules = {
            "hello": "Hi there! How can I help you today?",
            "bye": "Goodbye! Have a great day!",
            "how are you": "I'm just a bot, but I'm doing fine! How about you?",
            "name": "I am a rule-based chatbot created to assist you.",
            "help": "Sure, I am here to help! What do you need assistance with?",
            # Add more rules as needed
        }

    def get_response(self, user_input):
        user_input = user_input.lower()
        for key in self.rules:
            if key in user_input:
                return self.rules[key]
        return "I'm sorry, I don't understand that."

def main():
    bot = RuleBasedChatbot()
    print("Welcome to the Rule-Based Chatbot. Type 'bye' to exit.")
    while True:
        user_input = input("You: ")
        if user_input.lower() == "bye":
            print("Chatbot: Goodbye! Have a great day!")
            break
        response = bot.get_response(user_input)
        print(f"Chatbot: {response}")

if __name__ == "__main__":
    main()
