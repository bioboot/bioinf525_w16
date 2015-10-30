# BIOINF 525: Foundations of Bioinformatics and Systems Biology
BIOINF525 course website for 2016, see:  http://bioboot.github.io/bioinf525_w16/


This is a simple [jekell based static site](http://jekyllrb.com/docs/home/). 

To view locally on your own machine (i.e. before pushing or submitting a pull 
request to this [bioinf525_w16 GitHub](https://github.com/bioboot/bioinf525_w16) repo) 
you will need to have the **jekyll** and **github-pages** gem setup, i.e.:

Consider updating RubyGems first (likely need sudo for these).

	sudo gem update --system

Then install the Jekyll Gem and the GitHub Gem

	gem install jekyll
	gem install github-pages

Optional: Pygments python based syntax highlighter

	pip install Pygments


## Basics of Jekyll websites
Jekyll websites are configured based on the contents of the various underscore prefixed files and folders. You can find out more about these here: http://jekyllrb.com/docs/structure/

However, most likely you will want to leave most of these alone and just add  
content to the day{2,3,4,5}.md files and create new files in the **class-material/** 
directory (i.e. add lecture slides, handouts, cheat-sheets etc.)

Please remember that all content is on the **gh-pages** branch! 
So you will want to be working on this branch and push back to this branch.

A typical workflow for folks that have been added as **"Collaborators"** would look something like this:

	## One time only clone
	git clone https://github.com/bioboot/bioinf525_w16.git
	cd web-2015

	## Edit your files (e.g. module3.md)
	vi module3.md

	## Check changes localy
	jekyll serve

	## Pull recent changes
	git pull origin gh-pages

	## Stage, commit and push your changes
	git status
	git add module3.md
	git commit -m "Your msg about changes"
	git push origin gh-pages


## How this site was built
Basic setup entailed:

	jekyll new 2015
	cd 2015
	## Edited site title, description etc. in _config.yml
	vi _config.yml  
	rm -rf _posts/   ##  we are not going to have a blog
	mv index.html blog.html  ## can delete later

Create a simple index.md file and have a quick look with 'jekyll serve'

	jekyll serve

After some more content addition I then followed the [instructions for adding 
to GitHub pages](http://jekyllrb.com/docs/github-pages/).

