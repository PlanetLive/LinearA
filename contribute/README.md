## Make Edits and Additions

Contribute updates and images, add your comments as GitHub issues, and reuse our pages as submodules in your projects and models.

You can include as a [submodule within a GitHub site](/localsite/start/submodules). 

	git submodule add https://github.com/PlanetLive/LinearA LinearA
	git commit -m "[repo] submodule"
	git submodule update --init --recursive

Include our localsite repo for common navigation javascript:

	git submodule add https://github.com/ModelEarth/ModelEarth localsite
	git commit -m "[repo] submodule"
	git submodule update --init --recursive

Lastly, push within Github Desktop. (The repos will already be commited.)
Then you'll see the submodules in your main Github website and you can view it at yoursite.github.io/LinearA or your custom domain.

