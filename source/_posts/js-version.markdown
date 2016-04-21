#Hexo-Theme-Hux

### Ported Theme of [Hux Blog](https://github.com/Huxpro/huxpro.github.io), Thank [Huxpro](https://github.com/Huxpro) for designing such a flawless theme.

###[Demo &rarr;](http://kaijun.rocks/hexo-theme-huxblog/)


### Usage

I didn't published it as a single theme folder because a few of the pages are added and modified manually, so you should manually create some folders for the new pages and modify the `_config.yml` if you only have the single theme folder.

So i published the whole hexo project for your convenience, all pre settings and boilerplates are included, have a look and go ahead customizing your own blog!

##### Init

```
git clone https://github.com/Kaijun/hexo-theme-huxblog.git
cd hexo-theme-huxblog
npm install
```

##### Modify
Modify `_config.yml` file with your own info.
Especially the section:

```
deploy:
  type: git
  repo: https://github.com/Kaijun/hexo-theme-huxblog
  branch: gh-pages
```
Replace with your own repo!

##### Serve/Deploy

```
hexo serve // run hexo in local environment
hexo deploy // hexo will push the static files automatically into the specifig branch(gh-pages) of your repo!
```

##### Enjoy! 
And **Star** this Project if you like it! [**Following**](https://github.com/Kaijun) would also be appreciated!
