# Useful_module
this reposeitory mainly contains some often used code module， such  as random, plot, txt, image_resize and so on.

## python part
* 1 获取一个字符串中某些元素的索引， 包括所有相同的元素. [参考资料](https://stackoverflow.com/questions/2294493/how-to-get-the-position-of-a-character-in-python)
```python
def get_index(string, character):
    print([pos for pos, char in enumerate(string) if char == character])
    
def main():
    a = 'sdgn_ksmdf_sdkg_dfsgm_sdgm_'
    get_index(string=a, character='_')
```

2 获取一个list中某个值的索引，包括相同元素
```
[i for i in range(len(mylist)) if mylist[i]==(A,3)]
```
