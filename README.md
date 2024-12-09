def main():
    while True:
        try:

            user_input = input("Введіть число: ")
            number = int(user_input)
            result = 10 / number
            print(f"Результат: {result}")
        except Exception as e:
            print(f"Виникла помилка: {e}")
        finally:
            print("Продовжуємо роботу програми...\n")

if __name__ == "__main__":
    main()
