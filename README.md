# Goal

Create continuous integration of Quarto website without using docs folder, build docs folder on deployment server

# Links

https://github.com/quarto-dev/netlify-plugin-quarto
https://main--vermillion-salmiakki-8cfe18.netlify.app/docs/

# Progress

- Netlify needs quarto CLI in order to run quarto commands
- After figuring out how to get quarto CLI on netlify, run quarto render command upon build
- Got deployment without docs working, merge conflicts may still arise in _freeze and now trying to get build working with just posts folder

