Blogging template for GitHub pages
==================================

	buzzwords:
	- jekyll
	- responsive web design
	- microformats

Usage
-----

- Fork
- Rename the repo to username.github.com
- Push something to your renamed repo to trig GitHub to generate the page
- Browse to http://username.github.com to see the result

If you like to polish the default design or know some awesome Jekyll magic, I'm happy to merge pull requests.

__Try locally__

	git clone https://kblomqvist@github.com/kblomqvist/ghblog-template.git
	cd ghblog-template
	jekyll --server

Now open your browser and go to _localhost:4000_.

Did not have Jekyll? To install Jekyll you have to have Ruby and Ruby gems installed. If you do not have these yet, it is recommended to install Ruby locally:

	# MANDATORY! Install a bunch of support software
	sudo aptitude install build-essential curl autoconf \
	zlib1g zlib1g-dev bison openssl libssl-dev \
	libsqlite3-0 libsqlite3-dev sqlite3 libxml2-dev

	# Install RVM locally (no sudo!)
	bash < <(curl -s https://raw.github.com/wayneeseguin/rvm/master/binscripts/rvm-installer)

	# Install Ruby 1.9.3 locally (no sudo!)
	rvm install 1.9.3

	# Use Ruby in this login session
	rvm use 1.9.3

Now you are ready to install Jekyll (do not use sudo)

	gem install jekyll 

License
-------

The code that this project consists of is licensed under MIT and is based of MIT-licensed work by [Tom Preston-Werner](http://github.com/mojombo/jekyll).

The design of the default template is based on [initializr-template](https://github.com/verekia/initializr-template).
