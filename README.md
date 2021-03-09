# Setting up Git with Gitlab (Speedrun any%) 🏃

## **1) Adding ssh key to gitlab 🔑**

1.1) Open windows terminal and enter `ssh-keygen -t rsa -b 2048 -C "<comment>"` with comment being an identifier, e.g. ("Desktop")

1.2) Press `enter` at all the options (3 times)

1.3) Navigate to `C:\Users\<YourUser>\.ssh` and find `id_rsa.pub`

1.4) Open `id_rsa.pub` in a text editor and copy all contents

1.5) Open [Gitlab](https://b3.complang.tuwien.ac.at/) Website

1.6) Click on the top right icon, navigate to `Settings>SSH Key` and paste it in the first textbox

1.7) Click `Add key`

Now you can push commits to the gitlab repository.

## **2) Cloning the gitlab project 🧠**

2.1) Open IntelliJ

2.2) Click `Get from VCS` ![image](https://user-images.githubusercontent.com/31989404/110538611-811e8980-8124-11eb-97ba-7d5c743a5527.png)

3.3) Navigate back to your Gitlab project and press the blue `clone` button, then copy the `Clone with SSH` option ![image](https://user-images.githubusercontent.com/31989404/110539127-25083500-8125-11eb-9c99-ed2dc693f70b.png)

3.4) Back in IntelliJ, paste it under the `URL` box and pick a location where you want to save the project

3.5) When asked if you want to connect anyways, pick yes

Now you can open and work on the project.

## **3) Committing and pushing your project 🔗**

3.1) On the top right, you should have buttons looking like this: ![image](https://user-images.githubusercontent.com/31989404/110539827-048caa80-8126-11eb-89ab-7811d07d98b7.png)

3.2) When you want to commit, click the first icon or press `Ctrl + K`

3.3) Select which files you want to commit changes from ![image](https://user-images.githubusercontent.com/31989404/110540086-57fef880-8126-11eb-9136-6307bbf25a6f.png)
Add a commit message (e.g `Add constructor`) and press commit

Now you saved the commit locally, but when you to push it to the Gitlab project, press the right icon or `Ctrl + shift + K` and select `Push`

You are now a certified git expert 🧙

