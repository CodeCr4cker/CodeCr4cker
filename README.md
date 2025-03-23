<p align="center">

 <img src="https://github.com/CodeCr4cker/CodeCr4cker/blob/main/1000207624-removebg-preview.png">

</p>

#To download the tool from we need a code and code is:-
```
git clone
```


```
import os
import subprocess

def create_folders_and_push_to_github(repo_path, folders):
    # Navigate to the repository path
    os.chdir(repo_path)

    # Step 1: Create folders
    for folder in folders:
        os.makedirs(folder, exist_ok=True)
        # Create a .gitkeep file inside each folder to ensure Git tracks it
        with open(os.path.join(folder, '.gitkeep'), 'w') as f:
            pass  # Just creating an empty .gitkeep file

    # Step 2: Add changes to git
    subprocess.run(["git", "add", "."], check=True)
    
    # Step 3: Commit the changes
    subprocess.run(["git", "commit", "-m", "Added multiple folders with .gitkeep files"], check=True)

    # Step 4: Push changes to GitHub
    subprocess.run(["git", "push", "origin", "main"], check=True)  # Replace 'main' if you use a different branch

    print("Folders created and changes pushed to GitHub.")

if __name__ == "__main__":
    # Path to your local GitHub repository
    repo_path = input("Enter the path to your local GitHub repository: ")

    # Ask user for folder names
    folders_input = input("Enter the folder names separated by commas (e.g., folder1,folder2,folder3): ")

    # Split the input into a list of folder names
    folders = [folder.strip() for folder in folders_input.split(",")]

    # Call the function to create folders and push to GitHub
    create_folders_and_push_to_github(repo_path, folders)
````
<!--
 <img src="https://github.com/Divyanshu-85/Divyanshu-85/blob/main/Dark-Green-Modern-Initial-Logo-unscreen%20(1).gif" height="200px">
	
<img src="https://github.com/Divyanshu-85/Divyanshu-85/blob/main/Screenshot_2025-01-24-17-27-25-32_40deb401b9ffe8e1df2f1cc5ba480b12.jpg">

<a href="https://github.com/Divyanshu-85/Required-Document/blob/main/Gamer.md"><img src="https://github.com/Divyanshu-85/Divyanshu-85/blob/main/152d5105-2a65-492d-8f78-2ed71763573e.png" height="20px"></a>

<div style="text-align: center;">
  <img src="https://github.com/Divyanshu-85/Divyanshu-85/blob/main/Navy_Blue_Geometric_Technology_LinkedIn_Banner-removebg-preview.png" alt="LinkedIn Banner">
</div>

<!--
<div style="text-align: center;">
  <img src="https://github.com/Divyanshu-85/Divyanshu-85/blob/main/1000179512-removebg-preview.png" alt="Profile Image">
</div>


<img src="https://github.com/CodeCr4cker/CodeCr4cker/blob/main/IMG_20250310_205137.jpg">
-->
