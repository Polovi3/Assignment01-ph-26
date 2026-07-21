### Problem I faced...
When I add my code in git then Git terminal shows multiple fatal errors.
---
  1. First error couldnot recogonized me then put this 
    git config --global user.email "your_email@example.com"
    git config --global user.name "Your Name"
2. Suddenly show that (nothing to commit, working tree clean) : I thougbt this is and error then I reseach and help form AI and find the main reason which is
    a. fatal: Could not read from remote repository : git remote remove origin
3. Add HTTPS linkes proprly : git remote add origin https://github.com/Polovi3/Assignment01-ph-26.git
4. Then I push my code again and add this on github : git push -u origin main
5. Final issue show on my code was (This site can't be reached) :
   a. git remote remove origin
   b. git remote add origin <Peast Your right HTTP Link here>
   c. git push -u origin main
