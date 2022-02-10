# Sabified's Github Page!
[Link](https://sabified.github.io)

You can find my profile [here](https://github.com/Sabified/) and look at my repositories.

### Greetings

Simple greeting function in python!

```markdown
def greeting(text):
    print(text)
    
greeting("Hello!")

> Hello!
```



# Repositories
## main.py in tokenlister
[Repository Link](https://github.com/Sabified/tokenlister/)
```markdown
TOKENS = {
    "0": "ZERO",
    "1": "ONE"
}
T_UNKNOWN = "UNKNOWN"
tokens = []
def apply_tokens(string):
    current_character = 0
    for char in string:
        if char in TOKENS:
            tokens.append(TOKENS[char])
        else:
            print("Unknown Character: \'" + char + "\' Character " + str(current_character + 1))
            tokens.append(T_UNKNOWN)
        current_character += 1
    print(tokens)
test_string = "0102"
apply_tokens(test_string)

< Output: Unknown Character: '2' Character 4
['ZERO', 'ONE', 'ZERO', 'UNKNOWN']>
```
## WeaponSimulator
[Repository Link](https://github.com/Sabified/WeaponSimulator/tree/making)
[On Launch](https://prnt.sc/26t0nci)
 
[When clicked on p2 and damage](https://prnt.sc/26t0klo)

## XpSystem
[Repository Link](https://github.com/Sabified/XPSystem)
[On Launch](https://prnt.sc/26t0qtu)
[When clicked on get xp many times](https://prnt.sc/26t0rrw)

## Support or Contact

[Reddit](https://www.reddit.com/user/SabifiedSab)
