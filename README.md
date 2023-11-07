# Goal

Create continuous integration of Quarto website without using docs folder, build docs folder on deployment server

# Links

- https://github.com/quarto-dev/netlify-plugin-quarto
- https://vermillion-salmiakki-8cfe18.netlify.app/

# Progress

- Netlify needs quarto CLI in order to run quarto commands
- After figuring out how to get quarto CLI on netlify, run quarto render command upon build
- Got deployment without docs working, merge conflicts may still arise in _freeze and now trying to get build working with just posts folder

# Findings

- Deployment without docs possible
- Merge conflict in _freeze, re-hashing occurs upon render of new post
- Current workflow is as follows : 1. New post is made and rendered locally with "quarto render" in terminal, 2. Changes are pushed to persons branch and make a PR to main, 3. Take in new hash to resolve merge conflict and approve PR
- Freeze is set to false in _quarto.yml and so far resolved merge conflicts, but need more test 11/7/23

# Next Steps

- Create corporate Netlify for testing this, fork this repo and deploy site using the forked repo. Make sure to set build public directory to /docs

