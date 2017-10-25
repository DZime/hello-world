# hello-world
python
7.6 exercise
comma = ","
print("Enter input string:")
string = input()
while string != "q":
    if comma in string:
        firstWord = string.split(",")[0]
        secondWord = string.split(",")[1]
        print("First word:", firstWord)
        print("Second word:", secondWord)
    else:
        print("Error: No comma in string.")
    print("Enter input string:")
    string = input()


