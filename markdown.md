<!-- Create your  Repository -->
# Create a new directory forproject
mkdir my_project

# Change into the project directory
cd my_project

# Initialize a new Git repository
git init
# Add all files to staging
git add .
# Commit the changes locally
git commit -m "Initial commit"
# Add the GitHub repository as a remote
git remote add origin https://github.com/your-username/your-repository.git

# Verify the remote repository
git remote -v
# Push the local repository to GitHub
git push -u origin master
