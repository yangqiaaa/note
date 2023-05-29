# 1 install
```
sudo apt-get install nodejs
sudo apt-get install npm

node -v
npm -v

npm install -g hexo-cli
```

# 2 build 
```
cd blog-dir
hexo init myblog
cd myblog //进入这个myblog文件夹
npm install

node_modules: 依赖包
public：存放生成的页面
scaffolds：生成文章的一些模板
source：用来存放你的文章
themes：主题
** _config.yml: 博客的配置文件**
```

# 3 start
```
hexo g
hexo server
```

# 4 git
```
git config --global user.name "yourname"
git config --global user.email "youremail"

git config user.name
git config user.email

ssh-keygen -t rsa -C "youremail"

add key to github

ssh -T git@github.com
```

# 5 cfg
```
deploy:
  type: git
  repo: https://github.com/YourgithubName/YourgithubName.github.io.git
  branch: master


npm install hexo-deployer-git --save

hexo clean
hexo generate
hexo deploy

hexo clean清除了你之前生成的东西，也可以不加。可以用 hexo cl缩写
hexo generate 顾名思义，生成静态文章，可以用 hexo g缩写
hexo deploy 部署文章，可以用hexo d缩写
```

# 6 themes next
```
cd 博客根目录

git clone https://github.com/iissnan/hexo-theme-next themes/next


_config.yml

theme: next

```

