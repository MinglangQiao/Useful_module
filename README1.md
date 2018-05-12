* 1 获取一个字符串中某些元素的索引， 包括所有相同的元素. [参考资料](https://stackoverflow.com/questions/2294493/how-to-get-the-position-of-a-character-in-python)
```python
def get_index(string, character):
    print([pos for pos, char in enumerate(string) if char == character])
    
def main():
    a = 'sdgn_ksmdf_sdkg_dfsgm_sdgm_'
    get_index(string=a, character='_')
```
