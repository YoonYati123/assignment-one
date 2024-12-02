# Assignment One
Assignment one, question three

# Configure Git
git config --global user.name "Yoon Yati"
git config --global user.email "yoonyati12324@gmail.com"

# Create a new project
mkdir assignment-one
cd assignment-one
git init

# Create README file
echo "# Assignment One" > README.md
git add README.md
git commit -m "Initial commit with README"

# Link to GitHub and push
git branch -M main
git remote add origin https://github.com/YoonYati123/assignment-one.git
git push -u origin main

# Update README file
echo "Assignment one, question three" >> README.md
git add README.md
git commit -m "Updated README for assignment one"
git push

