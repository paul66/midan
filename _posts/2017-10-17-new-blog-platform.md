---
layout: post
title: Migrating my blog platform 
featured: false
author: paul
tags: []
image: '/images/posts/2017/10/jekyll-logo.png'
comments: false
---

Up until now I have hosted my blog on the Ghost platform. I paid a monthly subscription (billed annually) to use their service to avoid having to install and manage a blog platform myself. Ghost is a joy to use but the cost occurs whether I publish 100 posts a year or zero posts, so it's clearly easier to justify if I'm posting regularly. But I don't publish content regularly and with my subscription renewal coming up in December, I decided it's time to take the plunge and move my blog to a cheaper platform. Enter Jekyll!


## What are Ghost and Jekyll?

[Ghost](https://ghost.org) is an open-source online publishing platform. You have the choice to download the Ghost platform and install it on your own server for free or you can subscribe to a Ghost(Pro) account and have your blog hosted by Ghost (in the same way you can host your own Wordpress site or create an account at Wordpress.com).

If you self-host, you will have to manage the server environment, install and configure the Ghost server application and install updates as new versions are released. With a Ghost(Pro) account you are paying to have all that taken care of by someone else.

[Jekyll](https://jekyllrb.com/) on the other hand is a static site generator. It transforms plain text (markdown) files into static websites and blogs. It doesn't require a database and supports permalinks, categories, pages, posts and custom layouts, which makes it ideal for generating blog sites.

The drawback is that you run it from the command line (which is a big barrier to entry for some) and there is more set up and configuration than is required with a hosted solution. However, if you are comfortable with all that, once set up it is pretty simple to publish new content.

So if Ghost(Pro) is analogous to hailing an Uber, Jekyll would be like building your own kit car.

Jekyll is free to use but you still need to host your site somewhere. The good news is that it has very tight integration with [Github Pages](https://pages.github.com) so not only can you can benefit from Git version control but also automatic hosting on Github Pages...assuming you are comfortable working in a technical development environment.

## Why move from the simple Ghost(Pro) environment to the more complex Jekyll?

I originally chose the Ghost platform for its elegance and simplicity. I was happy to pay a nominal $5/month subscription to avoid hosting costs and the time it would take to administer my own website. So I signed up and started blogging.

I soon realised that whilst I enjoyed the writing process, I was never going to be a prolific blogger. In my first couple of years I was actually quite inconsistent. I had months of posting 3 or 4 times, but then could go months without posting anything. All the time paying Ghost my $5/month.

Then in 2016, having established a good name and solid customer base, Ghost unsurprisingly increased the cost of the cheapest Ghost(Pro) plan. It went up from $5/month billed monthly to $19/month billed annually or a whopping $29/month billed monthly. However, I liked Ghost so stuck with it, opting to pay annually. Then recently Ghost made an announcement that suggested that their future focus is likely to be journalism and news publications and the likely revenues that will flow from large corporate clients using their platform.

So now my blog is now costing me $228 a year rather than $60. Given my rate of output, that's a crazy cost per post, especially considering there are plenty of free alternatives. It also got me thinking about the difficulty in moving blog platform when all the content (text and images) are saved on a 3rd party's servers and only accessible while I continued to subscribe.

So with my Ghost subscription renewal coming up in December I decided it was time to find an alternative.

The conclusion I came to was that:

1. I would rather manage my own blog site than pay over $200/year
2. I wanted my content saved locally (and backed up in the cloud) to avoid future migration issues
3. I wanted to continue to write content in markdown
4. I wanted to avoid a database driven solution if possible

I had seen Jekyll (in my job as a web developer) and understood how it worked. I'm familiar with using the command line and have used Git version control. So the technical barrier to entry was fortunately not so great for me. I was attracted to the idea of having control of my own site and a system that re-generated the site whenever new content was added. And most importantly it was free and ran on my local machine.

The last piece of the puzzle was hosting. I didn't want to use a web host (more cost) and so was very happy to read that Github was tightly integrated with Jekyll and provided free hosting through their Github Pages platform. It was a no-brainer really: free source control and publishing rolled into one - count me in!

## What's in a theme?

Rather than develop the blog theme from scratch I sourced some open-source themes and tried them out. They all work in the same way so once you understand one, you pretty much understand them all. It definitely helps if you understand front-end web development and are happy to get your hands dirty in the code, tweaking layout and include files and editing configuration files. But a theme got me 95% of the way there.

## Migrating old content

I am going to start publishing brand new posts first and migrate my old posts over time. An important job that needs doing is to compress all the photographic images, which are way too big currently and consequently load very slowly. But I'll get there as fast as I can.

## New domain name

In moving from the Ghost platform I would need a new domain name. The default URL you get with Github is not very friendly but it does allow you to use a custom domain. So I have spent some of the money I have saved by not renewing my Ghost subscription I have bought a custom domain name: _therhythmof.life_.

## Onwards and upwards

So all that remains is for me to try harder in 2018 to write more often and more consistently. Now where have I heard that before...? 