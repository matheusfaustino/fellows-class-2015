Fellowship sprints
===================

# What is this?

We've decided that our [Mozilla Science Lab](https://www.mozillascience.org/) [fellowship](https://www.mozillascience.org/fellows) projects will be fundamentally **collaborative** and **exploratory**.

Each of us will propose a set of sprint projects. The projects can be anything from an idea to an existing tool, resource or community. Crucially, it must be possible to make transformative progress on the project by both of us working on it intensively for [X WEEKS] - so a 'sprint' in this context means a concentrated burst of activity towards a specific goal.

Once we've fleshed out the sprint ideas, critiqued them, taken feedback and improved or filtered them out, we will commit to an initial set of sprints. Both of us will work on each sprint together.

This document is a place for us to develop the logistics of doing sprints, figure out our individual sprint project ideas, and get feedback on all the above.

# Sprint project ideas

## Joey

(I moved the old ideas to another doc - see Fellowship Idea Projects - so if you don't see them here, don't worry!)

### Viz Sprint

Tags:

- Sci-comm
- Community Outreach

#### Motivation:

- Many researchers want to communicate their research to the public especially using web based visualization, but don't necessarily have the skills or the knowledge on how to do so or where to start. While there are many platforms that can produce and host charts, graphs, and text, some data stories are better told with more custom interaction and visualization. 

- There is an importance in building up interest for science communication at the local scale. By making a science communication more visible at the university (e.g. grads and faculty see their peers getting their work out there), we can:
	- inspire other researchers to invest into sci-comm projects
	- highlight sci-comm as a means of enaging with science for people who aren't necessarily scientists, but who want to participate (e.g. developers, designers, creatives)
	- enhance public understanding of what research is happening at UBC


#### What is it?

- The Viz Sprint is about developing web based science communication projects with researchers and their data. It is aimed to help researchers who want to get their research out into public by using visualization and the web. 
- I will work directly with researchers across UBC to build out a projects that help to communicate their work and their data.
- The Viz Sprint will essentially be about building collaborations between researchers and quickly iterating and prototyping visualizations with web technologies.
- The Viz Sprint will have several tangible outcomes:
	- the visualization project
	- project documentation / tutorial on how to build the thing.
	- a handy guide of helpful "do's" and "don'ts" for collaborations between researchers and creatives/developers might help to guide other researchers looking to engage in these types of relationships.	
#### Moving forward

- Tentative Project list:
	- Vancouver's Urban Greenhouse Gas Emissions and Impact 
		- I plan to start the sprint by working with my supervisor, Andreas Christen, to develop a web app for visualizing greenhouse gas (GHG) emissions in the city of Vancouver using data produced from models and measured in-situ. 
	- A Changing North American Biogeoclimate Zone Map 
		- tdb
	- Soundscapes of Northern BC in danger from oil pipeline development (pending approval from local community)
	- ...
	

### Mapping FUNdamentals
(Thanks Aure for that one)

Tags:

- education
- maps

#### Motivation

- There are a TON of resources online around web mapping and how make them. More often than not, if you have a question about how to do some task, someone has probably already asked it on stackoverflow and received an answer. This is great, but often times finding the right search terms will make or break your ability to find that crucial answer to your mapping question. 
- With online code sand boxes like codepen and jsfiddle, we are able to play with examples online without setting up local webservers or creating a bunch of files on our machines. It's awesome! Wouldn't it be great if you could play with API references online? Personally I love the [P5.js reference](http://p5js.org/reference/) and think that if web mapping had a really nice code sandbox like this, the world would be a supremely better place.

#### What is it?

- Mapping FUNdamentals is an interactive web mapping reference.
- It is aimed at taking (sometimes confusing) web map API references and making them more accessible and interactive so that beginners and experts alike can learn from and reference examples in a coherent way.
- I imagine it will look a lot like the [P5.js reference](http://p5js.org/reference/). I will start with leaflet.js, but it could be extended to Mapbox.js or d3.js examples etc. 
- By developing an interactive mapping "dictionary", I hope to develop a place were users will be able to better search for the mapping component they are interested in and learn that web maps, like everything else, can be deconstructed like legos and built into new and different and more awesome things.



<!--### Creatives for Science App

tags:

- sci-comm

- Creatives for Science is a social networking app aiming to bring scientists and creatives together.
- Creatives for Science aims to connect -info communicators- with -info generators- to bring science to the public and make science more accessible.
- Creatives for Science links talented people together in the local community to work on projects to enhance public understanding of science, technology, and the environment.
- Creatives for Science is a mobile and web app that simulates the experience modern "dating" apps - could be an interesting way to gain usership and develop local interactions.
- Thea Boodhoo - made the initial project page for [Creatives for Science](http://www.creativesforscience.org/) is on board with the development and wants to aid in the efforts.
- similar projects: 
	- [http://www.creativesforscience.org/](http://www.creativesforscience.org/) 
	- [Solvers](solvers.io)
	- [Mozilla Science Collaborate](https://www.mozillascience.org/collaborate)

### Learning Bank (new name in the works)

tags:

- education

#### Motivation:

Learning is best achieved when we have domain specific examples to work with 

#### What is Learning Bank?

- Learning Bank is browser based/desktop tool that you can drag and drop links that feeds into a database of resources for learning tools/skills - e.g. how to make a web map with javascript, how to run a T-test in R, etc. 
- Learning Bank uses web scraping to try and pull out the relevant programmng language and also the subject/data type the tutorial is working on. 
- users can then browse learning by langugage but also domain or data examples that are relevant for them.
- The idea then is that PrismDB will become a big database of helpful links and tutorials that are relevant for learning new skills and tools, etc that can be navigated and filtered in an enjoyable way.
- Ultimately PrismDB is a database of domain examples so that we can learn with the data and things that align closest to us. 
- Other technical notes:
- we then create a backup of the reference to save the content
- duplicate links without new content won't be saved - but upvoted - only if content has changed then we can keep the data. 

#### Related Links:

- like these, but it all goes to a community repository: 
  - http://lifehacker.com/5961188/whats-the-best-way-to-save-all-the-useful-articles-i-come-across-online
  - https://getpocket.com/
  - https://www.instapaper.com/
  - http://minilogs.com/

- http://www.labnol.org/internet/archive-web-pages/20192/

### Sketching Web Geography

tags:

- 
- education

#### Motivation:

- GIS education in universities is broken - we rely on proprietary tools, antiquated and boring examples, point-and-click software that lead to PDFs for sharing outputs.
- This is so lame and leading to a whole generation of confused and ill-functioning students.
- Also, the future of GIS is in the web - it's already happening (e.g. CartoDB), but there's a lot more to be explored.
- Sketching Web Geography?
- Sketching Web Geography is a web-based book that is aimed to protoype a new aspect of geo education - GIS meets the web. 
- Fundamental to this geo education is to integrate programming and the idea of sketching with code to build web based maps. 
- I propose to use modern web technologies such as P5.js, Leaflet.js, Turf.js, D3.js, and Github, and others, to put together a book that tries to capture the lego block approach to building and making things - in this case maps - with code.
- The book would start with P5 - learning the basics of the web then move to integrating maps.
- Each chapter is a lesson - e.g. intro to computation, geo data formats, making a map UI, etc.
- Best feature: a "lookbook" section that takes scientific data on real and relevant projects and explains how they are made and how to pull together the lessons from the book to make them. -->


## Richard

###  **slidewinder** - a new way of making (scientific) presentations by sharing and reusing individual slides

tags:

- reuse
- sci-comm

#### Motivation

 -  Scientists (and many other people) spend a lot of time and energy making slide decks.
 -  Ideally when a scientist makes a slide deck, if someone else had already made a slide, or figure in a paper, that captures what they want, they could reuse or remix it.
 -  It's hard to reuse slides and other materials that others have made - it's hard to find them, and it's hard to move their content into your deck.
 - It's hard to share slide content you've created in a way that enables others to reuse it easily.

#### What is it?

A new way of making presentations, and the free, open source software to do it. It works like this:

A user makes slides. Each slide is stored in a single text file, with the content and some metadata, but no styling. They build up a collection of slides. Using `slidewinder`, they can rapidly assemble a slide deck from some or all of the slides in their collection, and any new slides they want to add in the process. They can use collections of slides made by other people in the same way, and mix their own slides with those made by others. They can apply any styling they want to the deck, using existing stylesheets or new ones of their own. Slide collections can be auto-generated from sources such as the scientific literature - imagine one slide for every figure and table in each paper in the scientific literature!

Slidewinder has the following features:

- it focuses on the *slide*, rather than the whole *deck* as the unit. Slides have the following properties:
  - the style and content of slides are separated out from one another
  - content is written in simple plaintext (e.g. `markdown`)
  - each slide has metadata associated with it (e.g. title, tags, description, author, license)
- users can have a large collection of diverse slides spanning any number of topics
- users can have a collection of styles (in `css`)
- a slide deck can can be rapidly assembled from any subset of the slides in a collection, using any style
- the deck is generated using one of several existing open source presentation frameworks. This means:
  - the user can present the deck in their browser (which *every* computer has)
  - it can be viewed either locally or over the internet (no need to move files around on USB sticks)
 - the user can choose the framework to suit their purpose (loads of cool features, no restrictions)
- collections of slides can be shared online anywhere
- decks can also be shared, and can be used like individual slides to compose a new deck
- there will be a command-line interface, and a browser-based GUI (`slidewinder`)
- the user-facing software can connect to any number of online repositories of slides or styles and make use of the collections there

Additionally, we will build a website that includes the GUI and a large collection of open licensed slides. We will populate the slide collection with figures from open-licensed scientific papers. The website will show the power of the 'slide' focused way of thinking about presentations.

###  **BioJulia** as an exemplar for accessible, welcoming open source communities

tags:

- inclusiveness
- barriers to entry
- community

#### Motivation

Technology and especially software communities on the internet have a serious diversity problem. They are often unwelcoming to people who don't conform to the narrow social makeup of the group. And similarly, they can be very difficult to get involved in even if the person does feel welcomed - this is true for both users and contributors to such projects.

### What is it?

BioJulia is an open source project to build high-quality biological software tools for the Julia programming language. The project has a community of active developers, and is interested in holding itself to the highest standards - technically and in its social development.

This sprint will focus on making the BioJulia community as welcoming and accessible as possible to anyone who might want to get involved in any capacity. The sprint might cover the website and other online presences of the project, community rules and guidelines, teaching and learning materials and platforms, the design of the system from an accessibility perspective, and the overall user experience of the project.

All actions taken in BioJulia would be documented and used to produce a guide to opening up online software communities.

### **easyminer** - making content mining of the scientific literature as easy as it can possibly be

tags:

- reuse
- barriers to entry
- UX

#### Motivation

Content mining (a.k.a text and data mining, but also applying to images and other content) allows researchers and others to reuse the scientific literature at massive scale. Laws in the UK, Japan and USA, and soon in the EU, give researchers the right to do content mining and not be inhibited by publishers. Content mining has the potential to open up a new dimension of science, in which the work of others can be built upon more rapidly and at a larger scale than every before.

Unfortunately, there are two major forces blocking the use of content mining:

- The technology to carry out content mining is well developed, but has very poor user experience and interface design. It is hard to install, even for highly technical users, it is hard to figure out, and hard to use.
- Although the law is clear, the information available to researchers about what they can do is not - it is clouded by confusingly-worded contracts and terms-and-conditions from publishers, and by the lack of a clear source of accurate information.


#### What is it?

**easyminer** is a project that would make content mining as easy as it can possibly be by addressing the two problems outlined above.

The project would have two outputs:

1. a website that made it very easy for people interested in content mining to find out about the law and which tools to use
2. a piece of cross-platform software that bundles up all the best tools for content mining in an easy to install package, and makes them accessible through a single clean, effective GUI.

User experience design principles would guide both aspects of the project.
