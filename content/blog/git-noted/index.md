---
title: Ghi Chú Về Git
date: "2019-02-19T08:47:05.284Z"
---

# Xoá tất cả branch ở Local, ngoại trừ branch 

```
git branch | grep -v "develop" | xargs git branch -D
```
