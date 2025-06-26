# 1999 Script 
 
Travel back to 1999 with a single command. 

## Setup

Before running the script, you need to prepare your GitHub account:

1. **Create a new repository**  
   Visit [github.com/new](https://github.com/new) and create a new repository named `1999`

2. **Generate a personal access token**  
   Go to [github.com/settings/tokens/new](https://github.com/settings/tokens/new) and generate a personal access token with repository permissions, then copy it for later use

## Execute 
 
```bash 
sh -c "$(curl -fsSL https://raw.githubusercontent.com/AdityaDwiNugroho/1999-sc/main/index.sh)" 
``` 
 
## How It Works 
 
Git stores timestamps for every commit. This script manipulates those timestamps to create a commit dated January 1, 1999. 
 
The process: 
1. Creates a temporary directory named "1999" 
2. Initializes it as a Git repository 
3. Creates a README file 
4. Commits with date set to `1999-01-01T18:00:00` 
5. Pushes to GitHub as a new repository 
6. Cleans up the local directory 
 
## Requirements 
 
- GitHub username 
- Personal access token with repo permissions 
 
## Result 
 
You'll get a "1999" repository on your GitHub account with one backdated commit, creating a contribution square for January 1999 on your profile. 
 
## Screenshot 
 
![GitHub Contribution Graph](screenshot.png) 
 
*Your contribution graph showing activity from 1999* 
 
--- 
 
*Leave your digital footprint in the past.*