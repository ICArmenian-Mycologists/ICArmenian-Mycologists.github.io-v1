---
title: International Congress of Armenian Mycologists
---

# <i class="fas fa-dna"></i>International Congress of Armenian Mycologists

{%
  include figure.html
  image="icons/ICAM-icon.png"
  caption="Welcome to ICAM!"
  width="100%"
  link="team"
%}


[**International Congress of Armenian Mycologists**](https://ICArmenian-Mycologists.github.io/) is a collaborative effort between Armenian mycologists: Tania Kurbessoian M.S., Claudia Bashian-Victoroff M.S., Patty Kaishian Ph.D., and Arik Joukhajian. 

## International Armenian Connections

{% capture text %}
[Research](research) Our focuses range from saprotrophic fungal diversity, the use of ectomycorrhizal fungi for forest remediation, and Khachkar lichen diversity interests. Please reach out to us if you are interested in collaborating. <br>
{% endcapture %}

{%
  include feature.html
  image="images/laboratory.jpg"
  link="research"
  heading="Connecting all Armenian Mycologists!"
  text=text
%}

{% capture text %}
We are also interested in teaching bioinformatics tools and pipelines to assemble, annotate and assess fungal genomes. <br>


<center><a href="(https://ICArmenian-Mycologists.github.io/resources/">See our resources &nbsp;→</a></center>
{% endcapture %}
{%
  include feature.html
  image="images/Mycology.JPG"
  link="resources"
  heading="ICAM resources"
  text=text
%}

{% capture text %}
The International Congress of Armenian Mycologists welcomes people from diverse backgrounds regardless of race, ethinicity, religion, gender identity, gender expression, sexual orientation, political affiliation, national origin, or disability. Our main goal is to uplift the indigenous Armenian peoples in the scientific community.  <br>


<center><a href="(https://ICArmenian-Mycologists.github.io/team/">See our team members &nbsp;→</a></center>
{% endcapture %}
{%
  include feature.html
  image="images/ICAM_group_photo.png"
  link="team"
  heading="Our team members"
  text=text
%}

<!-- section break --> 

## Our Mission

International Congress of Armenian Mycologists Mission Statement


The International Congress of Armenian Mycologists (ICAM) is a network of research scientists of Armenian ethnicity. Our diverse research backgrounds on various aspects of fungal biology are allied in the mission of biological, ecological, and social welfare of all Armenian life forms. As an organization we strive to conduct critical scientific research on the understudied fungal kingdom in the both ancient yet contemporary civilization of Armenia.   

Armenia is a predominantly indigenous nation in West Asia whose vibrancy and beauty has withstood the terrors of colonization and genocide for hundreds of years. As Armenians are locked in a struggle of liberation and self-determination against such forces, we believe that human liberation is intimately linked to the liberation of all life, not least of which is fungal.  Drawing from Armenia’s strong tradition of land stewardship and intimacy with nonhuman life forms, the goal of ICAM is to leverage our passions and training as scientists to simultaneously advance mycological science and Armenian sovereignty. 

We seek to build science capacity in Armenia by: collaborating with the nation’s already successful scientists through shared grants, co-authorship, and resource allocation; by providing financed scientific mentorship to Armenian youth; and by gathering biological data that can be used in the protection of land and life. Because fungi are understudied worldwide, and Armenia has been home to a low proportion of that research, we aim to describe new species and accrue data for answering critical ecological and evolutionary questions. Seating such research in Armenia will serve to bolster Armenia’s overall impact and contribution to science. 

Despite the common assertion to the contrary, science is informed by sociopolitical forces. ICAM recognizes and affirms the positive relationship between indigenous sovereignty and biological diversity in Armenia and beyond, and stands in solidarity with all indigenous social justice  efforts around the world. 


<!-- ******JOIN****** -->
 <section id="join" class="join section">
   <div class="container text-center">
     <h2 class="title">Join Us</h2>
     <div class="row">
       <div class="col-sm-5 col-sm-offset-1 text-right text-right-sm">
         <h1 class="join-us-intro">We Need Your Voice. Join Us!</h1>
       </div>
       <div class="col-sm-5 text-left text-left-sm">
         <p>Sign up to receive updates, progress reports and ways to get involved. We're excited to have you join our amazing community!</p>
         {% if site.tinyletter_username %}
         <p><em>No spam. Just the occasional update.</em></p>
         <div class="row">
           <div class="col-sm-12">
             <form class="form-inline" role="form" action="https://tinyletter.com/{{ site.tinyletter_username }}" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/{{ site.tinyletter_username }}', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
               <div class="input-group input-group-lg col-sm-12">
                 <label class="sr-only" for="tlemail">Email address</label>
                 <input type="email" class="form-control" name="email" id="tlemail" placeholder="email address" />
                 <div class="input-group-btn">
                   <button type="submit" class="button btn btn-cta-secondary">Join Us!</button>
                 </div><!-- /btn-group -->
               </div><!-- /input-group -->
             </form>
           </div>
         </div>
         {% elsif site.mailchimp_embed_code %}
         <p><em>No spam. Just the occasional update.</em></p>
         <div id="mc_embed_signup">
           <form action="{{ site.mailchimp_embed_code }}" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate bs-component" target="_blank" novalidate>
             <div id="mc_embed_signup_scroll">
               <div class="form-group">
                 <label for="mce-EMAIL" class="sr-only">Email Address</label>
                 <input placeholder="email address" type="email" value="" name="EMAIL" class="required email form-control" id="mce-EMAIL">
               </div>
               <div class="form-group">
                 <div class="row">
                   <div class="col-xs-6">
                     <label for="mce-FNAME" class="sr-only">Given / First Name </label>
                     <input placeholder="given / first name" type="text" value="" name="FNAME" class="form-control" id="mce-FNAME">
                   </div>
                   <div class="col-xs-6">
                     <label for="mce-LNAME" class="sr-only">Family / Last Name </label>
                     <input placeholder="family / last name" type="text" value="" name="LNAME" class="form-control" id="mce-LNAME">
                   </div>
                 </div>
               </div>
               <div id="mce-responses" class="clear">
                 <div class="response" id="mce-error-response" style="display:none"></div>
                 <div class="response" id="mce-success-response" style="display:none"></div>
               </div>
               <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
               <div style="position: absolute; left: -5000px;"><input type="text" name="{{ site.mailchimp_spam_guard }}" tabindex="-1" value=""></div>
               <div class="clear">

                 <input type="submit" value="Join Us!" name="subscribe" id="mc-embedded-subscribe" class="button btn-success btn-block btn" />
               </div>
             </div>
           </form>
         </div>
         <script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
         <!--End mc_embed_signup-->
         {% else %}
         <p><em>Sorry, email signup is not available at this time <i class="fa fa-frown-o"></i></em></p>
         {% endif %}

         <!--form style="padding:3px;text-align:center;" action="https://tinyletter.com/{{ site.tinyletter_username }}" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/{{ site.tinyletter_username }}', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true"><p><label for="tlemail">Subscribe to Updates</label></p><p><input type="text" style="width:140px" name="email" id="tlemail" data-behavior="placeholder" placeholder="Email Address" /></p><input type="hidden" value="1" name="embed"/><input type="submit" value="Subscribe" /><p></p></form-->


       </div>
     </div>
   </div><!--//container-->
 </section><!--//join-->

 <!-- ******DONATE****** -->
 <section id="donate" class="donate section text-center">
   <div class="container">
     <div class="donate-inner">
       <h2 class="title text-center">Donate</h2>
       <div class="info">
         <p><strong>Become a donor today.</strong><br>As a small grassroots organization, know that every dollar will have an immense impact on our ability to continue working towards our mission.</p>
         {% if site.donorbox_campaign_name %}
           <div class="donorbox text-center">
             <iframe src="https://donorbox.org/embed/{{ site.donorbox_campaign_name }}" height="600px" width="100%" style="max-width:500px; min-width:310px" seamless="seamless" name="donorbox" frameborder="0" scrolling="no"></iframe>
           </div>
           {% if site.is_501c3 == true %}
             <p>Contributions are tax deductible to the extent permitted by law.<br>{{ site.org_name }} is a 501(c)(3) organization.</p>
           {% elsif site.fiscal_sponsor_name %}
             <p>{{ site.org_name }} is fiscally sponsored by {{ site.fiscal_sponsor_name }}, a 501 (c)(3) tax exempt non-profit organization.</p>
           {% endif %}
         {% else %}
         <div class="donorbox text-center">
         </div>
         <hr>
         <p class="text-warning">Sorry, online donations are not available at this time <i class="fa fa-frown-o"></i></p>
         <hr>
         {% endif %}
       </div><!--//info-->
       <div class="cta-container">
         <div class="speech-bubble">
           <p class="intro">Your support means the world to us :)</p>
           <div class="icon-holder  text-center"><i class="fa fa-smile-o"></i></div>
         </div><!--//speech-bubble-->
         <div class="btn-container  text-center">
           <!--//You need to generate your own PayPal button if you choose to use Paypal - https://www.paypal.com/us/cgi-bin/?cmd=_donate-intro-outside -->
           <!--PayPal generated code starts-->
               <!--form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
               <input type="hidden" name="cmd" value="_s-xclick">
               <input type="hidden" name="hosted_button_id" value="{{ site.paypal_button_id }}">
               <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
               <img alt="" border="0" src="https://www.paypalobjects.com/en_GB/i/scr/pixel.gif" width="1" height="1">
             </form-->
             <!--//PayPal generated code ends-->

         </div><!--//btn-container-->
       </div><!--//cta-container-->
     </div><!--//donate-inner-->
   </div><!--//container-->
 </section><!--//how-->
