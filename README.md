# yelp-ws
Mockup of a New Yelp Website made by Wintersmith


# Preview

	$ wintersmith preview

The site can now be accessed at [http://localhost:8080/yelp-ws](http://localhost:8080/yelp-ws)

Note that the base path is currently set to `resume` so you must include `resume` in the url.

# Deploy to gh-pages

	$ wintersmith build

	$ git add build

	$ git commit -m 'build'	

	$ git subtree push --prefix build origin gh-pages

Then, the page can be accessed at `http://[your-github-account-id].github.io/resume`


