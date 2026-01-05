1. `mkdir ~/documents`  
Explanation: `mkdir` command to create a new directory named ***documents*** located in my home directory.  


2. `cd ~/documents && touch plan.txt`  
Explanation: `cd` to change my current working directory to the newly created ***documents*** folder, and then used `touch` to create an empty file named ***plan.txt*** inside it.  


3. `echo "sample text abcdefghijklmnopqrstuvwxyz" > plan.txt`  
Explanation: `echo` command to add a string of text and the redirection operator `>` to write that text into ***plan.txt***.  


4. `ls -l plan.txt`  
Explanation: `ls -l` to list the file meta-details in long format.  


5. `cp plan.txt plan_copy.txt`  
Explanation: `cp` command to create an exact duplicate of ***plan.txt*** named ***plan_copy.txt***.  


6. `cd .. && mv documents project_documents`  
Explanation: first moved up one level to the parent directory using `cd ..`, `mv` to rename the ***documents*** directory to ***project_documents***.  


7. `mkdir ~/project_documents/archive`  
Explanation: `mkdir` to create a new subdirectory named ***archive*** inside the ***project_documents*** folder.  


8. `mv ~/project_documents/plan_copy.txt ~/project_documents/archive`  
Explanation: `mv` command to move ***plan_copy.txt*** from the main project folder into the ***archive*** subfolder.  


9. `ls -R ~/project_documents`  
Explanation: `ls` with the `-R` (recursive) flag on the parent directory. This displayed the entire directory tree, showing both the files in the main folder and the contents of the ***archive*** subfolder.  


10. `realpath ~/project_documents/archive/plan_copy.txt`  
Explanatino: `realpath` displays the absolute path of ***plan_copy.txt*** after it was moved into the ***archive*** directory.  