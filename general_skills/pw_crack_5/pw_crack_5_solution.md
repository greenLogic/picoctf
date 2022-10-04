The dictionary of passwords is open and read separated by lines, and stripped of whitespaces:

```python
dictionary = open('dictionary.txt','r')
dictionary_ps = dictionary.readlines()

for ps in dictionary_ps:
    level_5_pw_check(ps.strip())
```

The message inside `level_5_pw_check` that warns us about an incorrect password is removed to just print the flag.

```python
Welcome back... your flag, user:
picoCTF{h45h_sl1ng1ng_fffcda23}
```
