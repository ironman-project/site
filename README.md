# Ironman Project Site

Everything you need to know about the [Ironman Project](https://github.com/ironman-project/ironman).

You can see this documentation site live here: https://ironman-project.github.io/site/

# How to generate this site

While being on the `website` subfolder just run this command:

    GIT_USER=gepser \
    CURRENT_BRANCH=master \
    npm run publish-gh-pages

Of course, whit your own git user and with the proper current branch.

Changes will be pushed to the `gh-pages` branch, which will be always updated automatically, so don't do manual changes there.
