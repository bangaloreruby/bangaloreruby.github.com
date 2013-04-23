---
layout : page
---

<section id="container">
  <div id="flash"></div>
  
  <section class='column'>
  <article>
    <header><h2>20 April 2013</h2></header>
    <p>
      As usual April BRUG meet started with intros by people.
      <br /> 
      There were two topics scheduled for this meet.
    </p>
    <p>
      <strong>Yuva - Using Backbone in not so single page application</strong><br />
      Yuva started with an introduction to the basic architecture of a Backbone application (views, models, collections etc), with example code in slides. He explained why he wanted to use Backbone on his project (since the back-end is depend on some third party application response, even for pagination and filtering the results, his application wanted to communicate with the third party application and which is causing delay.) We had a lot of questions in between the slides and Yuva, Hemant and Dheeraj helped to clear almost all of them.
      <br />
      <br />
      Hemant given an intro to Faye(publish-subscribe messaging between web clients) which is also a part of this topic.
    </p>
    <p>
      <strong>Ashish - Codelearn</strong><br />
      Ashish wanted to make the discussion more interactive, so he didn't use slides at all. He started with explaining the architecture of Codelearn and the issues that he is facing now. His major concern is about the latency of the terminal window in Codelearn.
      <br />
      Lots of suggestions came up during the discussion, some of them are
      <br />
      * Event machine<br />
      * Removing the second Rails application in his current architecture<br />
      * Ruby VNC
      <br /><br />
    </p>
<!--     <p>
      That is it from March BRUG meetup. Slides for the presentations are:<br/>
      <a href="https://speakerdeck.com/swanandp/build-your-first-mapreduce-with-hadoop-and-ruby">build-your-first-mapreduce-with-hadoop-and-ruby</a><br/>
      <a href="https://speakerdeck.com/gnufied/introduction-to-dtrace">introduction-to-dtrace</a><br/>
    </p> -->
  </article>
  </section>
  <!-- end of April notes -->
  <section class='column'>
  <article>
    <header><h2>16th March 2013</h2></header>
    <p>
      The meetup started with intros by people and this time we had lot of new (at least more than couple) faces. There were 4 people who had come from Mysore(which includes the speaker Swanand), which also made  the meetup special.
      <br />
      There were 2 talks for the current meetup and the details of the same follows. 
    </p>
    <p>
      <strong>Swanand - Talk on Build your first MapReduce with Hadoop and Ruby</strong><br />
      The presentation was about the following:
      <br />
      * What's MapReduce and Hadoop<br />
      * What's Map and Reduce<br />
      * And a sample app to showcase the above
      <br /><br />
      The talk went into detail about what the map and reducer are, how MapReduce uses the key->value pair at every stage i.e. both in Map and Reduce jobs and also how it uses natural sorting for efficiency.
      <br/> 
      There was a demo at the end of the talk. The demo was about reading couple of books in txt format and find out the most used alphabet is e. During the demo Swanand showed us how to use Ruby to create Mappers and Reducers and use the configuration given by Hadoop.
      <br/>
      The presentation ended with showing References (which includes videos, articles and blog posts) which would help you to get started with Hadoop and also further documentation. 
    </p>
    <p>
      <strong>Hemant - Demo/presentation on dtrace in Ruby 2</strong><br />
      Started with explaining the architecture of dtrace sampling profiler (image below)  where dtrace probes and profiler run outside the program causing no overhead to your program.
      <br/>
      Then he explained more about anatomy of probes with the help of simple examples. There were many live examples shown on how to use dtrace commands (available in slides). Later he introduced us to D script language, which looks more or less similar to C syntax. You can refer to his slides which are self explanatory on the examples and functions used in D scripts. In after the talk discussions, there were suggestions that you should start using dtrace from beginning, if you are an author of a gem or a framework 
    </p>
    <p>
      That is it from March BRUG meetup. Slides for the presentations are:<br/>
      <a href="https://speakerdeck.com/swanandp/build-your-first-mapreduce-with-hadoop-and-ruby">build-your-first-mapreduce-with-hadoop-and-ruby</a><br/>
      <a href="https://speakerdeck.com/gnufied/introduction-to-dtrace">introduction-to-dtrace</a><br/>
    </p>
  </article>
  </section>
  <section class='column'>
    <article>
    <header><h2>19 Jan 2013</h2></header>
    <p>
      The meetup had two talks for the day: <em><strong>Ruby 2.0 features</strong> by Hemant (@gnufied)</em> and <em><strong>Building Allotrop</strong> by Rohit Mishra (@movingahead)</em> 
    </p>
    
    <p>
      The first talk was by Hemant who explained about the new features planned for Ruby 2.0. He explained about the 'refinements' feature being planned for Ruby 2.x, and the rationale behind it. He explained that refinements are a new way to handle the problems with monkeypatching in a sane manner. He then explained the syntax for refine/using, explained about the current state of flux in the documentation. There were questions about whether this will make it into Ruby 2.0 given the state of flux this feature is in. 
    </p>
    
    <p>
       Hemant then went on to explain about the new keyword arguments planned for this release, which adds more flexibility in passing arguments, a la Rails. The next point was about Module#prepend, a way working around the fact that 'include' appends methods, which can lead to some method overriding issues. He also went on to explain about Trace Point, a new way to profile ruby methods, and also about support for DTrace hooks which lets us do sophisticated debugging on ruby programs. You can find his <a href="https://speakerdeck.com/gnufied/ruby-2-dot-0-upcoming-changes">presentation here</a>. 
    </p>
    
    <p>Then it was over to Rohit, who gave a quick intro of his startup  Allotrop, which is basically a recommendation engine trying to connect our 'likes' to structured data. He explained his journey through several frameworks and languages before finally settling on Rails and why. He then talked about his struggle through making the right set of architectural choices, and how sometimes overthinking it really bites us. In Rohit's opinion, the right way to start with Rails is to find a mentor who has already been doing Rails for a while, and not being afraid to break stuff and learn from the results. During Q and A session it led to a good discussion where Nikhil explained how to apply YAGNI rule while choosing a gem. You can find his <a href="http://www.slideshare.net/movingahead/allotrop-brug">presentation here</a>.
    </p>

    
    <p>After the talks, there was longish discussion about Rails 4, concerns, strong parameters and how to make specs run faster, Zeus (the test runner), Backbone.js, Angular.js, etc. Here are some <a href="https://www.dropbox.com/sh/8rpeov7z5lz3a02/bd2-SGXWis/brug/jan2013">pics of the event</a>.</p>
    </article>
  </section>

  <section class='column'>
    <article>
      <header><h2>17 Nov 2012</h2></header>
      <p>
      The meetup had two talks for the day - <em>Lessons Learnt while building Survey Web</em> 
      by Nivedita, Smit, Srihari and Timothy of C42 Engineering and 
      <em>Git workflows</em> by Vamsee Kanakala of BangTheTable Software. 
      </p>

      <p>
      The meetup started with Srihari of C42 explaining the rationale for the survey-web project, and Nivedita took over explaining the use of STI in the project. After that, Srihari took over explaining the use and reasons behind picking Backbone.js for the front-end. Next was about APIs by Timothy and the advice was not to use scaffolding when doing them. Then Smit took over to discuss setting up an Omniauth provider with Doorkeeper. Then Srihari took over again for discussing about how they chose Titanium for the mobile version of Survey Web. Overall it was a very enlightening talk. You can find the <a href="http://brug-nov-slides.herokuapp.com/">full presentation here</a>.
      </p>

      <p>
      Next it was the Git Workflows talk by Vamsee. He explained the problem faced by using mostly merge for merging changes between private branches into the main development branch, with history quickly getting hard to track as to where the changes came from. He explained how BTT was moving to "rebase on private branch, merge on main branch" strategy to clean up their history and and be able to track branches properly. He alos explained how to use rebase and interactive rebase to keep history clean and understandable. There was also some discussion about how people usually do code pushes to production without having to move not-yet-completed features. Vamsee said he was considering a mix of cherry picking, tagging and finally feature toggles to achieve this. This part will be covered in another talk sometime in the future.
     </p>

     <p>
      After the talks, people mixed and had discussions about various topics. You can find some pictures of the event <a href="http://bit.ly/SFjbJi">here</a> and <a href="http://on.fb.me/ZTie69">here</a>.
     </p>
    </article>  
  </section>

</section>
