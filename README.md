# Rezolve_Tech_Assessment
<h1>Rezolve Exploratory Test Strategy Document(Technical Assessment)</h1>

<h3>Assessment Brief:</h3> 
<p> 
<h5>Product QA Tester Exercise</h5>
Please create a Test Strategy along with a test suite for the Rezolve Experience Platform using the url
below:
https://create.rezolve.com/engagement-creation
You can create a login using any email address and password.
Please create a test suite for the ‘Triggers’ section of the Platform. An online help guide is available here:
https://help.rezolve.com/merchants/ssp/triggers/
Please submit your exercise with a readme to detail how the test plan is structured.
Thank you.
</p>

<h3><ins>About Rezolve Platform and The Test Strategy Adopted:</ins></h3>
<p>
We were behind the world’s first online information platform, and the world’s first cloud e-commerce platform.  Now Rezolve brings you the first instant mobile engagement platform. We’re taking retailing into a new era of customer engagement, instant payments and endless possibilities.
 
For the purpose of this technical assessment and possibly the best approach, we have adopted Exploratory testing as opposed to scripted testing.
 
The adoption of exploratory test strategy was based on the fact that the testers that will carry out the testing, 
specifically myself, have limited knowledge of the application under test. The goal will be to simultaneously learn, 
design tests, and execution them on the fly.
</P>

<h3><ins>Entry Critera and Assumptions:</ins></h3> 
 <li>Rezolve platform is stable and in a testable state</li>
 <li>Engagements can be created on desktops, laptops, and Mobile devices</li>
 <li>Creation of engagement is supported by Windows, Linux, IOS, Android and macOS</li>
 <li>Users need to be registered to access and create engagement on the platform</li>
<br>

<h3>In- Scope:</h3>
<h4>For the purpose of this assessment, the testing would be focused on Triggers and the following test scenarios would be covered</h4>
<ul>
  <li>Create Triggers (such as watermarked images and GeoZones</li>
  <li>Create Target pages (such as Information Pages, and Instant Act Response Forms)</li>
  <li>Link Triggers and Target Pages together to create Engagements</li>
  <li>Edit your Engagements</li>
  <li>Cancel your Engagements</li>
 </ul>
<br>
<h3>Tools:</h3>
<li>TESTPAD - This tool has the necessary functinalities required for documentating your test. It will allow you to create test charters, 
and easily structure your tests in folders as you explore the application. The tool has a very good dashboard with test results and reports a click away.
The test scripts generated at the back of your exploration can easily be converted to regression/automation test suite.</li>
<li>Pen and Paper to write down test ideas as they come to mind</li>
<br>
<h3>Out-of-Scope:</h3> 
 <div>
  <li>Extensive coverage of entire Rezolve Experience Platform (This strategy document remains a living document and will continue to be update as new information is learned)</li>
  <li>Payment integration will not included</li>
 </div>
<br>

<h3>Test Charters:</h3>

<h4>Instrsution(s):</h4) <br>
 <p>I recommend two experienced testers to pair on this for a fixed time of 
at least 90mins without interruption. This applies to all subsequent test charters.</p>
 <br>
 <h4><ins>Test Charter 1 - Creating Engagement via location Trigger(Geozones)</ins></h4>
 <div>
 <li>Sign in(or sign up, if not registered) to SSP</li>
 <li>Choose location trigger(Geozones)</li>
 <li>Define the area of your Geozone using the map displayed</li>
 <li>Click on the map to create your Geozone</li>
 <li>Click on the map to create your Geozone</li>
 </div>
 <br>
 <div>
 <ul>Given I am on the create engagment page</ul>
 <ul>When I click on location Trigger</ul>
 <ul>Then I should see a google map</ul>
 </div>
 <h5>- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  - - - - - - - -  - - - - - - - - - - -- - -</h5>
 <div>
 <ul>Given I am on the google map</ul>
 <ul>When I search a location by postcode</ul>
 <ul>Then I should see the location on the map</ul>
 </div>
<br>
 
 <h4><ins>Test Charter 2 - Creating Engagement via Image Trigger</ins></h4>
 <ul>Given I am on the create engagment page</ul>
 <ul>When I click on location Trigger</ul>
 <ul>Then I should see a google map</ul>
 <h5>- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  - - - - - - - -  - - - - - - - - - - -- - -</h5>
 <ul>Given I am on the google map</ul>
 <ul>When I search a location by postcode</ul>
 <ul>Then I should see the location on the map</ul>
<br>
 
<h3>Test Suite 3 - Create Trigger by Audio</h3>
  <ul>1 Test</ul>
  <ul>2 Test</ul>
<br>
<h3>Test Suite 4 - Create Trigger by Beacon</h3>
 <ul>1 Test</ul>
  <ul>2 Test</ul>
<br>
<h3>Test Suite 5 - Create Trigger by Link</h3> 
 <ul>1 Test</ul>
  <ul>2 Test</ul>
<br>
