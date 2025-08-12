#FacetedNixFlake1
#Basic flake setup with git and brave (README ... How to setup your flake configuration. Omit my hardware configuration and adjust your configuration.nix to your own preferences and os version)
#See link for start on how to setup your own flake configuration --> https://nixos.asia/en/configuration-as-flake 
#Special thanks to https://emanote.srid.ca/ for this tutorial! Check out this website too!
#
#After above above Flake onfiguration tutorial it mentions saving your configuration to GIT by "pushing" your configuration repo to it, do this -->
# $git push --set-upstream https://github.com/GITUSER/ master 
#Change "GITUSER" to your GIT account main repository you have created. If you get a password authentication not supported see note below.
#
#Attempting to upload your config to GIT? Git Password Authentication Error?
#GitHub no longer supports password authentication for Git operations; you must use a Personal Access Token (PAT) or SSH keys instead.
#To push your Linux configuration to a GitHub repository via the CLI using HTTPS, generate a PAT from your GitHub account settings under Developer Settings > Personal Access Tokens.
#When prompted for a password during a git push, enter your GitHub username and the generated PAT as the password.
#To avoid entering the token repeatedly, configure Git to cache credentials using git config --global credential.helper store.
#Alternatively, switch to SSH authentication by changing your remote URL to git@github.com:username/repository.git and ensuring your SSH key is added to your GitHub account.
