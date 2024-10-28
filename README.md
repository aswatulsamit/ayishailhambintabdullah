import time

def introduce_name(name):
    print("✨ Introducing... ✨")
    time.sleep(1)
    for char in name:
        print(char, end='', flush=True)
        time.sleep(0.1)  # Adds a slight delay between each character
    print("\n\nWelcome to my world!")

# Call the function with your name
introduce_name("Aswatul Samit")
