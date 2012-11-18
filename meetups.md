---
layout : page
---

<section id="container">
  <div id="flash"></div>

  <section class='column'>
    <article>
      <header><h2>17 Nov 2012</h2></header>
      <p>
      <strong>Meetup Notes</strong><br />
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
