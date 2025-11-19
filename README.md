echo "# JenkinsCI" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/irfanvox/JenkinsCI.git
git push -u origin main

#Changing for pollSCM test again
