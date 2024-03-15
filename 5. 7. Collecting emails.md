---


---

<h1 id="learn-how-to-connect-an-email-list-to-your-landing-page">Learn how to connect an email list to your landing page</h1>
<p><em>In this lesson, you’ll learn:</em></p>
<ul>
<li>The basics of setting up a mailing list.</li>
<li>Why it matters.</li>
</ul>
<p><img src="https://s3.amazonaws.com/nugget.one/academy/email-list.jpg" alt=""></p>
<h4 id="why-set-up-an-email-list">Why Set Up an Email List?</h4>
<p>Remember the Sucessfull Business Stack?</p>
<p><img src="https://s3.amazonaws.com/nugget.one/academy/stack.png" alt=""></p>
<p>Well, our email list is  <em>the foundation</em>  of our stack.</p>
<p><img src="https://s3.amazonaws.com/nugget.one/academy/stack-bottom.png" alt=""></p>
<p>Our email list plays a  <em>pivotal</em>  role in our validation loop.</p>
<h4 id="validation-loop">Validation Loop</h4>
<p><strong>Step #1:</strong>  We find ways to get potential customers to our landing page.</p>
<p><strong>Step #2:</strong>  When they get there, hopefully they signup to our mailing list.</p>
<p><strong>Step #3:</strong>  When they do, we get their insights by:</p>
<ul>
<li>Inviting them to a customer interview.</li>
<li>Sending them a survey.</li>
<li>Chatting with them on Slack.</li>
<li>Etc.</li>
</ul>
<p><strong>Step #4:</strong>  After connecting, we use our learnings to:</p>
<ul>
<li>Refine our idea.</li>
<li>Improve marketing efforts to get more people to our landing page.</li>
<li>Gradually move our page from  <em>Vapor</em>  to  <em>Liquid</em>  to  <em>Solid</em>  with improved messaging.</li>
</ul>
<p><strong>Step #5:</strong>  Back to Step 1.</p>
<p><em>Note</em></p>
<p>When we know that multiple customers want to give us money, we move out of the validation loop and begin our pre-sales and launch phase.</p>
<h4 id="a-note-about-drip-campaigns--ebook-giveaways">A Note About Drip Campaigns &amp; eBook Giveaways</h4>
<p>It would be very tempting to try to convince users to signup to our list by offering a drip campaigns or a free eBook. The issue with doing that on our  <em>Vapor</em>  page is it will muddy our experiment.</p>
<p>At this point,  <strong><em>we want to be sure people are signing up to a wait list for our solution/benefit messaging</em></strong>  rather then giving us an email address in return for a freebie. In other words, we want to try to minimize the FOMO people from our seed group and maximize the Super Seeds.</p>
<p>Here are some other reasons to stick with the  <em>Vapor</em>  landing page formula:</p>
<ol>
<li>We want variables kept to a minimum, if we add other stuff it adds new reasons why things might not be working which is harder to uncover.</li>
<li>Anything we add without talking to customers is based on our best guess, and we may guess wrong and wast time.</li>
</ol>
<p>Don’t worry though! We will work extensively with drip campaigns and other marketing ideas in later Stages 9-11.</p>
<h4 id="how-to-connect-an-email-list-to-our-landing-page">How to Connect an Email List to our Landing Page</h4>
<p>The most common way to connect an email list to a landing page is to add an html form.</p>
<p>For example, in the  <a href="http://nugget.test/downloads/landing-pages/vapor.html">sample landing page</a>  I created, it looks like this:</p>
<p><em>&lt;<em>form action=“<a href="https://www.getdrip.com/forms/562905327/submissions">https://www.getdrip.com/forms/562905327/submissions</a>” method=“post”</em>&gt;</em></p>
<p><em>&lt;<em>input type=“text” name=“fields[email]” placeholder=“Your email…”</em>&gt;</em></p>
<p><em>&lt;<em>input type=“submit” value=“Get Notified”</em>&gt;</em></p>
<p><em>&lt;</em>/form_&gt;_</p>
<p>In the above case, it is plugging in to Drip. Note how there is a unique number in the form action address. That is the specific number that ties in to the email list account.</p>
<p><em>Note</em></p>
<p>In the version I created above, I have simplified the default code they supplied. If you want to copy my exact Drip code above, you can. The only thing you need to change is the unique account number.</p>
<p>As with website builders and analytics providers, there are plenty of email list providers to choose from.</p>
<p>Here is a list of ones I have used and like, along with instructions on how they work.</p>
<p>Email List Providers</p>
<ul>
<li><a href="https://help.drip.com/hc/en-us/articles/115003730671-Create-a-Form">Drip - Create a Form</a></li>
<li><a href="https://kb.mailchimp.com/lists/signup-forms/add-a-signup-form-to-your-website">Mailchimp - Add a Signup Form to Your Website</a></li>
<li><a href="https://help.madmimi.com/what-are-web-forms/">Mad Mimi - How To Create New Webforms</a></li>
</ul>
<p><em>Note</em></p>
<p>Ultimately I recommend Drip because it has great marketing automation at a sensible price point. We will be looking specifically at Drip automation techniques in future stages.</p>
<p><a href="https://www.getdrip.com/signup/starter">Here’s a direct link to Drip’s free plan</a></p>

