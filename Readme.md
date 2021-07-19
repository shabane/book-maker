# book-maker

### Description
> this is a simple way to create your book.
>
> 'pelican' is tool to create static-blog, i changed the default theme to a bootstrap theme,
> so now entire page of the site are responsive, and it's look like a book.
> 
> if you want to use this, just download it and read the documentation in the project.
> every thing you need to know about the file and directory structure are there.

### how to use
> 1. make sure python and pip are installed.
---
> 2. install pelican and markdown by this command ```pip3 install pelican markdown```
---
> 3. download the book-maker ```git clone https://github.com/shabane/book-maker.git && cd book-maker```
---
> 4. in 'book-maker' directory there is a 'content' directory in this directory we have two other sub-directory,
> named 'chapters' and 'pages'.
>
> 4.1 each season of your book should be under the 'chapters' direcory. your file shoud be a markdown file.
---
> 5. in 'pages' directory there is 5 file
>
> 5.1 'about.markdown' describe about your self and your book in this file.
>
> 5.2 'discuss.markdown' if you have a disscuse group, link it here.
>
> 5.3 'download.markdown' the downloadable version of your file shoud be here.
>
> 5.4 'index.markdown' this is the cover of you book.
>
> 5.5 'support.markdown' if you need to supported by other people write your payment address here.
---
> 6. dont forget to change some name and simple config in the 'pelicanconf.py'(such as time-zone) that is it, you done.
---
> affter all, whene you done, enter this command in the directory of your project ```pelican```
>
> now in the 'output' folder there is your site/blog/book. to see what you done enter this command ```pelican --listen```
> so now you can go to [127.0.0.1:8000](127.0.0.1:8000) in your browser to see the site.
---
> the last tip is to add theas fild to each page.
>
> |field in each page|require|
> |:-----:|:-----------------:|
> |Title|*|
> |Date|*|
> |Modified|optional|
> |Category|optional|
> |Tags|optional|
> |Slug|optional|
> |Authors|optional|
> |Summary|optional|
>
> #### for example:
> ```Title: My super title
> Date: 2010-12-03 10:20
> Modified: 2010-12-05 19:30
> Category: Python
> Tags: pelican, publishing
> Slug: my-super-post
> Authors: Alexis Metaireau, Conan Doyle
> Summary: Short version for index and feeds```


