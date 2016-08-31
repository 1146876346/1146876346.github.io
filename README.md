# stepbystep
A jekyll theme, simple and clear

## Preview
#### PC or Pad
<img style="box-shadow: 10px 10px 5px #888888;border: 1px solid black;" src="https://github.com/jokinkuang/stepbystep/raw/master/article.png"></img>
#### Mobile
<div style="box-shadow: 10px 10px 5px #888888;border: 1px solid black;">
<img style="width:50%;" src="https://github.com/jokinkuang/stepbystep/raw/master/mobile.png"></img>
<img style="width:50%;" src="https://github.com/jokinkuang/stepbystep/raw/master/mobile2.png"></img>
</div>

## Install
assume the github username is "hello" then:  
1. create a repository named "hello.github.io"  
2. clone this repository  
  `git clone https://github.com/jokinkuang/stepbystep.git`  
3. push the whole thing to your repo "hello.github.io"  
  `git remote set-url origin https://github.com/hello/hello.github.io.git`  
  `git push origin master`  
4. browse "hello.github.io"  
> if your github username is "world" then replace upper "hello" all to "world"  

## Custom Domain  
if you want to visit "www.hello.com" instead of "hello.github.io" then:  
1. create a file named "CNAME" (the file is already exist)  
2. add following to the "CNAME"  
  `www.hello.com`  
3. go to the Shop where your domain bought and set the Domain DNS to:  
  | prefix | record-type | host |  
  | ------ | ------ | ------ |  
  | www | CNAME | hello.github.io |  
