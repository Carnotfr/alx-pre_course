# Make sure you are in the root directory of your local repository (alx-pre_course)
cd /path/to/alx-pre_course

# Fetch all changes from the remote 'origin' repository, including the updated README.md
git fetch origin

# Update your local main branch with the changes from the remote
git pull origin main

# Create a new file 'up_to_date' with the git command used
echo "git pull origin main" > up_to_date

# Add 'up_to_date' to git
git add up_to_date

# Commit the changes with the message "How to be up to date in git"
git commit -m "How to be up to date in git"

# Push the changes to the remote 'origin' repository
git push origin main
