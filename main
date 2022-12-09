def get_text():
    with open("text.txt", "r") as f:
        a = f.readlines()
        for i1, i in enumerate(a):
            if "\n" in i:
                a[i1] = i[:-1]
        return a


def ans(text, a):
    for i1, i in enumerate(text):
        text[i1] = i.split(" ")
    for i in text:
        if int(i[1]) > a:
            print(f"час - {i[0]} параметр - {i[1]}")


def ui():
    while True:
        a = input("Введіть параметр AAA -> ")
        if a.isdigit():
            ans(get_text(), int(a))
            break
        else:
            print("Введіть тільки числа, не букви!\n")


def main():
    ui()


if __name__ == '__main__':
    main()
