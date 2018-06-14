# Clipper Website

This contains the sources for building my personal website, hosted at <http://dancrankshaw.com>.

First clone the repository and it's submodules.

```sh
git clone --recursive https://github.com/dcrankshaw/personal-website.git
```

The website is built with [Hugo](https://gohugo.io/overview/introduction/), a static site generator.
You should read at least the Hugo [quickstart](https://gohugo.io/overview/quickstart/), but here's how
to get the website built and running quickly

To build the website, you need to first install Hugo.

```sh
brew install hugo
```

Once you do that, you can build and serve the website locally by running the following command in
the root of the repo.

```sh
hugo server
```

You can see the website at <http://localhost:1313/>. Hugo will automatically detect and rebuild the website
when you change any files.


## Building the website

Once you've made your changes and tested them locally, submit a pull request. Once they've been merged into master, the new version of the site
can be published with the `publish_site.sh` script. From a freshly pulled and clean checkout of `master`,
run `./publish_site.sh <remote_repo_name>`. For example, if the name of your remote repo was `ucbrise`, run the following commands
from the root of the `clipper-website repo`.

```sh
git checkout master
git pull --rebase dcrankshaw master
./publish_site.sh dcrankshaw
```

You can read about how the `publish_site.sh` script works [here](https://gohugo.io/tutorials/github-pages-blog/).
