Clonning source code from repo


'''
git clone https://github.com/jeffhudz/aiops_projects.git
'''

To add files into staging or allow file to be tracked by git

'''
git add <file_name>
'''


Replace "you@example.com" with github email id

'''
git config --global user.email "you@example.com"
'''

Replace "Your name" with username

'''
git config --global user.name "Your Name"
''''

To perform commit

'''
git commit -m "Write message"
'''

Rename current branch to main

'''
git branch -M main
'''

To check remote branch Url and variable name

'''
git remote -v
'''

To send changes to remote branch

'''
git push <remote_branch_variable><branch_name>
'''

To remove file from staging area

'''
git rm --cached <filename>
'''