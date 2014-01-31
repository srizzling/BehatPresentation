##What we need?
- To hide the <font color="red"> **complexity** </font> of behat steps and to make it easier on clients.

- To keep the Behat feature files in <font color="red">**source control** </font>

- And still keep the good stuff the Behat Provides in terms of automation.


##Soultions Out There
<a href="http://imgur.com/T6WXKGo"><img src="http://images.smh.com.au/2012/12/11/3880802/1_puzzle-piece-620x349.jpg" title="Hosted by imgur.com" /></a>


##JiraExtenstion
##How it works?
Clients will write behat features in Jira
<a href="http://imgur.com/ECdQXlE"><img src="http://i.imgur.com/ECdQXlE.png" title="Hosted by imgur.com" /></a>

Then you can run these tests by executing the following command:

`vendor/bin/behat @app jira-SKI:51`


##Pros/Cons
<div style="float:right;background:green;color:white;width:50%">
<ul>
<li> Hidden Complexity </li>
<li> Clients can easily access the files </li>
</ul>
</div>

<div style="float:left;background:#FF6666;color:white;width:50%">
<ul>
<li> Behat Features are not in VCS </li>
</ul>
</div>


