Global setup:
 Set up git
  git config --global user.name "Your Name"
  git config --global user.email sukar@lab1521.com
      
Next steps:
  mkdir initialized3
  cd initialized3
  git init
  [IF WINDOWS]
	copy con README
	^Z (Ctrl+Z)
  [ELSE]
	touch README
  [END]
  git add README
  git commit -m 'first commit'
  git remote add origin git@github.com:sukar/initialized3.git
  git push -u origin master
      
Existing Git Repo?
  cd existing_git_repo
  git remote add origin git@github.com:sukar/initialized3.git
  git push -u origin master
      
Importing a Subversion Repo?
  Check out the guide for step by step instructions.
      
When you're done:
  Continue