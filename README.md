<h1>sourcery-dev-2021</h1>

<ol>
  <li>Fork given repository</li>
  <li>Go to your github account and find the forked repository</li>
  <li>Clone/Pull repository</li>
  <li>Create your branch. Name it like ‘feature/name-surname’</li>
  <li>Switch to that branch.</li>
  <li>Create a folder with your name like name-surname.</li>
  <li>Go to that folder. All changes you make will be inside this folder.</li>
  <li>Create a helloWorld.txt file with the text ‘Hello World!’</li>
  <li>Commit that file with message ‘My first commit’</li>
  <li>Push this code to repo</li>
  <li>Create a branch from your feature branch called conflict/name-surname</li>
  <li>Go to your conflict branch ( conflict/name-surname )</li>
  <li>Change helloWorld.txt file contents to ‘Hello World from merge-conflict branch!’</li>
  <li>Commit and push your changes</li>
  <li>Go back to your feature branch ( feature/name-surname )</li>
  <li>Change the contents of helloWorld.txt file to ‘Hello from feature branch!’</li>
  <li>Commit and push your changes</li>
  <li>Merge merge-conflict brach into your feature branch ( feature/name-surname )</li>
  <li>Resolve conflicts with your favourite editor. Your finished helloWorld.txt file contents should be:<br>
  Hello from feature branch!<br>
  and<br>
  Hello from merge-conflict branch!<br>
  after successful merge conflict</li>
  <li>Commit and push your resolved merge conflict</li>
  <li>You should have your feature branch with the helloWorld.txt file and it’s contents:<br>
  Hello from feature branch!<br>
  and<br>
  Hello from merge-conflict branch!<br>
  after successful merge conflict</li>
  <li>Go to repo page and check your commit history to see how it looks visually and that all steps were done successfully.</li>
  <li>Create a pull Request to merge your feature branch to master</li>
</ol

  
<h2>Most common commands cheat sheet</h2>
<ul>
  <li>git status - <em>shows the current status and relavent data</em></li>
  <li>git add <strong>pathToFile</strong> - <em>moves specified changes to staging area</em></li>
  <li>git add <strong>.</strong> - <em>moves all current changes to staging area</em></li>
  <li>git commit -m <strong>"message"</strong> - <em>moves changes from staging area to commit history</em></li>
  <li>git push - <em>updates remote repository with commit history from your local repository</em></li>
  <li>git push --set-upstream origin <strong>branchName</strong> - <em>creates an istance of your local branch in remote</em></li>
  <li>git pull - <em>updates your local repository with commit history from remote repository</em></li>
  <li>git branch <strong>branchName</strong> - <em>creates a new branch in local repository</em></li>
  <li>git checkout <strong>branchName/hash</strong> - <em>moves to the specified branch or commit</em></li>
  <li>git merge <strong>branchName</strong> - <em>merge specified branch commit history into current branch</em></li>
</ul>
