# Practice repo: sign commits by default

## Order of operations 

The steps I've taken with this repo. 

1. Restart my computer as my GPG credentials expire with restarts
1. Create new repo using GitHub web UI, initialize repo with a README file
1. In the repo's settings, go to **Branches**, then create a new **Branch protection rule** and select "Require signed commits"
1. Clone the repo via Terminal on my local machine
1. Run
   ```shell
   git config commit.gpgsign true
   ```
1. Run
   ```shell
   git config --local user.signingkey ####
   ```
1. Create the README and edit it