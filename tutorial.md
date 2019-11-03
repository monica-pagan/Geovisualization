## Lecture 10. Host and publish your map online (II)


## 3. Navigate to your JS/HTML/CSS folder in terminal
Open a GitHub Shell and navigate to the directory that is storing your javascript files by using the CD command. 

## 4. Initiate your folder
Now you will initialize the folder as a GitHub repository on your local machine. To do this type `git init` and click Enter.

## 5. Link your local webpage dictory with your github repository
type in `git remote add origin <your reposity name, such as https://github.com/boehnert/webpage.git>`. For example, I create a repository with name of `choroplethlead`, then I just need to type `git remote add origin https://github.com/xiaojianggis/choroplethlead.git`. This command will link your directory on your local machine with the GitHub repository.  You will see this command on GitHub under how to push an existing repository from the command line.

## 6. Create a branch for your repository
Branch is just like a virtual environment. We can create a seperate environment and do experiment inside it. Now you need to create a branch called `gh-pages` from GitHub and switch to this branch. Type in `git checkout -b gh-pages`. This command with switch to the gh-pages branch in the repository.

## 7. Commit everything in your folder to your repository
Now just commit everything in the folder to your repository by typing in `git add .`, then type in `git commit -m 'This is my initial commit'`

## 8. Push your project up to the branch on the Github repository
Push your project up to the branch gh-pages by typing in `git push origin gh-pages`

## 9. Open your webpage on Web browser
Now your project is up on GitHub. In a web browser log into your GitHub account and view the project in the gh-pages branch. You can also view the web site using your http://<GitHub handle>.github.io/repository name. My final website can be viewed at https://xiaojianggis.github.io/choroplethlead/


echo "# choropleth-lead" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/xiaojianggis/choropleth-lead.git
git push -u origin master

