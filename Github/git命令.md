# 使用Github的命令和错误解决

## 创建一个新的git库

echo "# LearnOpenGL" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/BestDAHU/LearnOpenGL.git

git push -u origin main

## push一个已经存在的库

git remote add origin https://github.com/BestDAHU/LearnOpenGL.git

git branch -M main

git push -u origin main

## 更新库文件(已配置好的库)

git status

git add .

git commit -m "更新说明"

git push

## 远程拉取代码库

