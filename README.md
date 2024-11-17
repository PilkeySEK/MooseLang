# MooseLang
A silly language that moose-ifies everything that we can think of

**this project is far from finished, we are happy for every contributor!**

## Testing the lang

1. Make a zip (linux edition):
Run the following command in the root directory of the project:
```
zip -r MooseLang.zip . -x README.md -x ./.git/**\* -x ./.git/
```
then, copy the .zip into your resourcepacks folder:
```
cp MooseLang.zip <resourcepack folder>
```
You can also shorten this to only be one single command by using `&&`:
```
zip -r MooseLang.zip . -x README.md -x ./.git/**\* -x ./.git/ && cp MooseLang.zip <resourcepack folder>
```