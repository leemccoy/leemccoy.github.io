## Welcome to my website's repository!

~ Built using [Quarto](https://quarto.org/) and deployed with [GitHub pages](https://pages.github.com/) ~

https://leemccoy.github.io/

***
The repo used to create the website: https://github.com/leemccoy/leemccoy.github.io
Make changes to the website in RStudio!!
The organization is pretty straightforward:
1. The _quarto.yml establishes the structure of website (headers/footers/tabs, also the "get in touch" tab)
2. index.qmd controls the landing page
3. about.qmd controls the information in the about tab
4. Ignore the posts and projects. We can update these if you decide you want to add a blog and/or project information (I think this would be cool, but not worth the effort now).
5. Don't touch anything else unless you really want to fuck things up!

To see the website once you make changes, go to the terminal and type:
quarto preview

Prior to committing, you will need to render the site (this converts those .qmd docs to html):
quarto render

Then do the normal add, commit, push. This can be done from the GUI in Rstudio, or in the terminal:
git add -A
git commit -m "Render site"
git push

***

Here is the information I used to create the website: 
https://ucsb-meds.github.io/creating-quarto-websites/

The free icons I used are from here:
https://fontawesome.com/search?ic=free-collection

***

~ This website was created by Melanie Frazier using a template and instructional materials from Sam Shanny-Csik
She teaches (amazing) workshops on building Quarto websites for the Bren School's [Master of Environmental Data Science]() (MEDS) program. 
She generously provides open source materials if you're looking to get started on your own webiste 😊

- [Creating your personal website using Quarto](https://ucsb-meds.github.io/creating-quarto-websites/)
- [Customizing Quarto Websites](https://ucsb-meds.github.io/customizing-quarto-websites/#/title-slide)
- [Adding a blog to your existing Quarto website](https://samanthacsik.github.io/posts/2022-10-24-quarto-blogs/)
