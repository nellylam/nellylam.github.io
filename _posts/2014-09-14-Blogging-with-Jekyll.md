---

title: Week 9 - How to Ask Questions
layout: post

---

Working with Jekyll was a big step for me. I knew I had to do it because any changes I made to headers and navigation bars meant repeating it on all my other pages, and I knew that was too repetitive and inefficient.

The transition to Jekyll was an arduous one, and I would say, I did not think I would be putting in so many hours to figure this out. Although, once I had everything (almost) set up and working, it has made it much easier to make changes to my header and navbar.

It takes a long time to figure out how to "serve" the site locally to view my changes live. When it was non-Jekyll, the browser can just be refreshed. But with Jekyll, I had to set the 'baseurl' to my local file location. I found that doing it this way did not always accurately render my page.

Eventually, this became my workflow:

1.	edit files and save
2.	in terminal: jekyll build
3.	git status
4.	git add .
5.	git commit
6.	git push
7.	refresh browser

This would be the workflow I use if the server was not rendering correctly. When done this way, I see it live online. The downside is that if there are bugs, then it would already be live.

After I implemented those changes, I got feedback from some friends about this blog, and I decided I want to take it in a direction that was more personal and less anonymous.

On the homepage, for example, there was no mention of my name. Someone visiting the site would not even know this is a personal website. So I swiftly changed the title of my blog and added my name.

I also decided to integrate font-awesome icons in my site to add more graphics. That was also a struggle. I sought help from the Google+ community as well as Stack Overflow. Turns out Github will not support plugins for Jekyll and it will not build your site, which means my updates didn't get hosted.

I found that I couldn't use the Font-Awesome Jekyll plugin. I just had to do it the normal way, by linking the font-awesome css and then using their special classes in the html tags.

I think that the fluidity of the site still needs a lot of work, but the workflow has gotten a lot more D.R.Y. This will always be a work in progress, but I think I have a clearer direction after this exercise.

