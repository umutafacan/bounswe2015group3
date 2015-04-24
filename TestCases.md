You can see test cases in excel form from [here](https://docs.google.com/spreadsheets/d/1rlrtcHrLKw1Y0T33QywUwe_gJit--WTQ0uJxVzd-lhc/pubhtml).

### Test Case ID: TC\_1 ###
**Test Priority:** High<br>
<b>Module Name:</b> Registration<br>
<b>Test Title:</b> Register User <br>
<b>Description:</b> Purpose is to check if a user can register to the system <br>
<b>Test Designed By:</b> Burak Yılmaz <br>
<b>Test Design Date:</b> 28/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A <br>
<b>Pre-conditions:</b>
<ul><li>Guest shall have a valid e-mail address and username which is not registered before.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Guest goes to main page or uses application and click on sign up button </td><td> URL of the main page , click button </td><td> Registration form with empty fields shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Guest writes e-mail address which are not registered before.But he or she leaves a requiered field empty </td><td> e-mail = 'ahmet.senturk@boun.edu.tr' </td><td> Warning message is displayed to warn the user to fill the empty fields </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>3 </td><td> Guest fills password field according to rules of password. </td><td> password = 'asdsdYIu2'  </td><td> After checking correction of all these fields, confirmation e-mail is sent. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>4 </td><td> Guest checks the mail box </td><td>  </td><td> Confirmation mail is received </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>5 </td><td> Guest enters to the system by the confirmation link. </td><td>  </td><td> Login is successful. Profile page is dispalyed. Guest becomes a member of the application. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_2</h3>
<b>Test Priority:</b> High<br>
<b>Module Name:</b>  Logining<br>
<b>Test Title:</b> Login <br>
<b>Description:</b> Purpose is to check if a registered member can login to the system. <br>
<b>Test Designed By:</b> Burak Yılmaz <br>
<b>Test Design Date:</b> 28/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A <br>
<b>Pre-conditions:</b>
<ul><li>Member shall has an active account for this platform.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Guest goes to main page or uses application, enters wrong e-mail address or password and click on login button </td><td> URL, submit button, e-mail = 'ahmet.senturkk@boun.edu.tr', password = 'asdsdYIu2' , submit button   </td><td> Warning message is displayed to warn the user about incorrect e-mail address or password. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Guest enters correct e-mail address or password and click on login button </td><td> e-mail = 'ahmet.senturk@boun.edu.tr',password = 'asdsdYIu2' , submit button </td><td> Login is successful. Profile page is dispalyed. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_3</h3>
<b>Test Priority:</b> High<br>
<b>Module Name:</b>  Searching <br>
<b>Test Title:</b> Search <br>
<b>Description:</b> Purpose is to check if basic search works correctly <br>
<b>Test Designed By:</b> Burak Yılmaz <br>
<b>Test Design Date:</b> 28/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> <br>
<b>Pre-conditions:</b>
<ul><li>There should be at least one group and event in the system.<br>
</li><li>There should be an active member using the application.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> User enters a keyword in the search box and clicks the search button  </td><td> keyword='basketball' , submit button </td><td> Events and groups related to the given keyword 'basketball' are displayed according to the their relation with semantic tagging </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_4</h3>
<b>Test Priority:</b> High <br>
<b>Module Name:</b>  Changing Profile <br>
<b>Test Title:</b> Change Password <br>
<b>Description:</b> Purpose is to check if a user can change his/her password. <br>
<b>Test Designed By:</b> Ahmet Enes BAYRAKTAR <br>
<b>Test Design Date:</b> 29/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> <br>
<b>Pre-conditions:</b>
<ul><li>Member shall has an active account and valid email password.<br>
</li><li>Member shall log in to the application.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member will choose “update your profile” option on the his/her profile page. </td><td> URL , click button  </td><td> His/her profile page shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member will choose “change password” option. </td><td> click button </td><td> Change password page shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>3 </td><td> Member shall write the password to the ”old password” textbox. </td><td> password = 'asdsdYIu2'  </td><td> Member shall fill the blanks correctly. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>4 </td><td> System will check if written password is correct or not . </td><td>  </td><td> Warning message is displayed if is password is not correct. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>5 </td><td> Member shall write the new password to the “new password” textbox. </td><td> password = 'Ilove352' </td><td> Member shall fill the blanks correctly. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>6 </td><td> System will check if written password is strong enough. </td><td>  </td><td> Warning message is displayed if password is not strong enough. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>7 </td><td> Member shall click the button “Save Changes”. </td><td> submit button  </td><td> Password change is successful page is displayed. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<h3>Test Case ID: TC_5</h3>
<b>Test Priority:</b> Medium <br>
<b>Module Name:</b>  Changing Profile<br>
<b>Test Title:</b> Update Profile Page <br>
<b>Description:</b> Purpose is to check if a user can update his/her profile page. <br>
<b>Test Designed By:</b> Ahmet Enes BAYRAKTAR <br>
<b>Test Design Date:</b> 29/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> <br>
<b>Pre-conditions:</b>
<ul><li>Member shall be logged in.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member will choose “update your profile” option on the his/her profile page. </td><td> URL , click button  </td><td> His/her profile page shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member will make any changes on his/her profile </td><td> role = 'Assistant'  </td><td> The changes will be submitted to the system. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>3 </td><td> System checks whether there is invalid changes and inform the member. </td><td> warningMessage = 'You can't change your role until you become an Assistant'  </td><td> Warning message is displayed if changes are not valid. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>4 </td><td> Member shall click “save changes” button. </td><td> submit button </td><td> The profile page will be updated. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_6</h3>
<b>Test Priority:</b> Medium <br>
<b>Module Name:</b>  Changing Profile<br>
<b>Test Title:</b> Changing Privacy Settings <br>
<b>Description:</b> Purpose is to check if a user can change his/her privacy settings <br>
<b>Test Designed By:</b> Ahmet Enes BAYRAKTAR <br>
<b>Test Design Date:</b> 29/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A  <br>
<b>Pre-conditions:</b>
<ul><li>Member shall be logged in</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member will choose “update your profile” option on the his/her profile page. </td><td> URL , click button  </td><td> His/her profile page shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member will choose “privacy settings” option. </td><td> selection option  </td><td> Privacy settings page shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>3 </td><td> Member will make any changes on these settings. </td><td> Visibility of profile page = 'Only registered users' </td><td> The changes will bu submitted to the system. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>4 </td><td> System checks whether there is invalid changes and inform the member. </td><td> warningMessage = 'Successfully updated'  </td><td> Warning message is displayed if changes are not valid. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>5 </td><td> Member shall click “save changes” button. </td><td> submit button  </td><td> The privacy settings will be updated. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_7</h3>
<b>Test Priority:</b> High <br>
<b>Module Name:</b>  Event settings <br>
<b>Test Title:</b> Creating an event <br>
<b>Description:</b> Purpose is to check if a user can create an event. <br>
<b>Test Designed By:</b> Ahmet Enes BAYRAKTAR <br>
<b>Test Design Date:</b> 29/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A  <br>
<b>Pre-conditions:</b>
<ul><li>Member shall have a registered account.<br>
</li><li>Member shall log in to the application.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member shall click on the create event button. </td><td> URL , click button </td><td> Create an event page shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member shall fill event creation page appropriatly. </td><td> topic = 'CmpE 352 sınavı' , date = '30/03/15' , isPeriodic = 'No' , period = 'null' , participants = 'Burak Yilmaz, Cem Özen' , tagList = 'sınav, CmpE 352' , content = 'Arkadaşlar yardımınız lazım sınav için ' </td><td> Warning message is displayed if the entries are not valid. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>3 </td><td> Member shall submit his/her event. </td><td> submit button  </td><td> Event will be displayed in the event list. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID:  TC_8</h3>
<b>Test Priority:</b> High <br>
<b>Module Name:</b>  Event settings <br>
<b>Test Title:</b> Joining an event <br>
<b>Description:</b> Purpose is to check if a user can join to an event. <br>
<b>Test Designed By:</b> Ahmet Enes BAYRAKTAR <br>
<b>Test Design Date:</b> 29/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A  <br>
<b>Pre-conditions:</b>
<ul><li>Member should be logged into the system.<br>
</li><li>Member should not have been added to that event.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member sees or searches for an event and chooses it. </td><td> URL , keyword = 'parti' , submit button </td><td> Search results is displayed. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member involves in that event by clicking join button. </td><td> selection option  </td><td> Member will be added to the event. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_9</h3>
<b>Test Priority:</b> Medium <br>
<b>Module Name:</b>  Posting <br>
<b>Test Title:</b> Posting on an event page <br>
<b>Description:</b> Purpose is to check if a user can post to an event. <br>
<b>Test Designed By:</b> Ahmet Enes BAYRAKTAR <br>
<b>Test Design Date:</b> 29/03/15 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A  <br>
<b>Pre-conditions:</b>
<ul><li>Member should be logged into the system.<br>
</li><li>Member should have already joined an event.</li></ul>

<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member goes to the event page. </td><td> URL </td><td> The page of the event shows up. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member writes a comment or attaches files. </td><td> topic = 'CmpE 352 sınavı' date = '29/03/15' content = 'Hallederiz, sesli study de bekliyoruz'  </td><td> Member prepares his/her comment. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>3 </td><td> Member clicks the post button. </td><td> submit button </td><td> Post will be posted in the event page. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_10</h3>
<b>Test Priority:</b> High <br>
<b>Module Name:</b>  Group settings <br>
<b>Test Title:</b>  Creating a group. <br>
<b>Description:</b>  The purpose is to create a group according to member’s decisions. <br>
<b>Test Designed By:</b> Umut Gülsün <br>
<b>Test Design Date:</b> 29.03.2015 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A  <br>
<b>Pre-conditions:</b>
<ul><li>Member shall have a registered account.<br>
</li><li>Member shall log in to the application.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member clicks the “create a group” button on his/her profile page.  </td><td> click button   </td><td> New window pops up with form. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member fills the form and hits create. </td><td> name = 'Hackers' , memberList = 'Ahmet Şenturk , Burak Yilmaz , Bünyamin Ince' , submit button </td><td> New group is created.  </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_11</h3>
<b>Test Priority:</b> Medium <br>
<b>Module Name:</b>  Group settings <br>
<b>Test Title:</b>  Updating information of a group page <br>
<b>Description:</b>  The purpose is to update information of a group page  <br>
<b>Test Designed By:</b> Umut Gülsün <br>
<b>Test Design Date:</b> 29.03.2015 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A  <br>
<b>Pre-conditions:</b>
<ul><li>Member shall log in to the application.<br>
</li><li>Member shall be admin of the group.</li></ul>


<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Admin of the group shall click the button “update information” of the group page.   </td><td> URL , click button  </td><td> New window pops up with form. </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member fills the form and hits save. </td><td> name =   'Brave Hackers' , submit button  </td><td> Group info is updated.  </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />

<h3>Test Case ID: TC_12</h3>
<b>Test Priority:</b> Low <br>
<b>Module Name:</b> Group Settings <br>
<b>Test Title:</b>  Leaving a Group <br>
<b>Description:</b> The purpose is leaving from a group <br>
<b>Test Designed By:</b> Abdurrahman Can Kurtan <br>
<b>Test Design Date:</b>  29/03/2015 <br>
<b>Test Executed By:</b> N/A <br>
<b>Test Execution Date:</b> N/A  <br>
<b>Pre-conditions:</b>
<ul><li>User shall be logged in to the system.<br>
</li><li>User shall be a member of the group.</li></ul>

<table><thead><th> <b>Steps</b> </th><th> <b>Test Steps</b> </th><th> <b>Test Data</b> </th><th> <b>Expected Result</b> </th><th> <b>Actual Result</b> </th><th> <b>Status (Pass/Fail)</b> </th><th> <b>Notes</b> </th></thead><tbody>
<tr><td>1 </td><td> Member goes to the group page </td><td> URL </td><td> The page of the group shows up </td><td>N/A</td><td>N/A</td><td>N/A</td></tr>
<tr><td>2 </td><td> Member clicks to leave group button </td><td> leave button </td><td> User should be left from the group </td><td>N/A</td><td>N/A</td><td>N/A</td></tr></tbody></table>

<hr />