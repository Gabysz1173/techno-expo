:fire: This repo is for my presentation on computing at school. :fire:

Utilisation de Reveal.js

Use of 
    Reveal.js to generate slides 

Spectacle 
    npm add spectacle
    npm create-spectacle # to create new presentation 
    
    npm install # in the presentation dir 
    npm start  # to launch the presentation 

Reveal-md 
```shell
npm i https://github.com/patarapolw/reveal-md.git
# or 
npm i -g https://github.com/patarapolw/reveal-md.git
git submodule add https://github.com/patarapolw/reveal-md.git
``` 
    
```shell
cd reveal-md && npm i
cd ..
npm i ./reveal-md
# This will create symlink, but `yarn add ./reveal-md` will copy to `node_modules`
```
