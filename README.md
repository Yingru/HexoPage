# Build a website using Hexo

## 1. preparation
- install npm
- install hexo
```
sudo npm install hexo
```

## 2. [start a new website](https://hexo.io/docs/setup)
```
cd folder/
npx hexo init HexoPage
cd HexoPag/
npm install
```
once initialized, here is the folder looks like:
```
.
├── _config.yml    # configure most settings here
├── package.json   # application data. EJS, Stylus and Markdown renders are installed by default
├── scaffolds      # when a new post created, hexo bases the new file o the scaffold
├── source         # source folder. (ignore hidden files and folders names starts with "_" except "_posts"
|   ├── _drafts
|   └── _posts
└── themes
```


## 3. [work on config/themes](https://hexo.io/docs/configuration)


## 4. [Create a new post/foldre]
```
hexo new page tag
hexo new page category
hexo new page project
```
## 4. [Publish your page on Github](https://hexo.io/docs/one-command-deployment)
> I choose one-commend deployment, so much simplier than HUGO/Jekyll
```
npm install hexo-deployer-git --save
# edit _config.yml
hexo clean && hexo deploy
```
