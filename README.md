# Guide to get GitFiti working on your `Windows` machine

1. Clone this repo on your machine => [Gitfiti](https://github.com/aneagoie/gitfiti)

2. Create a new GitHub repo to store your handiwork.

3. First make sure you have Python 3 and Git (or any terminal which can run shell commands.) installed on you machine.

4. Then, create a new repository on your github account and make sure that you create an empty repo even __WITHOUT__ a README.md.

5. If you are using SSH on your GitHub account. Then you are ready to go.

6. If you are not using SSH, copy the HTTPS URL from your repo. You will need this link to edit the `gitfiti.sh` script because the python script generates the git commands with the SSH URL.

7. Then, run the gitfiti.py script. (On your Windows CMD go to the GitFiti folder path and type the command `python gitfiti.py`)

8. Leave the Github URL blank

![Blank URL](https://i.udemycdn.com/redactor/raw/2019-03-10_09-10-06-4c5104a059fc8d6aace2c55ebf0885f2.png)

9. Enter your username

![Username](https://i.udemycdn.com/redactor/raw/2019-03-10_09-11-07-064dde4a1b8d06da982df6d36ea0d1a2.png)

10. Then enter the name of the new created repo (it doesn't have to be gitfiti). Leave the weeks to offset blank


![Repo name](https://i.udemycdn.com/redactor/raw/2019-03-10_09-12-40-4f3995a9ddae1873c11f6335669ed8f3.png)

11. Then, type `gitfiti` in the prompt to generate way more commits

![Command](https://i.udemycdn.com/redactor/raw/2019-03-10_09-14-05-860aee974e3c1ecaa083ad2575026eef.png)

12. Then at the next prompt, leave 'load images from' blank

![Load Images Prompt](https://i.udemycdn.com/redactor/raw/2019-03-10_09-15-33-262a4bd1c56a6f890c3e0f5dedbf54a7.png)

13. Now, type one of the image keywords in the next prompt. I picked the octocat2

![Image Name](https://i.udemycdn.com/redactor/raw/2019-03-10_09-16-51-7d931ce189cba05c438e0fdbbe8f3952.png)

14. After all of this, copy and paste the gitfiti.sh script into another directory which is __NOT__ a git project already.

15. Now, if you are using SSH with GitHub, then you are ready to execute the new gitfit.sh script.

16. If you are not using SSH, open the gitfiti.sh file, scroll down to the very bottom and paste the HHTPS URL (the one you copied in STEP 4) from your GitHub repo to the git remote add statement:

![GitHub Link](https://i.udemycdn.com/redactor/raw/2019-03-10_09-22-38-c98999da29e5f889b9d0b2d451327ac3.png)
___________________________________________________________________________________________________

Now, run the gitfiti.sh script and wait until the prompt changes. It may look like nothing is happening but behind the scenes, the script creates the commits. You can watch this process by opening the directory which this script has created and then go into the .git directory.

If you are using SSH, then you won't get any further prompts and you are finished with it.

If you are not using SSH, then you may get prompts which asks you for your GitHub username and password.

The script makes the the `git add`, `git commit` and `git push` to your repo and finially, you have your gitfiti:

![octocat2](https://i.udemycdn.com/redactor/raw/2019-03-10_09-29-10-e63632b7f1fffa9daa894f40f70a1d78.png)


Thanks for following!!! 🙂

P.S : The original instructions were provided by [Wolfgang Kreminger](https://github.com/r4pt0s). I have modified it a little and included a few things which I felt would clarify the instructions a bit more.