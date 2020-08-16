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

## 3. [work on config/themes](https://hexo.io/docs/configuration)

## 4. [Publish your page on Github](https://hexo.io/docs/one-command-deployment)
> I choose one-commend deployment, so much simplier than HUGO/Jekyll
```
npm install hexo-deployer-git --save
# edit _config.yml
hexo clean && hexo deploy
```
