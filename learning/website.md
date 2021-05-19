---
layout: posts
title: Website
---

## Background
When I decided to make a website I was keen to remind myself that it only needs to be simple and the content informative to be effective. I'm not really inclined to learn complete web development.

I've certainly made plenty of mistakes and don't proclaim this site to be anything special. However I've still managed to learn a few bits and pieces putting this together. I'm under no illusions that a lot of people will find what I'm doing very basic. At the very least these notes are a reminder and record for myself, but if there is a slim chance they could be useful to someone then all the better.

## Layout and organisation
* Draw a layout
* Have some sort of plan
* Be organised (folder structure)

## Markdown
I spent a little time learning html, however as my focus here is not on building amazing websites, when I learnt about the simplicity and ease of use of markdown (especially for use on github pages), it seemed the obvious choice. I still use the odd bit of html here and there but that's just my preference

Some points on using markdown
* For a line break, markdown syntax is 2 spaces. Great for convenience but I prefer html `<br>` for visibility
* Markdown needs spaces, and trips up without them. For instance after '#' for headers; without a space it won't format properly

## Images

### Naming
It's definitely a good idea to name your images something sensible.
I've read this can be good for search engines and all that stuff, but it also makes your own life easier.
A fairly typical convention that I try to use is "folder_or_use-photo_name-widthxheight"
I'm definitely no expert, but jpegs seem to be the best choice for plain old website images (from a quick web search...)

### Resolution
Initially I thought it was best to resize my images before uploading as this would keep the file sizes to a minimum. However I quickly realied that you are going to lose out in quality that way. 

I wanted a small image for the introduction section of my adventures page, so I used: <br>
<img src="/images/learning/website/resolution-300x225.jpg" alt = '300 by 225 pixel image of me sitting down on a hill'/> <br>
Which is 300 x 255 pixels and 22KB file size, pretty clearly not great quality

It seems that would I should actually do is resize the image first to bring it to a more manageable file size, then resize it again to the size I want on my page. As a demonstration, for my own sake as much as yours, here is a photo of me having a sit down in descending resolutions, with associated file size <br>

###### Initial resized image, displayed at 400 px wide for comparison - 300x255 - 22KB
<img width="400" src="/images/learning/website/resolution-300x225.jpg" alt = '300 by 225 pixel image of me sitting down on a hill'/>
<br> This size was poor quality already, so it's not surprise that displaying it slightly larger makes it even worse again

###### 500x375 - 64KB
<img width="400" src="/images/learning/website/resolution-500x375.jpg" alt = '500 by 375 pixel image of me sitting down on a hill'/>
<br> Only slightly larger size and this image already looks pretty good. By zooming in (or displaying the image any larger) its pretty clear that the quality has been reduced

###### 1000x750 - 224KB
<img width="400" src="/images/learning/website/resolution-1000x750.jpg" alt = '1000 by 750 pixel image of me sitting down on a hill'/>
<br> At this size, the image looks great to me. I can't confidently tell the difference between this and the higher resolution images below, although by zooming in I can see the difference

###### 2000x1875 - 820KB
<img width="400" src="/images/learning/website/resolution-2000x1500.jpg" alt = '2000 by 1500 pixel image of me sitting down on a hill'/>
<br> Even zoomed in, I find it difficult to discern a clear difference between this image and the original file below

###### Original image - 4000x3000 - 3.5MB
<img width="400" src="/images/learning/website/resolution-4000x3000.jpg" alt = '4000 by 3000 pixel image of me sitting down on a hill'/>
<br>

##### Summary
A web search of this question will give you all sorts of answers, and its pretty clear that really it comes down to what you are trying to show with your image.
It seems to me that images around ~**1000x750** will suit nearly all my uses and this provides a small enough file size to load easily. I can always use larger sizes for special cases as required.

## CSS
I might learn some CSS in the future to go with the bare bone html I've picked up. That way I could have a bit more control over my site layout


### Jekyll
---
details go in here
(title, layout etc)
---

Cheat get around: remove all posts from _posts folder in order to remove them by default from homepage

Added (copied) if statement to remove subscribe button from footer

Sorted out my header section: config file using the customer header titles section