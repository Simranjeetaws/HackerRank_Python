### SWAP CASE


#### SOLUTION 1
```
def swap_case(s):
    
    return s.swapcase()

if __name__ == '__main__':
    s = input()
    result = swap_case(s)
    print(result)

```

#### SOLUTION 2

```
def swap_case(s):
    swapped = ""
    for c in s:
        if c.islower():
            swapped = swapped + c.upper()
        elif c.isupper():
            swapped = swapped + c.lower()
            
        else:
            swapped = swapped + c
    return s.swapcase()

if __name__ == '__main__':
    s = input()
    result = swap_case(s)
    print(result)
```

