# User Guide

To write your own posts for TReviews, first clone the repository in a local directory of your choice. Then, follow the set-up steps below:

## Install HUGO

Run the following command in your terminal to install HUGO: 

```
brew install hugo
```

## Local Testing

To ensure the local development environment is set, open an editor and navigate to the cloned directory via the command line. Run the following command to spin up a local port for testing:
```
hugo server
```

If everything checks out, your server should be running on http://localhost:1313/. 

Changes made locally will reflect instantaneously on this server.

## Create A Post

To write a new post, first navigate to /content/posts. Here, you'll notice a list of markdown files representing distinct vehicle posts. 

Create a new .md file in this directory. Note that the post will initially be set to the contents of default.md, which acts as a preset for new posts. The simplest way to get started is to copy/paste this file or any other post into yours.

At this point, you're all set! All content and formatting is subject to you, along with the theme preset variables featured in the file header.

For more specific questions, reference previous post source code or check out [PaperMod](https://adityatelange.github.io/hugo-PaperMod/) official docs.

## Publishing Content

To create a stable deployment pipeline, any content drafted for publishing should be pushed to the remote dev branch. From here, simply create a pull request. Once merged to main, Netlify will automatically redeploy the site with relevant changes.