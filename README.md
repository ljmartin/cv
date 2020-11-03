# cv
my cv in markdown / pandoc

see https://blog.chmd.fr/editing-a-cv-in-markdown-with-pandoc.html

# example:

![text](./Screen Shot 2020-11-03 at 12.13.12 pm.png)

to build:
```
pandoc --standalone --from markdown --to html -o index.html index.md
```
