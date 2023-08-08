The code that returns the flag seems (at first sight) to be correct. However in the main menu, it seems that someone forgot to include it.

We just added the call to the function on the b) option, and re-run the program.

```python
 elif choice == 'b':
      print_flag()
```

```python
What would you like to do? (a/b/c) b
picoCTF{7h3_r04d_l355_7r4v3l3d_ae0b80bd}
```
