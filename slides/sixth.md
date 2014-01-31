##What we need?
- To hide the <font color="red"> **complexity** </font> of behat steps and to make it easier on clients.

- To keep the Behat feature files in <font color="red">**source control** </font>

- And still keep the good stuff the Behat Provides in terms of automation.


##Solutions Out There
<iframe width="640" height="480" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.co.nz/maps?f=q&amp;source=s_q&amp;hl=en&amp;geocode=FYtOzAEdG1agBCn_m4FSVtwOOTEnLG49Vpd1Kg%3BFYhyYAEdbdNFBSk1b7ec7en4OTHZxp2oqulGYA&amp;q=Behat,+Uttar+Pradesh,+India+to+Jirat,+West+Bengal,+India&amp;aq=3&amp;oq=behat+to+jira&amp;sll=-41.24437,174.761855&amp;sspn=0.529716,1.056747&amp;ie=UTF8&amp;t=m&amp;saddr=Behat,+Uttar+Pradesh,+India&amp;daddr=Jirat,+West+Bengal,+India&amp;ll=26.627818,82.946777&amp;spn=9.420278,14.0625&amp;z=6&amp;output=embed"></iframe><br />


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