# Devops-practice
This is where I try and learn Devops as much as I can
there is big emphasize on Github, Jenkins, Docker in the tutorial i am following, but to my knowledge I know Kafka can also be very handy
so I am creating this and will be linking it to the practice project I am creating in Jenkins
I hope this helps.

as of now i am following the tutorial of edureka


3:48:32/ 6:47:12

*also check the ubuntu/linux installation in virtual box and the use of web ubuntu emulators (chk bookmark on chrome)

53:00 docker demo
is a little problematic for me atleast i had to look at other edureka video to see
if docker commands are working or not
https://www.youtube.com/watch?v=iJeL2tOFfvM&t=1210s&ab_channel=edureka%21

using this repo as practice
https://github.com/saurabh0010/devops-tutorial



**GitHub: git clone someone else's repository & git push to your own repository**

I'm going to refer to someone else's repository as the other repository.

Create a new repository at github.com. (this is your repository)

Give it the same name as the other repository.
Don't initialize it with a README, .gitignore, or license.
Clone the other repository to your local machine. (if you haven't done so already)

git clone https://github.com/other-account/other-repository.git
Rename the local repository's current 'origin' to 'upstream'.

git remote rename origin upstream
Give the local repository an 'origin' that points to your repository.

git remote add origin https://github.com/your-account/your-repository.git
Push the local repository to your repository on github.

git push origin master
Now 'origin' points to your repository & 'upstream' points to the other repository.

Create a new branch for your changes with git checkout -b my-feature-branch.
You can git commit as usual to your repository.
Use git pull upstream master to pull changes from the other repository to your master branch.
