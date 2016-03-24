### 1. Who are you?

Hi, I'm Ismail HAMADI(Hamza for short), An [algerian](https://en.wikipedia.org/wiki/Algeria) student from the university of science and technology Houari Boumediene( [U.S.T.H.B](http://www.usthb.dz) ) where i'm persuing a first year master degree in Software Ingeneering.
I'm reachable on the internet under the following addresses : 
* Gmail at [ham.ism.official@gmail.com](ham.ism.official@gmail.com) or [ismnoiet@gmail.com](ismnoiet@gmail.com).
* Github at [@ismnoiet](https://github.com/ismnoiet).
* My new jekyll blog at [ismnoiet.github.io](https://ismnoiet.github.io)
* Google plus at [+hamisml](https://plus.google.com/u/0/+hamisml).
* Twitter at [@ham_ism](https://twitter.com/ham_ism).
* And some times asking and answering questions on [stackoverflow](http://stackoverflow.com/users/3863740/hamism).

### 2. What do you want to do?
I want to make  jekyll simpler and easy to use i've started by creating [jekyll-post-generator](https://www.npmjs.com/package/jekyll-posts-generator), a Nodejs package to create posts and 
categories for jekyll. Now after some research i'm planning to convert the previous package into  a jekyll [command plugin](https://jekyllrb.com/docs/plugins/#commands). I have also started recently developing jekyll plugin to add social media links, so instead of using the current method which is storing  social media images under the folder ``_includes``(like **icon-twitter.svg** and **icon-github.svg**) and then hard code the HTML view of each social media link inside ``_includes/footer.html`` as an example :
```ruby
	# this is hard coded
	{% if site.twitter_username %}
	   # ....	
	{% endif %}	
```
The solution could be to add  ``social_media`` hash inside ``_config.yml``, something like  this : 
```yaml
social_media:
    github: github
    twitter: twitter
    gplus: gplus
    facebook: facebook
    dribble: dribble
    behance: behanc
```

And now inside ``_includes/footer.html`` we can take advantage of  [liquid for loop](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers) to generate all links automatically without having to hard code every single entry. for example we put inside ``_includes/footer.html`` the following code:
```ruby
	{% for social in site.social_media %}
		# display each item
	{% endfor%}
```

The interesting thing about the previous ideas is that they are very specific,faisable and issential(at least in my point of view, due to the fact that they eliminate a lot of unnecessary repetitive work).

I would like to work on any jekyll related project, especially [Internationalization / localization support for Jekyll](https://github.com/github/mentorships/issues/106), [Jekyll community plugin and theme directory](https://github.com/github/mentorships/issues/105).

Other ideas can come along the way, so this just an ideas list to  start with.

### How are you going to do it ?

Planning and scheduling are the key to finish any kind of work, for the software field it is no exception. Therefore i'll be respecting the following planning: 

#### Timeline
**March~April:** Get familiar with jekyll ecosystem and continue to learn more about it, its [templating engine](https://github.com/Shopify/liquid/wiki) and [plugins](https://jekyllrb.com/docs/plugins/).

**April~May(Before official starting):** Continue to learn. Make some contributions and try to design a good architecture, add test cases whenever possible.

**23th May:** The official commencement.

**1st-3rd Week:** Refactor the project.

**4th Week:** Fully test it.

**20-27 June:** Official mid-term evaluation.

**5th-6th Week:** Add documentation.

**7th-8th Week:** Improve the documentation and try to fix issues.

**9th-10th Week:** Continue fixing issues and trying to implement new features.

**15 ~ 23 Aug:** Submitting code and evaluations.

**30th Aug:** Official final evaluation.


### Why you?

Because i'm pasionate about this field and i'm a fast learner, i've learned 
a lot from open source projects through chat rooms and reading through their source code.I want to contribute and give back to the community.
Working under the eyes of a create company like Github is an honor, pleasure and a motivation to push my self and improve my skills continuesly.
I would love to be able to say i worked for Github.

Here is a list of projets and packages that i've created or contributed to : 

1. [nodeschool-workshop](https://www.npmjs.com/package/nodeschool-workshops) 
3. [Bower​Injector](https://packagecontrol.io/packages/BowerInjector)
4. [text-to-format](https://www.npmjs.com/package/text-to-format)
5. [jekyll-posts-generator](https://www.npmjs.com/package/jekyll-posts-generator)
6. [Google-Chrome-JavaScript-API-Auto-complete](https://github.com/ismnoiet/Google-Chrome-JavaScript-API-Auto-complete)
7. [PHPCRUD](https://github.com/ismnoiet/PHPCRUD)
8. Contributed to [SJSJ](https://github.com/HugoGiraudel/SJSJ) by creating [JSJargon](https://github.com/ismnoiet/JSJargon)
9. Contributed to [Slim-PDO](https://github.com/FaaPz/Slim-PDO)
10. Contributed to [json-to-json-schema](https://github.com/mohsen1/json-to-json-schema)
