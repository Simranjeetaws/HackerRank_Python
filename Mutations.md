### Mutations


#### SOLUTION

```
def mutate_string(string, position, character):
    lst = list(s)
    lst[position] =  character
    string = ''.join(lst)
    return string

if __name__ == '__main__':
    s = input()
    i, c = input().split()
    s_new = mutate_string(s, int(i), c)
    print(s_new)

```
