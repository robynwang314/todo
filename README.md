# ToDo App #

This single-page to-do application features a fluid user interface that– by using JavaScript– allows users to rapidly add dynamic content.
<br/><br/>
<b>Tools & Languages:</b> Javascript, jQuery, AJAX, JSON, AWS, Bootstrap, Carrierwave, Devise, SimpleForm, RSpec, HTML5 and CSS3.

## Table of Contents ##
<ul> 
  <li><a href="#about"> About </a></li>
  <li><a href="#technologies"> Built With </a></li>
  <li><a href="#setup"> Getting Started </a></li>
  <li><a href="#usage"> Deployment </a></li>
  <li><a href="#contact"> Contact</a></li>
</ul>

<div id="about"></div> 

## About ##
This single page ToDo app allows users to create a ToDo list and check items off. 

<div id="technologies"></div> 

## Built With ##
This app integrates the following: 
<ul>
  <li><a href="https://aws.amazon.com/" rel="nofollow">AWS</a></li>
  <li><a href="https://github.com/twbs/bootstrap-rubygem">Bootstrap </a></li>
  <li><a href="https://github.com/rails/jquery-rails">JQuery-Rails</a> Gem</li>
</ul>

<div id="setup"></div> 

## Getting Started ##
Enter into your development environment into the directory where your code will be living in, and create a new application. 
<pre>$ rails new todo --database=postgresql --skip-turbolinks --skip-test-unit</pre>

<p>Once the application is created, enter into your "ToDo" text editor and edit your database.yml file accordingly.</p>

<p>Then change directory into your ToDo project and create the initial database and start the server</p>
<pre><code> $ rake db:create</code></pre>

<p>In a separate terminal window, enter into your ToDo folder and set up the web development pipeline</p>
<pre><code>create new Github repository
create project in heroku and then deploy it to heroku</code></pre>

### Setting Up Testing Environment ###
Install RSpec following the <a href="https://github.com/rspec/rspec-rails">RSpec</a> documentation

Once the spec folder is created,we can remove the default Ruby on Rails <code>Test::Unit</code>.
<pre>$ rm -rf test</pre>

Now, run this command to run the test suite.
<pre>$ bundle exec rspec</pre>

Then, run the test suite again by running the following command:
<pre>$ bundle exec rspec</pre>

It tells us we have one test that is pending. So edit <code>spec/helpers/grams_helper_spec.rb </code>and remove the line so it looks like this:
<pre>RSpec.describe GramsHelper, type: :helper do
end 
</pre>

Save the file and run the test suite again. The response returns to tell us we don't have any tests failing or passing. 


<div id="usage"></div> 

## Deployment ##
This live project can be view at: https://todoster-robyn-wang.herokuapp.com/

And it's code can be found at: https://github.com/robynwang314/todo

### Screenshots ###

<b>Landing Page:</b> <br/>
<img src="/app/assets/images/home.png" alt="Homepage" width="45%">

<div id="contact"></div> 

## Contact ##

<ul>
  <li><a href="http://robynwang-portfolio.herokuapp.com/" target="_blank">Portfolio</a></li>
  <li><a href="https://www.linkedin.com/in/tyrobynwang" target="_blank">LinkedIn</a></li>
  <li><a href="https://github.com/robynwang314" target="_blank">GitHub</a></li>
</ul>
