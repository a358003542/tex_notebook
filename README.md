## tex_notebook
用latex制作的一个个人笔记


## 制作epub

```
pandoc -o main.epub main.tex --metadata-file=epub.yaml --resource-path=figures
```