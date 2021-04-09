# Change Directory to "Users"
cd ..


# Make an empty directory
mkdir copy-mslearn-dp100


# Copy the lab materials recursively into the new folder (folder 1)
cp -R mslearn-dp100/* copy-mslearn-dp100/


# Go to Github, create a new repository


# Git clone the new Github repo into the machine -> folder 2
Git clone <your new repo address>


# Copy the lab materials recursively from folder 1 to folder 2
cp -R copy-mslearn-dp100/* <your new repo name>


# Go to folder 2
cd <your new repo name>


# Git stage new files
Git add .


# Git commit new files
Git commit -m "Test commit"


# Git push
Git push