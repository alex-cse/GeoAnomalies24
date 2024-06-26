[Link](https://onspatial.github.io/GeoAnomalies24/)
# Use GitHub:
## Build the Website and publish to GitHub.io page

The website source code is at the `main` branch and the compiled code is at the `gh-page` branch

1. Clone the project to your repository    
2. Go to repository setting -> find the GitHub Pages
3. Set the branch to `gh-page` and save it.
4. Go to 'config.yml' and edit the baseurl to "https://yourGitHubUserName.github.io/youRepositoryName/"
5. Check the URL; it might take a while for the repo to be compiled and published to the url.



## Configure the website

Everytime when you change a place, Hugo will automatically refresh your browser.

1. Change the concent in "about": Edit `themes/hugo-conference/layouts/partials/about.html`
2. Change the cover image: replace `static/img/cover.jpg`
3. Change all other content: Edit `config.yml`

