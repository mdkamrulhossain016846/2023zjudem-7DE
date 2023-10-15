<h1 style="text-align:center; font-size:2vw" >How to Build Website</h1>

<h3>Steps of building -</h3>

STEP-1 : Installing all the necessary tools.<br>
STEP-2 : Open repository into <a href="https://github.com/">GitHub.</a><br>
STEP-3 : Publish the page from <a href="https://github.com/">GitHub.</a><br>
STEP-4 : Clone the repository into <a href="https://desktop.github.com/">GitHub Desktop.</a><br>
STEP-5 : Open the repository into <a href="https://code.visualstudio.com/">Visual Studio Code</a> and write the code.<br>
STEP-6 : Push all the changes into origin.<br>

### STEP-1 : Installing all the necessary tools<br>
  - <a href="https://github.com/">GitHub</a> as a host of the webpage.
  - <a href="https://desktop.github.com/">GitHub Desktop</a> to push the code from local to origin.
  - <a href="https://code.visualstudio.com/">Visual Studio Code</a> to write code and document.
  - <a href="https://nodejs.org/en">Nodejs</a> to build the environment.
  - <a href="https://www.nexmaker.com/doc/1projectmanage/markdown.html">Markdown</a> language to write the document.

### STEP-2 : Open repository into <a href="https://github.com/"> GitHub</a>
First need to open an account on <a href="https://github.com/"> GitHub</a>.To create repository click New from home page.After that set the name,keep it public and add a readme file and then click create repository(follow the picture's where is surrounded by yellow circle for your better understand)


<img src="img/tm_logo/github_repositoryopen/githubnewbutton.png">
<br>
<h2>Here, we use the repository name as "delete" to make this documentary.So don't be confuse.Repository name can be anything.</h2>
<br>
<img src="img/tm_logo/github_repositoryopen/createrepository.png">

### STEP-3 : Publish the page from <a href="https://github.com/"> GitHub</a>
To publish the page,go to repository setting and select page from code and automation, then select main from the branch and select root from the folder.Late when docs will be installed folded,need to select doc/ from the folder and then click save.(follow pictures)
After this a link will be created which is our webpage link. For now the link page will be blank because we havn't written and pushed our code.

<img src="img/tm_logo/github_repositoryopen/sett_page.png"><br>


<img src="img/tm_logo/github_repositoryopen/page_save.png">

### STEP-4 : Clone the repository into <a href="https://desktop.github.com/"> GitHub Desktop</a>

To clone the repoc open <a href="https://desktop.github.com/"> GitHub Desktop</a>. Find the option "Clone a repository" and search the repository created on <a href="https://github.com/"> GitHub</a> web and click Clone, Now the repository has been cloned.(follow pictures)
<br>
<img src="img/tm_logo/github_repositoryopen/clone_1.png">

<img src="img/tm_logo/github_repositoryopen/clone_2.png">

### STEP-5 : Open the repository into <a href="https://code.visualstudio.com/"> Visual Studio Code</a> and write the code

To open the repository into VScode from github desktop click "Open in visual studio code". 
<img src="img/tm_logo/github_repositoryopen/open in_vs.png">

Now the repositroy has opened in VScode.<br>
<br>
<img src="img/tm_logo/github_repositoryopen/vs_1.png">

- ### Install docify
open terminal in VScode in that opened repository and give the following command
> npm i docsify-cli -g
<img src="img/tm_logo/github_repositoryopen/terminalopen_vs.png">

after giving this command docsify should be install in your system, if not please click <a href="https://www.npmjs.com/package/docsify-build-cli?activeTab=readme"> docsify problem</a>.<br>

Now to create the doc folder give the following command in terminal
> docsify init ./docs
<img src="img/tm_logo/github_repositoryopen/doc_open.png">

* After that write the code inside document folder.

### STEP-6 : Push all the changes into origin.

To push the code in origin need to save the code and open GitHub Desktop and give a commit change comment and click "commit to main" and then click push origin.(follow the pictures)
<img src="img/tm_logo/github_repositoryopen/push_1.png">

<img src="img/tm_logo/github_repositoryopen/push_2.png">

<h3>Here we use the repository name as "delete" so we didn't edited code in this repository. We have edited our code in our team repository.After push to origin all our code has updated in our github repository.Here is the picture.</h3>
<img src="img/tm_logo/github_repositoryopen/after_push.png">

### Final publish

Follow the step 3. As the docs folder created, now to publish the page open the repository and as follow

> setting > page > under page select the main branch and slect docs from the folder and save it and then the web page link will be available.

Picture -
<img src="img/tm_logo/github_repositoryopen/final_publish.png">


