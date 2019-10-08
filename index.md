---
layout: workshop      # DON'T CHANGE THIS.
carpentry: "swc"    # what kind of Carpentry (must be either "lc" or "dc" or "swc").  
                      # Be sure to update the Carpentry type in _config.yml as well.  
venue: "Centro de Física Teórica y Matemáticas" # brief name of host site without address (e.g., "Euphoric State University")
address: "Nicolas Cabrera 13, Madrid, Spain"      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria")
country: "es"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes)
language: "es"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
latlng: "40.549532,-3.687608"       # decimal latitude and longitude of workshop venue (e.g., "41.7901128,-87.6007318" - use https://www.latlong.net/)
humandate: "Nov 28, 4 Dec 9:00 am - 6:00 pm, 2019"    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: "29 Nov 9:00 am  -  1:00 pm 2019"    # human-readable times for the workshop (e.g., "9:00 am - 4:30 pm")
startdate: 2019-11-28      # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate: 2019-11-29        # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
instructor:  ["Iñigo Aldazabal", "Emilio Ambite", "Alfonso Nuñez","Bryan Zaldivar"] # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper: ["Andrés Díaz-Gil", "Eduardo de Cordoba", "Marcos Ramírez", "Nadir Samos"]     # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: ["marcos.ramirez@csic.es"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
collaborative_notes:             # optional: URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document
eventbrite:           # optional: alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
---

{% comment %} See instructions in the comments below for how to edit specific sections of this workshop template. {% endcomment %}

{% comment %}
HEADER

Edit the values in the block above to be appropriate for your workshop.
If the value is not 'true', 'false', 'null', or a number, please use
double quotation marks around the value, unless specified otherwise.
And run 'make workshop-check' *before* committing to make sure that changes are good.
{% endcomment %}



{% comment %}
For a workshop please delete the following block
{% endcomment %}
<!--<div class="alert alert-danger">
This is the workshop template. Delete these lines and use it to customize your
own website. If you are running a self-organized workshop or have not put in a
workshop request yet, please also fill in 
<a href="{{site.amy_site}}/submit">this workshop request form</a> to let us know
about your workshop and our administrator may contact you if we need any extra
information.
</div> -->

{% if page.carpentry != site.carpentry %}
<div class="alert alert-warning">
You specified <code>carpentry: {{page.carpentry}}</code> in <code>index.md</code> and
<code>carpentry: {{site.carpentry}}</code> in <code>_config.yml</code>. Make sure you edit both files. After editing <code>_config.yml</code>, you need to run <code>make serve</code> again to 
see the changes take effect locally.
</div>
{% endif %}

{% comment %}
EVENTBRITE

This block includes the Eventbrite registration widget if
'eventbrite' has been set in the header.  You can delete it if you
are not using Eventbrite, or leave it in, since it will not be
displayed if the 'eventbrite' field in the header is not set.
{% endcomment %}
{% if page.eventbrite %}
<iframe
  src="https://www.eventbrite.com/tickets-external?eid={{page.eventbrite}}&ref=etckt"
  frameborder="0"
  width="100%"
  height="280px"
  scrolling="auto">
</iframe>
{% endif %}





<div id="coll">
 With the collaboration of: 
 <div id="CFMlogo" class="">
  <img src="cfm-banner.png" />
  <a href="http://cfm.ehu.es/">Centro de Física de Materiales EHU</a>
 </div>
<!--<div id="sipba" class="col-md-6">	
<img src="transparent_vertical_black.png" style="max-width:200px">
</div>	-->
</div>


<div id="general_resgistration">
<h2 id="registration">Registration</h2>	
<div id="content_registration">
<!-- Registration is open as June the 1st. 	Registration is  <strong>closed</strong> as of June the 25th. All available seats for the workshop have been filled.-->

 <p>Assistance is limited to 32 people and seats are assigned in a first-come fist-served basis.</p>	

 <div style="display: block;" class="classictemplate template">	
<style type="text/css">	
  #groupsio_embed_signup input {border:1px solid #999; -webkit-appearance:none;}	
  #groupsio_embed_signup label {display:block; font-size:16px; padding-bottom:10px; font-weight:bold;}	
  #groupsio_embed_signup .email {display:block; padding:8px 0; margin:0 4% 10px 0; text-indent:5px; width:58%; min-width:130px;}	
  #groupsio_embed_signup {	
    background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif;	
  }	
  #groupsio_embed_signup .button {	
      width:25%; margin:0 0 10px 0; min-width:90px;	
      background-image: linear-gradient(to bottom,#337ab7 0,#265a88 100%);	
      background-repeat: repeat-x;	
      border-color: #245580;	
      text-shadow: 0 -1px 0 rgba(0,0,0,.2);	
      box-shadow: inset 0 1px 0 rgba(255,255,255,.15),0 1px 1px rgba(0,0,0,.075);	
      padding: 5px 10px;	
      font-size: 12px;	
      line-height: 1.5;	
      border-radius: 3px;	
      color: #fff;	
      background-color: #337ab7;	
      display: inline-block;	
      margin-bottom: 0;	
      font-weight: 400;	
      text-align: center;	
      white-space: nowrap;	
      vertical-align: middle;	
    }	
</style>	
<div id="groupsio_embed_signup">	
<!--	
<form action="https://groups.io/g/lund-SC-workshop/signup?u=2154170982873630030" method="post" id="groupsio-embedded-subscribe-form" name="groupsio-embedded-subscribe-form" target="_blank">	
-->	
<form target="_blank" action="https://workshops.ift.uam-csic.es/SCWcftmat2019/registro" method="GET">	
    <div id="groupsio_embed_signup_scroll">	
     <div style="position: absolute; left: -5000px;" aria-hidden="true"><input name="b_2154170982873630030" tabindex="-1" value="" type="text"></div>	
    <div id="templatearchives"></div>	
    <input value="Register here" name="subscribe" id="groupsio-embedded-subscribe" class="button" type="submit"/>	
  </div>	
</form>	
</div>	
</div>
</div>	
</div>
<!-- Fin registration -->



<div id="contents_wrap">
<h2 id="general">Contents</h2>
<div id="contents">
 <ul>
  <li><a href="#general">General Information</a></li>
  <li><a href="#details">Workshop Details</a></li>
  <!--<li><a href="#sponsors">Sponsors</a></li>-->
  <li><a href="#schedule">Schedule</a></li>
  <li><a href="#syllabus">Syllabus</a></li>
  <li><a href="#setup">Software Setup Instructions</a></li>
</ul>
</div>
</div>

<div id="general_wrap">
<h2 id="general">General Information</h2>

<!--
  INTRODUCTION
  Edit the general explanatory paragraph below if you want to change
  the pitch.
-->

{% if page.carpentry == "swc" %}
  {% include sc/intro.html %}
{% elsif page.carpentry == "dc" %}
  {% include dc/intro.html %}
{% elsif page.carpentry == "lc" %}
  {% include lc/intro.html %}
{% endif %}

<!--
  WORKSHOP DETAILS
  A separated section for detailed workshop information
-->

</div>


<div id="details_wrap">
<h2 id="wdetails">Workshop Details</h2>

<!--
  AUDIENCE
  Explain who your audience is.  (In particular, tell readers if the
  workshop is only open to people from a particular institution.
-->

{% if page.carpentry == "swc" %}
  {% include sc/who.html %}
{% elsif page.carpentry == "dc" %}
  {% include dc/who.html %}
{% elsif page.carpentry == "lc" %}
  {% include lc/who.html %}
{% endif %}


<!--
  LOCATION
  This block displays the address and links to maps showing directions
  if the latitude and longitude of the workshop have been set.  You
  can use http://itouchmap.com/latlong.html to find the lat/long of an
  address.
-->

{% if page.latlng %}
<p id="where">
  <strong>Where:</strong>
  {{page.address}}.
  Get directions with
  <a href="//www.openstreetmap.org/?mlat={{page.latlng | replace:',','&mlon='}}&zoom=16">OpenStreetMap</a>
  or
  <a href="//maps.google.com/maps?q={{page.latlng}}">Google Maps</a>.
</p>
{% endif %}

<!--
  DATE
  This block displays the date and links to Google Calendar.
-->

{% if page.humandate %}
<p id="when">
  <strong>When:</strong>
  {{page.humandate}}.
  {% include workshop_calendar.html %}
</p>
{% endif %}

<!--
  SPECIAL REQUIREMENTS
  Modify the block below if there are any special requirements.
-->

<div class="alert alert-warning">
<p id="requirements">
  <strong>Requirements:</strong> Participants must bring a laptop with a
  Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges
  on. They should have a few specific software packages installed (listed
  <a href="#setup">below</a>). They are also required to abide by
  {% if page.carpentry == "swc" %}
  Software Carpentry's
  {% elsif page.carpentry == "dc" %}
  Data Carpentry's
  {% elsif page.carpentry == "lc" %}
  Library Carpentry's
  {% endif %}
  <a href="{{site.swc_site}}/conduct.html">Code of Conduct</a>.
</p>
</div>
<!--
  ACCESSIBILITY
  Modify the block below if there are any barriers to accessibility or
  special instructions.
-->

<p id="accessibility">
  <strong>Accessibility:</strong> We are committed to making this workshop
  accessible to everybody.
  The workshop organisers have checked that:
</p>
<ul>
  <li>The room is wheelchair / scooter accessible.</li>
  <li>Accessible restrooms are available.</li>
</ul>
<p>
  Materials will be provided in advance of the workshop and
  large-print handouts are available if needed by notifying the
  organizers in advance.  If we can help making learning easier for
  you (e.g. sign-language interpreters, lactation facilities) please
  get in touch (using contact details below) and we will
  attempt to provide them.
</p>

<!--
  CONTACT EMAIL ADDRESS  .
You may need to move the div's with class="col-md-6" around inside -->

<p id="contact">
  <strong>Contact</strong>:
  Please email
  {% if page.contact %}
    {% for contact in page.contact %}
      {% if forloop.last and page.contact.size > 1 %}
        or
      {% else %}
        {% unless forloop.first %}
        ,
        {% endunless %}
      {% endif %}
      <a href='mailto:{{contact}}'>{{contact}}</a>
    {% endfor %}
  {% else %}
    to-be-announced
  {% endif %}
  for more information.
</p>
</div><!--div wdetails -->

<!--
  SCHEDULE
  Show the workshop's schedule.  Edit the items and times in the table
  to match your plans.  You may also want to change 'Day 1' and 'Day
  2' to be actual dates or days of the week.
-->

<div id="schedule_wrap">
<h2 id="schedule">Schedule</h2>

<!-- DO NOT EDIT SURVEY LINKS -->
<p><em>Surveys</em></p>
<p>Please be sure to complete these surveys before and after the workshop.</p>
<p><a href="{{ site.pre_survey }}{{ site.github.project_title }}">Pre-workshop Survey</a></p>
<p><a href="{{ site.post_survey }}{{ site.github.project_title }}">Post-workshop Survey</a></p>

{% if page.carpentry == "swc" %}
  {% include sc/schedule.html %}
{% elsif page.carpentry == "dc" %}
  {% include dc/schedule.html %}
{% elsif page.carpentry == "lc" %}
  {% include lc/schedule.html %}
{% endif %}

<!--
  Collaborative Notes
  If you want to use an Etherpad, go to
      http://pad.software-carpentry.org/YYYY-MM-DD-site
  where 'YYYY-MM-DD-site' is the identifier for your workshop,
  e.g., '2015-06-10-esu'.
-->
{% if page.collaborative_notes %}
<p id="collaborative_notes">
  We will use this <a href="{{page.collaborative_notes}}">collaborative document</a> for chatting, taking notes, and sharing URLs and bits of code.
</p>
{% endif %}

</div> <!-- div schedule_wrap -->

<div id="syllabus_wrap">
<!--
  SYLLABUS
  Show what topics will be covered.
  1. If your workshop is R rather than Python, remove the comment
     around that section and put a comment around the Python section.
  2. Some workshops will delete SQL.
  3. Please make sure the list of topics is synchronized with what you
     intend to teach.
  4. You may need to move the div's with class="col-md-6" around inside
     the div's with class="row" to balance the multi-column layout.
  This is one of the places where people frequently make mistakes, so
  please preview your site before committing, and make sure to run
  'tools/check' as well.
-->
<h2 id="syllabus">Syllabus</h2>

{% if page.carpentry == "swc" %}
  {% include sc/syllabus.html %}
{% elsif page.carpentry == "dc" %}
  {% include dc/syllabus.html %}
{% elsif page.carpentry == "lc" %}
  {% include lc/syllabys.html %}
{% endif %}

<div><!-- div syllabus_wrap -->



<div id="setup_wrap">

<!--
  SETUP
  Delete irrelevant sections from the setup instructions.  Each
  section is inside a 'div' without any classes to make the beginning
  and end easier to find.
  This is the other place where people frequently make mistakes, so
  please preview your site before committing, and make sure to run
  'tools/check' as well.
-->

<h2 id="setup">Setup</h2>
<p>
  To participate in a
  {% if page.carpentry == "swc" %}
  Software Carpentry
  {% elsif page.carpentry == "dc" %}
  Data Carpentry
  {% elsif page.carpentry == "lc" %}
  Library Carpentry
  {% endif %}
  workshop,
  you will need access to the software described below.
  In addition, you will need an up-to-date web browser.
</p>
<p>
  We maintain a list of common issues that occur during installation as a reference for instructors
  that may be useful on the
  <a href = "{{site.swc_github}}/workshop-template/wiki/Configuration-Problems-and-Solutions">Configuration Problems and Solutions wiki page</a>.<b> Choose your OS below for detailed installation instructions</b>
</p>


<div id="shell"> <!-- Start of 'shell' section. -->
  <h3>The Bash Shell</h3>

  <p>
    Bash is a commonly-used shell that gives you the power to do simple
    tasks more quickly.
  </p>

  <div class="row">
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse"  href="#collapseOne" aria-expanded="false" aria-controls="collapseOne"><h4 id="shell-windows">Windows</h4></a>  
      <div id="collapseOne" class="collapse">  
      <a href="https://www.youtube.com/watch?v=339AEqk9c-8">Video Tutorial</a>
      <ol>
        <li>Download the Git for Windows <a href="https://git-for-windows.github.io/">installer</a>.</li>
        <li>Run the installer and follow the steps bellow:
          <ol>
            <!-- Git 2.8.2 Setup -->
            <!-- Information -->
            <li>Click on "Next" till you see:</li>
            <!-- Adjusting your PATH environment -->
            <li>
              <strong>
                "Use Git from the Windows Command Prompt", select it and click on "Next".
              </strong>
                If you forgot to do this programs that you need for the workshop will not work properly.
                If this happens rerun the installer and select the appropriate option.
            </li>
            <!-- Choosing the SSH executable -->
            <li>Keep clicking on "Next" till you see:</li>
            <!-- Configuring the line ending conversions -->
            <li>
              <strong>
                "Checkout Windows-style, commit Unix-style line endings", select it and click on "Next".
              </strong>
            </li>
            <!-- Configuring the terminal emulator to use with Git Bash -->
            <li>
              <strong>
                Keep "Use Windows' default console window" selected and click on "Next".
              </strong>
            </li>
            <!-- Configuring experimental performance tweaks -->
            <li>Click on "Install".</li>
            <!-- Installing -->
            <!-- Completing the Git Setup Wizard -->
            <li>Click on "Finish".</li>
          </ol>
        </li>
        <li>
          If your "HOME" environment variable is not set (or you don't know what this is):
          <ol>
            <li>Open command prompt (Open Start Menu then type <code>cmd</code> and press [Enter])</li>
            <li>
              Type the following line into the command prompt window exactly as shown:
              <p><code>setx HOME "%USERPROFILE%"</code></p>
            </li>
            <li>Press [Enter], you should see <code>SUCCESS: Specified value was saved.</code></li>
            <li>Quit command prompt by typing <code>exit</code> then pressing [Enter]</li>
          </ol>
        </li>
      </ol>
      <p>This will provide you with both Git and Bash in the Git Bash program.</p>
    </div><!-- End collapseOne -->	
  </div>
  <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse"  href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        <h4 id="shell-macos">MacOS X</h4></a>
     <div id="collapseTwo" class="collapse">
      <p>
        The default shell in all versions of Mac OS X is Bash, so no
        need to install anything.  You access Bash from the Terminal
        (found in
        <code>/Applications/Utilities</code>).
        See the Git installation <a href="https://www.youtube.com/watch?v=9LQhwETCdwY ">video tutorial</a>
        for an example on how to open the Terminal.
        You may want to keep
        Terminal in your dock for this workshop.
      </p>
     </div> <!-- End collapseTwo -->
   </div>
   <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree"><h4 id="shell-linux">Linux</h4></a>
     <div id="collapseThree" class="collapse">
      <p>
        The default shell is usually Bash, but if your
        machine is set up differently you can run it by opening a
        terminal and typing <code>bash</code>.  There is no need to
        install anything.
      </p>
     </div><!-- End div collapseThree-->
    </div>
  </div>
</div> <!-- End of 'shell' section. -->

<div id="git"> <!-- Start of 'Git' section. GitHub browser compatability
           is given at https://help.github.com/articles/supported-browsers/-->
  <h3>Git</h3>
  <p>
    Git is a version control system that lets you track who made changes
    to what when and has options for easily updating a shared or public
    version of your code on a remote repository. You will need a
    <a href="https://help.github.com/articles/supported-browsers/">supported</a>
    web browser (current versions of Chrome, Firefox or Safari,
    or Internet Explorer version 9 or above).
  </p>
  <p>
    You will need an account at <a href="https://gitlab.ift.uam-csic.es/">IFT's GitLab</a>
    for parts of the Git lesson. We encourage
    you to create a GitiLab account if you don't have one already.
  </p>

  <div class="row">
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapseg1" aria-expanded="false" aria-controls="collapseg1"><h4 id="git-windows">Windows</h4></a>
      <div id="collapseg1" class="collapse">
      <p>
        Git should be installed on your computer as part of your Bash
        install (described above).
      </p>
      </div> 
    </div>
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapseg2" aria-expanded="false" aria-controls="collapseg2">         <h4 id="git-macosx">Mac OS X</h4>
      </a>
      <div id="collapseg2" class="collapse">
       <a href="https://www.youtube.com/watch?v=9LQhwETCdwY ">Video Tutorial</a>
       <p>
        <strong>For OS X 10.9 and higher</strong>, install Git for Mac
        by downloading and running the most recent "mavericks" installer from
        <a href="http://sourceforge.net/projects/git-osx-installer/files/">this list</a>.
        After installing Git, there will not be anything in your <code>/Applications</code> folder,
        as Git is a command line program.
        <strong>For older versions of OS X (10.5-10.8)</strong> use the
        most recent available installer labelled "snow-leopard"
        <a href="http://sourceforge.net/projects/git-osx-installer/files/">available here</a>.
      </p>
      </div>
    </div>
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapseg3" aria-expanded="false" aria-controls="collapseg3">
        <h4 id="git-linux">Linux</h4>
        </a>
      <div id="collapseg3" class="collapse">
      <p>
        If Git is not already available on your machine you can try to
        install it via your distro's package manager. For Debian/Ubuntu run
        <code>sudo apt-get install git</code> and for Fedora run
        <code>sudo yum install git</code>.
      </p>
      </div>
    </div>
  </div>
</div> <!-- End of 'Git' section. -->

<div id="editor"> <!-- Start of 'editor' section. -->
  <h3>Text Editor</h3>
  <p>
    When you're writing code, it's nice to have a text editor that is
    optimized for writing code, with features like automatic
    color-coding of key words.  The default text editor on Mac OS X and
    Linux is usually set to Vim, which is not famous for being
    intuitive.  if you accidentally find yourself stuck in it, try
    typing the escape key, followed by <code>:q!</code> (colon, lower-case 'q',
    exclamation mark), then hitting Return to return to the shell.
  </p>

  <div class="row">
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapsee1" aria-expanded="false" aria-controls="collapsee1"><h4 id="editor-windows">Windows</h4></a>
      <div id="collapsee1" class="collapse">
     <p>
        nano is a basic editor and the default that instructors use in the workshop.
        It should be proposed as an option in the Git Bash installation. Please follow the
	installation procedure of Git Bash and select nano when asked.
      </p>
      <p>
        Others editors that you can use are
        <a href="http://notepad-plus-plus.org/">Notepad++</a> or
        <a href="http://www.sublimetext.com/">Sublime Text</a>.
        <strong>Be aware that you must
          add its installation directory to your system path.</strong>
        Please ask your instructor to help you do this.
      </p>
      </div>
    </div>
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapsee2" aria-expanded="false" aria-controls="collapsee2"><h4 id="editor-macosx">Mac OS X</h4></a>
      <div id="collapsee2" class="collapse">
      <p>
        nano is a basic editor and the default that instructors use in the workshop.
        See the Git installation <a href="https://www.youtube.com/watch?v=9LQhwETCdwY ">video tutorial</a>
        for an example on how to open nano.
        It should be pre-installed.
      </p>
      <p>
        Others editors that you can use are
        <a href="http://www.barebones.com/products/textwrangler/">Text Wrangler</a> or
        <a href="http://www.sublimetext.com/">Sublime Text</a>.
      </p>
      </div> 
    </div>
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapsee3" aria-expanded="false" aria-controls="collapsee3"><h4 id="editor-linux">Linux</h4></a>
      <div id="collapsee3" class="collapse">
      <p>
        nano is a basic editor and the default that instructors use in the workshop.
        It should be pre-installed.
      </p>
      <p>
        Others editors that you can use are
        <a href="https://wiki.gnome.org/Apps/Gedit">Gedit</a>,
        <a href="http://kate-editor.org/">Kate</a> or
        <a href="http://www.sublimetext.com/">Sublime Text</a>.
      </p>
      </div>
    </div>
  </div>
</div> <!-- End of 'editor' section. -->

<div id="python"> <!-- Start of 'Python' section. Remove the third paragraph if
           the workshop will teach Python using something other than
           the IPython notebook.
           Details at http://ipython.org/ipython-doc/2/install/install.html#browser-compatibility -->
  <h3>Python</h3>

  <p>
    <a href="http://python.org">Python</a> is a popular language for
    research computing, and great for general-purpose programming as
    well.  Installing all of its research packages individually can be
    a bit difficult, so we recommend
    <a href="https://www.continuum.io/anaconda">Anaconda</a>,
    an all-in-one installer.
  </p>
    <p>
      Regardless of how you choose to install it,
      <strong>please make sure you install Python version 3.x</strong>
      (e.g., 3.4 is fine).
    </p>
    <p>
      We will teach Python using the IPython notebook, a programming environment
      that runs in a web browser. For this to work you will need a reasonably
      up-to-date browser. The current versions of the Chrome, Safari and
      Firefox browsers are all
      <a href="http://ipython.org/ipython-doc/2/install/install.html#browser-compatibility">supported</a>
      (some older browsers, including Internet Explorer version 9
      and below, are not).
    </p>
  <div class="row">
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapsep1" aria-expanded="false" aria-controls="collapsep1"><h4 id="python-windows">Windows</h4></a>
      <div class="collapse" id="collapsep1">
      <a href="https://www.youtube.com/watch?v=xxQ0mzZ8UvA">Video Tutorial</a>
      <ol>
        <li>Open <a href="https://www.anaconda.com/download/">https://www.anaconda.com/download/</a> with your web browser.</li>
        <li>Download the Python 3 installer for Windows.</li>
        <li>Install Python 3 using all of the defaults for installation <em>except</em> make sure to check <strong>Make Anaconda the default Python</strong>.</li>
      </ol>
      </div>
    </div>
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapsep2" aria-expanded="false" aria-controls="collapsep2"><h4 id="python-macosx">Mac OS X</h4></a>
      <div id="collapsep2" class="collapse">
      <a href="https://www.youtube.com/watch?v=TcSAln46u9U">Video Tutorial</a>
      <ol>
        <li>Open <a href="https://www.anaconda.com/download/">https://www.anaconda.com/download/</a> with your web browser.</li>
        <li>Download the Python 3 installer for OS X.</li>
        <li>Install Python 3 using all of the defaults for installation.</li>
      </ol>
      </div>
    </div>
    <div class="col-md-4">
      <a class="" role="button" data-toggle="collapse" href="#collapsep3" aria-expanded="false" aria-controls="collapsep3"><h4 id="python-linux">Linux</h4></a>
      <div class="collapse" id="collapsep3">
      <ol>
        <li>Open <a href="https://www.anaconda.com/download/">https://www.anaconda.com/download/</a> with your web browser.</li>
        <li>Download the Python 3 installer for Linux.<br>
          (Installation requires using the shell. If you aren't
           comfortable doing the installation yourself
           stop here and request help at the workshop.)
        </li>
        <li>
          Open a terminal window.
        </li>
        <li>
          Type <pre>bash Anaconda3-</pre> and then press
          tab. The name of the file you just downloaded should
          appear. If it does not, navigate to the folder where you
          downloaded the file, for example with:
          <pre>cd Downloads</pre>
          Then, try again.
        </li>
        <li>
          Press enter. You will follow the text-only prompts. To move through
          the text, press the space key. Type <code>yes</code> and
          press enter to approve the license. Press enter to approve the
          default location for the files. Type <code>yes</code> and
          press enter to prepend Anaconda to your <code>PATH</code>
          (this makes the Anaconda distribution the default Python).
        </li>
        <li>
          Close the terminal window.
      </ol>
      </div>
    </div>
  </div>
<!--
  <p>
  Once you are done installing the software listed above,
  please go to <a href="setup/index.html">this page</a>,
  which has instructions on how to test that everything was installed correctly.
  </p>
-->
</div> <!-- End of 'Python' section. -->
</div> <!-- div setup_wrap-->
