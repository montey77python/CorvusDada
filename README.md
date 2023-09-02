import os

file = open('./vercel.json', 'r')
str = file.read()
file = open('./vercel.json', 'w')

str = str.replace('"maxDuration": 10', '"maxDuration": 30')

file.write(str)
file.close()# CorvusDada
Create deploy-prep.yml

* Create deploy-prep.py

* Update vercel.json

* Update deploy-prep.yml

* Update vercel.json

* Added coauthor

Co-authored-by: Dou Xiaobo <93511091+douxiaobo@users.noreply.github.com>

* Update deploy-prep.yml

* refactor: format code

* Added if condition to disable deployments on forks

Co-authored-by: Rick Staa <rick.staa@outlook.com>

* Update deploy-prep.yml

Co-authored-by: Dou Xiaobo <93511091+douxiaobo@users.noreply.github.com>
Co-authored-by: Anurag Hazra <hazru.anurag@gmail.com>
Co-authored-by: rickstaa <rick.staa@outlook.com>

