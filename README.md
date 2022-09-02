1. Скачать и установить git https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git
2. Скачать и установить VSC https://code.visualstudio.com/ (особенно это касается владельцев mac'ов , установить, а не запустить из папки скаченных файлов)
3. С этого момента можете забыть о кириллице и пробелах в именах папок и файлов)


…or create a new repository on the command line;

echo "# 1" >> README.md;

git init;

git add README.md;

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/PabloMuertte/1.git

git push -u origin main


…or push an existing repository from the command line

git remote add origin https://github.com/PabloMuertte/1.git

git branch -M main

git push -u origin main

