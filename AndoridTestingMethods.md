![http://core0.staticworld.net/images/article/2012/10/androidbugtrashgaller-100006437-large.png](http://core0.staticworld.net/images/article/2012/10/androidbugtrashgaller-100006437-large.png)

# Introduction #

Testing an application is important part of development process which enhance the applications stability.
Proper testing is important to maintain application which has less bug, is smoother, and has better UX.
The testing methods could be divided to two part aspects for tester:
  * Test by developer such as unit test and debugging tools
  * Test by test engineers such as automated tests and user tests.
  * Beta testing

![http://www.thoughtworks.com/sites/default/files/assets/fabio-cupcake-new4.png](http://www.thoughtworks.com/sites/default/files/assets/fabio-cupcake-new4.png)

# Test by Developer #

Android developers does debugging or testing after developed a part of program and it helps to see whether it works or not. For example they can use program as called as Genymotion which simulates to many android device. Another method is Unit testing.  To do unit tests developer should write test cases with JUnit api.  Also android SDK allows to use a python programs. Also automatic SDK building tools provides a basic test when package is building such as Jenkins.

# Test by Test Engineers #

The test engineering is very important because todays an android app used by millions of user and hundreds of  devices. So an app should be nearly flawless and serve very well UX. A benefit for test by tester is that seeing app from control by perspective of 3rd person so the bugs or bad UX part can be seen by them for example and developer can miss mistake like behaviors at landscape, portrait mode or UX mistakes such as too small button for pressing and not smooth use of application. Other benefits is testing on real devices which is essential because android apps behave different at simulators and devices. Also testing in different versions can cause bug which developer may not notice. The first method is that testing on devices one by one which done by tester who knows the application cases. It's advantage is quick testing which is sometimes very useful . Such as a developer solved a bug then tester makes tests while developer is continuing to coding.  Other method is automated testing which runs on many devices. Automated testing is written by python codes which used a programs such as seeTest. The automated test serves nearly perfects testing which runs on many different devices and versions. So it is necessary to build large scaled app. Also this technique works well with agile development.

![http://1.bp.blogspot.com/-EbpKRVv1kIQ/UvFJ-78KnpI/AAAAAAAB2gQ/a2d6yyV5P04/s1600/CAM00216.jpg](http://1.bp.blogspot.com/-EbpKRVv1kIQ/UvFJ-78KnpI/AAAAAAAB2gQ/a2d6yyV5P04/s1600/CAM00216.jpg)

# Beta Testing #
It is different technique for testing. Beta testing is low cost method also very effective. Beta testing means which releasing apps to limited users. So it gives an opportunity to test on many devices for a long time for free. A disadvantage of beta testing is could lower reputation if app has a lot of bugs. So beta testing should done after  app is ready. Hence it is a final step of testing an app.  There are many tools to use beta testing such as Hockeyapp, Betabound, Testfairy and crash tools Crittercism. So these makes automatically reports bugs to developer.

![http://www.hipmob.com/documentation/integrations/img/HockeyApp/figure14.png](http://www.hipmob.com/documentation/integrations/img/HockeyApp/figure14.png)