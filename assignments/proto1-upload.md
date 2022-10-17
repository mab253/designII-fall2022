# 💻🤖 uploading prototype #1 code

We are going to use Github to share code from the current versions of our project prototypes. We will each create a different _branch_ in the same private repository. 

Once you are added to this repository via your e-mail, you can see it here: https://github.com/mab253/22design2-proto1

1. Do you have a Github account? Please [set one up](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) in case you don't.

2. Do you have `git` downloaded on your machine? 
  - Open your terminal and type: `git --version`
  - If you don't see a version number, you can install `git` [here](https://git-scm.com/downloads).


3. In your terminal, move so that you are operating inside the directory where you want to work - using `cd` (change directory)
  - For example, do you want to handle the code on your Desktop? Do you have a folder where you are working on your project?


4. Once you are where you want to be in the file structure, you need to `clone` the Github repository where you will be uploading your code.
  - The URL for the private class Github repository can be found here, under the "Code" green menu:
  <img width="1645" alt="Screen Shot 2022-10-17 at 2 41 27 PM" src="https://user-images.githubusercontent.com/17707843/196256926-4548819c-ee6e-40a5-9618-8b95933ff0f0.png">
  
  - In your terminal, type `git clone URL` (but replace "URL" with the one from the repo)
  - Now we need to "step inside" this folder we've downloaded: type `cd 22design2-proto1`. You can use `pwd` ("print working directory") to see if you are inside the right folder.

5. Now you are going to work in your own _branch_ in this repository. 
  - Choose a short name for your branch - a nickname based on your project name, or your own name, your Discord name, etc.
  - In your terminal, type `git branch NAME` (but replace "NAME" with what you've chosen
  - Now type `git branch` - you should see yours listed! And maybe others!

6. You've made the branch, but now you have to actually get _on_ it. In git, this is called "checkout."
  - In your terminal, type `git checkout NAME` (but use your branch name)

7. Now we are going to create a "commit," an upload that changes the origin repository, not just on your computer.
  - In your own file system, change the content of the repository folder: keep the README.MD, but add your own code. You can drag and drop a folder here.
  - If you are using something like Google Colab or another cloud platform with a shareable link, create a text or markdown file that has that link, and add it to this folder.
  - When you are done, in your terminal, type `git add .` This adds your changes.

8. We now need to add a message to describe your upload, your commit, so that people reading the repository know why you made the change.
  - In your terminal, type `git commit -m YOUR MESSAGE` - but replace YOUR MESSAGE with a short description of what you are doing, i.e. "uploading prototype for GAN project"

9. Now the final push!
  - In  your terminal, type `git push origin NAME` - but very important, change the NAME to your BRANCH NAME that you've created

10. Now when you check out the Github repo in the [web interface](https://github.com/mab253/22design2-proto1), you should be able to see your own branch! Look for a drop-down list of branches labeled "main" in the upper left. 
<img width="1115" alt="Screen Shot 2022-10-17 at 2 54 58 PM" src="https://user-images.githubusercontent.com/17707843/196259347-575945e6-70cc-4fa5-b7fa-f05291b1ed91.png">

