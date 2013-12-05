---
layout: post
title: "A young person’s guide to actually building something"
date: 2012-12-14 20:21:28
categories: startups
image: http://zmitri.files.wordpress.com/2012/12/8eced-square-feature-scaled1000.jpg?w=500&h=500
published: false
---

In my [last post](/startups/2012/12/07/young-persons-guide-to-quitting-your-job.html), I spoke about why I went from being a salaried employee to starting my own company, [Backspaces](http://backspac.es). In this post I’m going to outline the approach my team and I took to actually building something over the course of 6 months.

Hopefully this will provide you with some inspiration or insight into our product development process. It’s also a pretty cool account of how we went from a team with no Objective-C/iOS experience to, just this week, getting featured by Apple.

#In the beginning, there was nothing, so build!#

##Starting with nothing can be daunting, but in a startup it’s the default.
Having some idea of what you want to build is very important at the beginning but having a grand vision means nothing without an actual product and serious traction \[1\] or revenue.

##When it’s your company, you need to be willing to build or learn how to build whatever it takes to make it happen.
I didn’t know Objective C or iOS programming when I came up with the idea for Backspaces, so I asked the best Objective C developers \[2\] I knew how I should learn it. They suggested I read [Aaron Hillegass’ book](http://www.amazon.com/gp/product/0321821521/ref=as_li_qf_sp_asin_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0321821521&linkCode=as2&tag=arbor02-20) \[3\] — so I read the entire thing, did every single practice problem over the course of 2 days, and then built the first prototype of Backspaces. It may sound a little ridiculous, but it’s exactly the type of thing you need to be willing to do.

#Iterate like crazy and get user feedback

##“Treat every line of code as if it’s going to be thrown away one day.” \[4\]
This is probably the most understated yet useful piece of advice I’ve ever received. Coding is just as much a form of self expression as any creative medium, so unless you explicitly approach a project with the mindset that it’s going to be thrown away you can get very attached to your work. The first 3 iterations of Backspaces were almost 100% rewrites because I wasn’t thinking about the code as the product, I was thinking about the product itself.

##Introducing the Minimal Vomit-Inducing Product.
Not only did we have our first prototype built in 3 days, we had beta users within the first 2 weeks. We didn’t even wait for an MVP to put it in the hands of users — we gave them the first product that wouldn’t make them sick. I admit, some of the UI and UX was downright confusing, but we were able to focus on adding in the features we needed instead of worrying about pixels.

##Work hard, talk to users even harder.
Until we submitted our app to the store, we worked in 2 week iteration cycles and then took a half week off to observe usage and talk to users. Working hard is important, but observing how people were using the app, and talking to power users were the most important things we did early on. It won’t necessarily provide you with some Eureka moment, but little suggestions start to add up. The original idea for Backspaces was to track where you went and share walking routes, but everything changed after we put it into the hands of creative users. I can literally point you to the 2 Backspaces \[5\] that made us think of the app as more than just a tool or utility for mapping where you go.



#Open source code and culture can be very powerful

##Strategically open sourcing something people want can be very valuable.
Although the Objective-C open source community is growing, it’s still very small compared to the Ruby and Python ecosystems. If you make something cool in Objective C, you will get a lot of attention for it. Mobile and iOS development is still very “wild west” in comparison to web development — one or two talented developers (like Loren Brichter or Mattt Thompson) can outperform entire teams and command the attention of iOS devs everywhere.

We decided to open source an Instagram-like camera picker we built for fun over a weekend. It now has hundreds of followers and watchers, and is being used in a number of iOS apps. By the way, it also brought in hundreds of Backspaces downloads and got us an article on The Next Web \[6\].

#From idea to App Store in 3 months

##We decided to run our own incubator — but without the funding and famous entrepreneurs and investors to back us up.
I’ve always believed that there’s something special about the amount of work you can get done in 3 months. It’s enough time to create something substantial, but at the same time requires alacrity. And so, we gave ourselves a 3 month deadline to get our app in the store. I moved out of Manhattan, and we rented a floor of a house in Sunset Park, Brooklyn, where there were far fewer distractions — I suspect this is one of the reasons YC makes you move to Mountain View. For the first three months we built features, iterated on those features, and talked to users — that’s it.

##The App Store approval process isn’t that bad.
If you run a proper beta test with Testflight before you release to the store, everything will seem like a breeze. It’s true that you need to get used to the idea of provisioning and distribution profiles, but other than that, I haven’t had any troubles with the App Store process. Just assume it’s going to take any where from 7 to 14 days for them to approve your app — and yes, an App Store employee will download and open your app (sometimes only for a second or two) to make sure it works. It seemed foreign to me at first, but I’ve learned to respect the process and the advantages it has over a completely open system.

#Just keep going

##I don’t have much more to say except that everything changes once you’re in the App Store.
You’re competing against giants like Facebook, Google, Angry Birds, Twitter, and Instagram for mindshare — nobody is going to notice you unless you’re very lucky. If you’re going to succeed, you’re going to need to love what you’re doing, and you’re going to need to be tough as nails. It’s not easy, but it will all seem worth it once you start to see real users using your app. Getting featured by Apple is just the icing on the cake.
<br /><br />
##NB: This is the second post in a series. See the first [here](/startups/2012/12/07/young-persons-guide-to-quitting-your-job.html).

\[1\] Traction is a word that gets thrown around a lot by investors, but often isn’t well defined. I get the impression that “traction” starts around 10,000 active users.

\[2\] The team at [Embark](http://letsembark.com) 

\[3\] The Big Nerd Ranch Guide to iOS Programming is more useful than the one on Objective-C

\[4\] [Daniel Doubrovkine](http://twitter.com/dblockdotorg), Lead engineer at Artsy.

\[5\] Aanand’s [What U know about Backspaces](http://backspac.es/r/4meLz27LlN) and Patti’s [fog light night](http://www.backspac.es/r/FabeIe7jBz).

\[6\] [Open source instagram](http://thenextweb.com/dd/2012/08/22/heres-open-source-instagram-clone-develop)
