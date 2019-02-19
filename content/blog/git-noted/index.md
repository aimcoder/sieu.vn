# Xoá tất cả branch ở Local, ngoại trừ branch 

```
git branch | grep -v "develop" | xargs git branch -D
```
