# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with single quotation (')

### Backtick location on keyboard

- Make note of where the backtick button is located.
- It should appear above the tab key, but it may vary based on your keyboard layout.

<img width="200px" src="https://saplingai.zendesk.com/hc/article_attachments/360067410394/backtick.png" />
  
```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number
num = int(input("Enter a number: "))

# Check if the input is non-negative
if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```

- When you can you should attempt to apply snytax highlighting to your codeblocks

```Python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number
num = int(input("Enter a number: "))

# Check if the input is non-negative
if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```Python
# This code contains a deliberate NameError
def print_message():
    print(unknown_variable)

# Call the function
print_message()
```

> Here is an example of using a codeblock for an error that appears in Python.

## Step 2 - How to take screenshots

A screenshot is when you capture a part of you screen from your laptop desktop or phone.

This is not to be confused with taking a photo with your phone.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - User Emojis (Optional)

Github Flavoured Markdown supports emoji shortcodes.

Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Speak No Evil | `:speak_no_evil:` | 🙊

## Step 5 How to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Speak No Evil | `:speak_no_evil:` | 🙊
```

### Location of the Pipe character on a keyboard

- It may vary based on your keyboard layout.
  
<img width="400px" src="https://forums.macrumors.com/attachments/applekeyalw-xlarge-jpg.285310/" />

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

## External References
- [Github Flavored Markdown Spec](https://github.github.com/gfm/)
- [https://docs.github.com/en](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM Task List](https://github.github.com/gfm/#task-list-items-extension-) <sup>[1]</sup>
- [GFM Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM Tables (with Extension)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
