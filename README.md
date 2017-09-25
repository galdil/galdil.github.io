# static-testing-site
This is a site based on Jekyll for testing interactions.
The `gh-pages` is being published automatically via [http://qmerce.github.io/static-testing-site](http://qmerce.github.io/static-testing-site).
Any change in this branch is automagically being published.
For more detail see [here](https://pages.github.com/).

## Updating site
The SDK being used is [http://static.qmerce.com/js/sdk/dev/apester-sdk.min.js](http://static.qmerce.com/js/sdk/dev/apester-sdk.min.js) and it is set [here](https://github.com/Qmerce/static-testing-site/blob/gh-pages/_includes/head.html#L54). It can be easily changed.

Each page has inline interactions set in [here](https://github.com/Qmerce/static-testing-site/blob/gh-pages/_layouts/page.html) and [here](https://github.com/Qmerce/static-testing-site/blob/gh-pages/_layouts/post.html), and as well can be changed.

## Forking
When forked, the site URL will be changed, so it should be updated [here](https://github.com/Qmerce/static-testing-site/blob/gh-pages/_config.yml#L8).
