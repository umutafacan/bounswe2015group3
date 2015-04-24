# Use case diagram #

http://i.imgur.com/CVMiYcz.jpg?1?1729

# Use Case #1 #
  * **Name:** Registering to the applciation
  * **Actors:** Guest (will become member)
  * **Purpose:** To register to the application
  * **Preconditions:**
    1. Actor shall have a valid e-mail address and username which is not registered before.
  * **Steps:**
    1. Guest views the site or the app.
    1. Guest shall clicks Sign Up to be registered.
    1. Guest shall writes e-mail address and password.
    1. Guest  shall accepts Terms and Conditions.
    1. Guest shall clicks complete button.
    1. The application will send an e-mail to the actor for the confirmation.
    1. Guest shall verify the e-mail address

  * **Postconditions:**
    1. A member account created on the system.
  * **Exceptions:**
    1. E-mail address doesn’t belong to Boğaziçi University and CMPE.
    1. Password is not strong enough.

# Use Case #2 #
  * **Name:** Logging in
  * **Actors:** Members
  * **Purpose:** To login
  * **Preconditions:**
    1. Member shall has an active account for this platform.
    1. Member shall provide correct e-mail address and password.

  * **Steps:**
    1. Member will enter his/her boun e-mail address and password
    1. System checks these credential correct or not, and informs the member about this check

  * **Postconditions:**
    1. Member will login to the system and see his/her  homepage if the credentials are correct.
    1. Member will stay in the login page and ‘Forget your e-mail address or passward’ warning will be shown if the credentials are not correct.

# Use Case #3 #
  * **Name:**Forgot password
  * **Actors:** Members
  * **Purpose:** To create a new password after forgot password
  * **Preconditions:**
    1. Member shall has an active account and valid e-mail password.
  * **Steps:**
    1. Member will choose “forgot password” option.
    1. Member will be directed to the “forgot password” page.
    1. Member will enter his/her e#mail address.
    1. System will check if the e#mail address belongs to a registered member.
    1. System will send an e#mail to the member including the new password creating page link.
    1. Member will go to the link and enter new password.

  * **Postconditions:**
    1. The password of the member will be updated in the system.

# Use Case #4 #
  * **Name:** Changing password
  * **Actors:** Members
  * **Purpose:** To change password
  * **Preconditions:**
    1. Member shall has an active account and valid e#mail password.
    1. Member shall log in to the application

  * **Steps:**
    1. Member will choose “update your profile” option on the his/her profile page
    1. Member will choose “change password” option.
    1. Member shall write the password to the ”old password” textbox
    1. System will check if written password is correct or not
    1. Member shall write the new password to the “new password” textbox
    1. System will check if written password is strong enough
    1. Member shall click the button “Save Changes”

  * **Postconditions:**
    1. The password of the member will be updated in the system.

# Use Case #5 #
  * **Name:** Changing information profile page
  * **Actors:** Members
  * **Purpose:** To update basic information of members
  * **Preconditions:**
    1. Member shall be logged in.
  * **Steps:**
    1. Member will choose “update your profile” option on the his/her profile page
    1. Member will make any changes on his/her profile
    1. System checks whether there is invalid changes and inform the member
    1. Member shall click  “save changes” button  .

  * **Postconditions:**
    1. System will update all changes on an member

# Use Case #6 #
  * **Name:** Changing privacy settings of profile
  * **Actors:** Members
  * **Purpose:** To change privacy settings of a member
  * **Preconditions:**
    1. Member shall be logged in.
  * **Steps:**
    1. Member will choose “update your profile” option on the his/her profile page
    1. Member will choose “privacy settings” option
    1. Member will make any changes on these settings
    1. System checks whether there is invalid changes and inform the member
    1. Member shall click  “save changes” button  .

  * **Postconditions:**
    1. The system checks the privacy settings of a member
    1. According to these settings, profile pages of members will be seen or not  from other people(guests,members or specific people)


# Use Case #7 #
  * **Name:**  Searching(by member name, event name, group name and tag)
  * **Actors:** Members/Guests
  * **Purpose:** To searche a member, event, group or a tag
  * **Preconditions:**
    1. There should be a textbox can be used in every pages of site .
    1. There should be a algorithm that performs best performace searches.

  * **Steps:**
    1. Member or guest enters the word that he/she wants search to “search” textbox
    1. Member or guest clicks the search button
    1. Member or guest sees all the results

  * **Postconditions:**
    1. The system should remember what a member searched before to offer him/her more accurate results

# Use Case #8 #
  * **Name:** Creating a group
  * **Actors:** Members
  * **Purpose:** To create a group according to member’s decisions
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.

  * **Steps:**
    1. There should be new window pops up after a member clicks the “create a group” button in his/her profile page.
    1. There should be enough functionality on this window to let the member make all decisions about settings of this group like name, description and privacy of the group.
    1. There should be “add photo” button to let the member upload a photo to make it group photo, optionally.
    1. There should be list of textboxes for e#mail addresses of people that admin member wantsto invite to this group.


  * **Postconditions:**
    1. The system shall  create this group and take admin member to the group page.
    1. The system shall make necessary changes in databases about criterion of the group


# Use Case #9 #
  * **Name:** Updating information of a group page
  * **Actors:** Members
  * **Purpose:** To update information of a group page
  * **Preconditions:**
    1. Member shall log in to the application.
    1. Member shall be admin of the group

  * **Steps:**
    1. Admin of the group shall click the button “update information” of the group page
    1. The same window in creation of the group page will open again.
    1. Admin of the group will update information of the group
    1. After the changes, admin shall click the button “Save Changes”

  * **Postconditions:**
    1. The system should update changeson this group and take admin member to the  group page.
    1. The system should make necessary changes in databases about updatemember of the group


# Use Case #10 #
  * **Name:** Changing privacy settings of a group
  * **Actors:** Members
  * **Purpose:** To set privacy seeting of a group
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the appliction.
    1. Member shall be a participant of the group.
    1. Member shall have the authority to set the privacy settings.
  * **Steps:**
    1. Member shall go to the group page.
    1. Member shall click on the change privacy settings button.
    1. Member shall change privacy settings as s/he wishes.
    1. Member shall submit the changes.
  * **Postconditions:**
    1. The application shall set the changes.
    1. The application shall notify members of the group that the privacy settings have been changed.

# Use Case #11 #
  * **Name:** Deleting a group
  * **Actors:** Members
  * **Purpose:** To disband a group
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
    1. Member shall be a participant of the group.
    1. Member shall have the authority of deleting the group.
  * **Steps:**
    1. Member shall go to group page.
    1. Member shall click on the delete group button.
  * **Postconditions:**
    1. The application shall notify member of the group that the group has been disbanded.
# Use Case #12 #
  * **Name:** Logging out
  * **Actors:** Members
  * **Purpose:** Logging out
  * **Preconditions:**
    1. Member should be logged into the system.
  * **Steps:**
    1. Member clicks log out.
  * **Postconditions:**
    1. The members has logged out.
# Use Case #13 #
  * **Name:** Creating an event
  * **Actors:** Members
  * **Purpose:** To organize an event
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
  * **Steps:**
    1. Member shall click on the create event button.
    1. Member shall fill event creation page appropriatly.
    1. Member shall submit his/her event.
  * **Postconditions:**
    1. The application will give confirmation message to the member.
    1. The application will publish the created event.

# Use Case #14 #
  * **Name:** Subscribing to a group
  * **Actors:** Members
  * **Purpose:** To be up-to-date about the topic of the group
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
    1. Member shall find a group for herself/himself.
  * **Steps:**
    1. Member shall click on the subscribe button.
  * **Postconditions:**
    1. The application will add the member to the group.
    1. The application will notify the subscribers about any new content in the group.

# Use Case #15 #
  * **Name:** Unsubscribing from a group
  * **Actors:** Members
  * **Purpose:** To leave a group
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
    1. Member shall be a participant of the group.
  * **Steps:**
    1. Member shall click on the unsubscribe button.
  * **Postconditions:**
    1. The application will delete the member from the group.
    1. The application will not send any notifications about the group to the member.

# Use Case #16 #
  * **Name:** Posting on a group page
  * **Actors:** Members
  * **Purpose:** To post a new content to a group page
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
    1. Member shall be a participant of the group.
  * **Steps:**
    1. Member shall write a post and click on the post button.
  * **Postconditions:**
    1. The application will put the post on the group page to publish the post.

# Use Case #17 #
  * **Name:** Showing event list
  * **Actors:** Members
  * **Purpose:** To see event list
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
  * **Exceptions:**
    1. Private events shall not be published.
  * **Steps:**
    1. Member shall click on the event list button.
  * **Postconditions:**
    1. The application will get published events and list them for the member.

# Use Case #18 #
  * **Name:** Showing member list
  * **Actors:** Members
  * **Purpose:** To see member list
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to application.
  * **Exceptions:**
    1. Member can not see a member that blocked him/her.
    1. Member can not see a member that does not want to be in the list.
  * **Steps:**
    1. Member shall click on the member list button.
  * **Postconditions:**
    1. The application will get member list and serve it to the member.

# Use Case #19 #
  * **Name:** Inviting someone to a group
  * **Actors:** Members
  * **Purpose:** To invite some to a group
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
    1. Member shall be a participant of the group.
  * **Steps:**
    1. Member shall go to the group page.
    1. Member shall click on the invite button.
    1. Member shall select a member.
  * **Exceptions:**
    1. Invited member shall be accepting invitations.
  * **Postconditions:**
    1. Invited member shall accept or reject the invitation.
    1. In case of accepting: the application shall add the invited member to the group and notify further content changes.
    1. In case of rejecting: The application shall give a message to the member that his/her invitation is rejected.

# Use Case #20 #
  * **Name:** Sharing media
  * **Actors:** Members
  * **Purpose:** To share certain photo, video etc.
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
  * **Steps:**
    1. Member shall upload the media that s/he wants.
    1. Member shall submit the media.
  * **Postconditions:**
    1. The application shall get the media and publish it.

# Use Case #21 #
  * **Name:** Changing privacy settings of a group
  * **Actors:** Members
  * **Purpose:** To set privacy seeting of a group
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the appliction.
    1. Member shall be a participant of the group.
    1. Member shall have the authority to set the privacy settings.
  * **Steps:**
    1. Member shall go to the group page.
    1. Member shall click on the change privacy settings button.
    1. Member shall change privacy settings as s/he wishes.
    1. Member shall submit the changes.
  * **Postconditions:**
    1. The application shall set the changes.
    1. The application shall notify members of the group that the privacy settings have been changed.

# Use Case #22 #
  * **Name:** Deleting a group
  * **Actors:** Members
  * **Purpose:** To disband a group
  * **Preconditions:**
    1. Member shall have a registered account.
    1. Member shall log in to the application.
    1. Member shall be a participant of the group.
    1. Member shall have the authority of deleting the group.
  * **Steps:**
    1. Member shall go to group page.
    1. Member shall click on the delete group button.
  * **Postconditions:**
    1. The application shall notify member of the group that the group has been disbanded.

# Use Case #23 #
  * **Name:** Joining an event
  * **Actors:** Membera
  * **Purpose:** To involve an event, see event time, place and other participants of the event.
  * **Preconditions:**
    1. Member should be logged into the system.
    1. Member should not have been added to that event.
  * **Steps:**
    1. Member sees or searches for an event and chooses it.
    1. Member involves in that event by clicking join button.
  * **Postconditions:**
    1. The system adds the member to the event.
    1. The system notifies the participants about any new posts in the event.

# Use Case #24 #
  * **Name:** Leaving an event
  * **Actors:** Members
  * **Purpose:** To leave an event
  * **Preconditions:**
    1. Member should be logged into the system.
    1. Member should have already joined an event.
  * **Steps:**
    1. Member looks at his or her events.
    1. Member leaves the event by clicking the leave button.
  * **Postconditions:**
    1. The member is not joining the event any more.
    1. The system does not notify the member about new posts in the event.

# Use Case #25 #
  * **Name:** Posting on an event page
  * **Actors:** Members
  * **Purpose:** Posting on an event page
  * **Preconditions:**
    1. Member should be logged into the system.
    1. Member should have already joined an event.
  * **Steps:**
    1. Member goes to the event page.
    1. Member writes a comment or attaches files.
    1. Member clicks the post button.
  * **Postconditions:**
    1. Other members are notified.

# Use Case #26 #
  * **Name:** Inviting someone to an event
  * **Actors:** Members
  * **Purpose:** Inviting someone to an event
  * **Preconditions:**
    1. Member should be logged into the system.
    1. Member should have the right to invite someone to an event.
  * **Steps:**
    1. Member goes to the event page.
    1. Member clicks invite.
    1. Member enters the names of the members to be invited.
    1. Member clicks done.
  * **Postconditions:**
    1. The invited members are notified by the system.

# Use Case #27 #
  * **Name:** Deleting an event
  * **Actors:** Members
  * **Purpose:** Deleting an event
  * **Preconditions:**
    1. Member should be logged into the system.
    1. Member should have the right to delete the event.
  * **Steps:**
    1. Member goes to the event page.
    1. Member clicks delete event.
  * **Postconditions:**
    1. The members are notified about the deletion.