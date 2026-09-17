# Decision log

## 1. What did you set out to build, and what changed?

What you wanted at the start, and what is actually live now.
Name one thing you dropped or added along the way, and why.

I wanted to build a portfolio website website that links to my various projects and gives some information about myself. The live version of the website is accurate to this original vision with
mostly minor alterations to the original plan. One thing that I added along the way was a hobbies section under my projects to elaborate more on my "about me" section and show some photos.

---

## 2. A fork in the road

Name one real choice where you could have gone two ways.
Plain HTML or a framework. One page or several. Your own CSS or someone's template.
What goes on the front page and what does not.

Say which you picked, what the alternative was, and what you gave up by not taking it.

"There was no alternative" is not an answer. Find the fork.

The largest choice I made was my choice of template. I explained my idea and used claude design to create several design templates, choosing the current one to get a basic template before I added information.
Although, the current design and the template have several differences that I would work out over the course of creating the website including removing several pieces of superfluous text and adding an email contact
which did not exist in the original design.

---

## 3. Where you overruled the agent

One time Claude suggested, wrote, or claimed something and you did not take it.

What did it do? How did you notice? What did you do instead?

If it genuinely never happened, say so plainly, and then say what you would have had to
check in order to notice. Being honest here costs you far less than a story you cannot
defend when you record your video.

I overruled almost all of the text the AI wrote and rewrote it myself. I read the text noticing that the voice of the writing was not accurate to myself and was quite unappealing to me
so I decided to rewrite it to match my writing style.

---

## 4. How you know it works

What check did you run, and what did it tell you?

Then the real question: **what would have made this check fail?**
A check that could not have failed is not a check.

Link to your `verification/` folder.

I opened the live site on my main browser, ingognito browser, and phone and the website loaded with no issues. Also, fetched the live URL with curl and it came back with no problems.
These checks would have failed. If I had not uploaded or incorrectly uploaded my photos fetch.txt would have shown an error when fetched. Also, if the url failed to pull up the site it would have failed.

---

## 5. What is still wrong

One thing on your own site that is not right, not finished, or that you do not
fully understand.

What would you do next, and how would you find out?

One thing that may be an issue is the majority of the page's weight is contained within the one GIF I used on the page. I tried to compress it but the compression made it look far too bad. 
I would find a better method of compressing the gif, shorten it, or potentially remove it if the file size ended up being a problem.
