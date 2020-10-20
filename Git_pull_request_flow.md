Github Flow For Pull Requests

---
1. Fork the repository by clicking on the fork icon.

2. Clone the forked repository and cd to that repository.

<br><center> 
[git clone <url>](images/img1_pr.png)

3. Create a new branch.

<br><center>
[git checkout -b <new branch name>](images/img2_pr.png)

4. To pull the latest code from the original repository add upstream.

<br><center>
[git remote add upstream <url>](images/img3_pr.png)

5. Set upstream branch.

<br><center>
[git branch -u upstream/master <branch>](images/img4_pr.png) 

6. Pull the latest code.

<br><center>
[git pull](images/img5_pr.png)

7. Make changes and add them.

<br><center>
[git add <filename or . to indicate changes in current directory](images/img6_pr.png)

8. Commit the changes.

<br><center>
[git commit -m" message"](images/img7_pr.png)

9. Push the changes.

<br><center>
[git push <remote branch>](images/img8_pr.png)

10. Create pull request by navigating to the forked repository. 
