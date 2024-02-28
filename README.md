## This is a README file
A non functional, optional document that gives some information about this repository. 
Similarly, you can create a repo named README in github and create a custom bio at github.com/[your username]/README.
Heres mine: https://github.com/calebrlx/README
README documents can be formated using markdown (.md) or in plain text (.txt)
The basics of markdown
```
# - Used to depict a header
## - Used to depict a header, but smaller
```
Then the rest is pretty much plain text or you can go into more detail (here)[https://github.com]
if your reading this from the main page and you want to view the source to see how i did any styling, click on the README.md file in the "code" section at the top of the page or click "." and navigate to README.md

## This repository 
Its named calebrlx.github.io for a reason.
Just like naming a repo README, [your username].github.io is special
It allows you to host a website for free with your github account.



<summary>Method 1</summary>
<details open>
<br>
Simply create the repo from your github home screen, 
click "add file", name it "index.html" and add this
<details>


<summary>Method 2</summary>
<details open>
or click "." on your keyboard while in the your repos home which should open github.dev, an online ide. on the far left hand side youll see a vertical list of items, click on the gear icon at the bottom, hover over Themes and click the first item in the list (Colors Themes) and select something with dark in the name. now that thats out of the way, click the top item that looks like files, once in the Explorer menu, hover over the item that has the repoository name in all caps and [GITHUB], then select the far right icon that looks like a single file with a plus next to it. That should bring up a text input box that. just put "index.html" and hit enter. now click on that file and add this
</details>

```
<!DOCTYPE html>
<html>
    <head>
        <!-- This is a comment and won't effect the code -->
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <!-- Basic Meta Tags -->
        <title>Website</title> <!-- This will change the text on the page tab -->
        <link rel="icon" href="/img.png" type="image/png" sizes="32x32" /> <!-- This controls the favicon, the little image you see on google next to websites and on the left of the title -->
        <meta name="description" content="Some cool site I found."> <!-- Not that important, mostly for seo related stuff -->
        <style> 
        </style> <!-- Styling con be put in here using css -->
    </head>
    <body>
        <div> <!-- Basic divider, usefull for more complex layouts and styling -->
            <h1>Hey!</h1> <!-- Basic header text, equal to # in markdown -->
            <h3>Sub-hey</h3> <!-- Basic header text, equal to ### in markdown -->
            <p>something something</p> <!-- Basic paragraph text -->
        </div>
    <body>
</html>
```

<details closed>
<summary><h3>Method 1<h3></summary>
once done, click the green "commit" button in the upper right hand corner. it should bring up a commit screen with a message, just click commit changes or what ever it wants you to do. once its commited, wait about a minute, create a new tab in your browser, enter "https://[your username].github.io" and go to the page. hopfully if you did every thing right you should see some text that look familiar. (if not, my emails caleb@alyeska.dev). once thats up and running, I want you to google "single page html github" or click [here](https://github.com/topics/githubio), and from there find a website you like. just click on a repo, most of the time theres a link on the right side you can click on to view a demo of the website in the repo. then you can open the files and copy/paste them into your github.io repo. some sites may be designed differently and may use css, js, or another frame work.
</details>


<details closed>
<summary><h3>Method 2<h3></summary>
after that, click the 3rd item down from the top, should look like 3 dots connected in a sort of branch pattern. this is source control. your gonna see the file(s) you just created under changes. theres a text box above that and the green commit and push (read it as "save") button. your gonna wanna enter something in this, doesnt matter what it is, you could actualy describe what you did to change to file (in this case, added the first file) or you can do like the professionals like me do and enter a random letter. after youve entered your description/message, click the commit button. this will upload your changes to the repo and after minute, you should be able to go to https://[your username].github.io
<details>



## Other stuff

anything you put in the public folder will be accesable through "yoursite.com/.." so if you put an image "img.png" in the public folder (public/img.png) you would be able to find it on your website at "domain.com/img.png"

routing: any .html file you create in this file will be a path, index is a special file that is used as the home dir of you page "domain.com/". if i were to create a file about.html and publish the site, i would be able to view it by going to "domain.com/about"

(sidenote: most repos have a licence somewhere on the page, common ones are MIT and Apache. they essentialy say "you can use and modify this code but dont sue us if something bad happens" if its on git. there are some specifics for each license but i know MIT means its free use, you can clone it, add your own content, and say you wrote the whole thing if you wanted to without any mention). 

frameworks add a level of complexity but they make it easier to maintain and write bigger webpages. i highly recomend doing a general search to find some opensource projects and examine the source code. open source software.

another resource for running your own website is [Vercel](https://vercel.com). they offer generous free tier and have alot of OSS websites. it allows for more control over github.io. you can sign up for vercel using your github account and easily run repositories straight from vercel. so you could open the web ide on github for a project, deploy it on vercel, and anytime you commit, youll see the webpage on vercel automaticly redeploys. there should be a url (etc../vercel.app or something like that) on your project you can click to see your page live. anyone with this link can view your page. you could use a link shortener like https://v.gd.com (free, no sign in, easy to use) to shorten the url if you wanted to.

alot of the features on github are more tailored for proffetionals. "commit" is essentialy saving with extra steps. its from something called "git" which is version control software. super useful for when you are managing a massive code base for something like facebook but not really that nessesary for smaller personal projects. 

git is pre installed on almost every computer, you can use it by running "git [commands]" from your terminal app (on mac you can press space and command then type terminal and select terminal. on windows, id say install linux or buy a mac. on linux, actualy if your using linux im going to assume you know what your doing or are already in the command line interface). if you want to download a github repo, copy the url, it has to be "https://github.com/[username]/[reponame]"(not .dev and nothing after the repo name), and run "git clone [githuburl]". you can do this with your own repos but keep in mind if the visibility of your repo is set to private, you wont easily be able to clone the project on your local machine.



my personal faverite OSS include:
- [next.js](https://github.com/../) (framework)
- [chadnext](https://github.com/../chadnext) (basic SaaS that uses next.js)

idk abt opensource but amazing websites:
- https://huggingface.co/chat  - mostly for ai, /chat will alow you to try out the latest ai models completle for free and without an account 
- huggingface.co  - amazing site with the source code for ai models and other resources. 
- vercel.com  - hosting platform for webpages (https://vercel.com)
- railway.app  - hosting platform for resources (stuff like api's and databases) more technical (https://railway.app)
- aws  - hosting platform but more complex. i know they have a free tier but youd have to know ssh and how to use ubuntu headless along with alot of more complex computer system design stuff. also, this is the real way amazon was so successful, sure they make a decent amount off selling products but they also run most of the internet(they own computers, companies pay to use them and host their website. sites like vercel likley use aws to host websites by running some preconfigured server on aws and giving the user a nice drag and drop interface) its cheaper to use then other hosting platforms at enterprise scales. good to know about but dont worry too much about this (https://aws.amazon.com)
- chatgpt  - S+ tier resource. free to use 3.5 model but plus version is 100% worth it. (https://chat.openai.com)
- openai api  - more technical, useful if you want to make an app with ai. check out docs if you want more info, no free teir, credit based payment, still INSANELY cheap (https://platform.openai.com)
- vscode  - this is a local ide, its the same one github.dev uses. its completely free and opensource, i belive its made by microsoft but i could be wrong. its super light weight and feature rich yet simple to get started with, go to (https://vscode.com) and follow the instructions to install it localy if you want to work on projects localy
- docker  - more complex but its usefull for defining how an app runs (https://github.io)
- next.js  - docs for nextjs if you want to learn the frame work (https://nextjs.org/docs)
- sololearn  - good for learning the basics of a programming language, i think its on the app store
- pythonista  - ios app, its a few dollars on the app store but its a super useful for quickly writing and running basic python scripts without worring about set up 


## terms 

### git
- git 
- pull
- merge
- main
- version control
- commit
- repo
- source code
- fork
- issues
- contribute
- push

### networking 
- http
- https
- tld (.com)
- subdomain
- port
- proxy
- ip
- dns
- records
- domain
- url
- uri
- cookies
- inspect
- webconsole

### cli
- cli
- navigation
    - ls 
    - cd 
    - mkdir
    - vim
    - rm -rf 
    - ~/
- npm
- pnpm
- yarn
- pip

### languages
- shell .sh
- typescript .ts .tsx
- javascript .js .jsx
- json .json
- python .py
- swift .swift

### files
- README.md
- index.html
- package.json
- yarn.lock
- .git
- docker-compose.yml
- Dockerfile

### other 
- syntax
- bug


------

<details open>
<summary>Want to ruin the surprise?</summary>
<br>
Well, you asked for it!
</details>