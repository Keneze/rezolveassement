# Rezolve Exploratory Test Strategy Document(Technical Assessment)


<h5>Product QA Tester Exercise Brief</h5>
Please create a Test Strategy along with a test suite for the Rezolve Experience Platform using the url
below:
https://create.rezolve.com/engagement-creation
You can create a login using any email address and password.
Please create a test suite for the ‘Triggers’ section of the Platform. An online help guide is available here:
https://help.rezolve.com/merchants/ssp/triggers/
Please submit your exercise with a readme to detail how the test plan is structured.
Thank you.


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
  <li>Delete your Engagements</li>
  <li>Duplicate and edit your Engagements</li>
  <li>Dashboard</li>
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
  <li>Extensive coverage of entire Rezolve Experience Platform (This strategy document remains a living document and will continue to be updated as new information is learned)</li>
  <li>Payment integration will not included</li>
 </div>
<br>

<h3>Test Data:</h3>
 <li>Your GeoZone(s)</li>
 <li></li>

<h3>Test Charters:</h3>

<h4>Instrsution(s):</h4) <br>
 <p>I recommend two experienced testers to pair on this for a fixed time of 
at least 90mins without interruption. This applies to all subsequent test charters.</p>
 <br>
 <h4><ins>Test Charter 1 - Creating Engagement via location Trigger(GeoZones)</ins></h4>
 <h5>Choose a Trigger</h5>
 <div>
 <li>Sign in(or sign up, if not registered) to SSP</li>
 <li>Choose location trigger(Geozones)</li>
 <li>Define the area of your Geozone using the map displayed</li>
 <li>Click on the map to create your GeoZone</li>
 <li>Click on the edge of your GeoZone to increase or reduce the area</li>
 <li>Move the red circle to change the loctaion on the map</li>
 <li>Click on the pin to remove the GeoZone selected</li>
  <li>when satisfied with your GeoZone selection and the area you want to cover, choose a Target Page to continue</li>
 <li>Hover over the area you selected to see the size in Radius and Area, Measured in square metre(m^2)</li>
 <li>Visual check at the bottom right, you should see Guidline Cost Per Day, in pounds for UK users</li> 
 </div>
 
 <h5>Choose a Target Page(information)</h5>
 <h6>(Other Target pages, such as Act, Buy and Url will be tested with a different engagement. You can also edit your existing engagement and change the target to Act, or Buy or Url.)</h6>
 <li>While on the target page, you should see 4 types of Targets -information, Act, Buy & Url</li>
 <li>Select information to tell users about your engagement</li>
 <li>Enter title for your target</li>
 <li>Enter subtitile</li>
 <li>Notice that as you enter information, the Notification Preview on the right side of the page is automatically populated as well</li>
 <li>Customers will see these information when they enter your GeoZone</li>
 
 
 <h5>Drag and drop items from the left to build your information target</h5>
 <li>For image, enter name of image you want to upload</li>
 <li>Click on the pin to remove the GeoZone selected</li>
 <li>click upload button to upload image from your computer or mobile</li>
 <li>Add header and other information you wish to display</li>
 <li>When you are happy with what you want to show to your customers, click configure GeoZone to configure your GeoZone duration</li>

 <h5>Configure GeoZone</h5>
 <li>On the Target Users drop-down, select the category user you want to target</li>
 <li>set your campaign duration</li>
 <li>Set a custom time or select All day duration which your campaign should be active</li>
 <li>set when you want the Trigger Notification, that whether you want users to be notified immediately they enter your GeoZone or on Exit</li>
 <li>If you selected the trigger Nofication to kick in after users have dwell in your GeoZone for a while, set the time</li>
 <li>Click confirm and Publish once you are happy with your GeoZone configuration</li>
 
 <h5>Confirm and Publish</h5>
 <li>Enter the name of your engagement</li>
 <li>Check that all the details of your engagement is correct and displayed correctly</li>
 <li>When you are happy, click create engagement</li>
 
 <h5>Make Payment</h5>
 <li>enter your payment details</li>
 <li>click 'Pay' to activate your engagement</li>
  
 <h4><ins>Test Charter 2 - Creating Engagement via Image Trigger</ins></h4>
 <h5>Choose a Trigger</h5>
 <li>Sign in(or sign up, if not registered) to SSP</li>
 <li>Choose Image trigger</li>
 <li>Drag and drop or browse for image on your computer to upload</li>
 <li>Image size must not be more than 150 MB</li>
 <li>Check that Image format is either *.jpg or *.tif</li>
 <li>Hover over information(i) icon next to Upload an image label to see how watermarked images work with Rezolve enabled devices</li>
 <li>Click on Advanced options drop-down at the bottom to set Watermark Strength</li>
 <li>Watermark Strength of 5 is recommended to make your watermark easily scanable</li>
 <li>select choose a Target Page once you are happy with your uploaded image</li>
 
 <h5>Choose a Target Page(information)</h5>

 <li>Choose a saved target page</li>
 <li>Search for Saved Target page if you target of interest is not on the first page</li>
 <li>Click confirm and publish to continue</li>
 <li>Click back button to change your target if required</li>

 <h5>Confirm and Publish</h5>
 <li>Enter the name of your engagement</li>
 <li>Check that all the details of your engagement is correct and displayed correctly</li>
 <li>When you are happy, click create engagement</li>
 
 <h5>Make Payment</h5>
 <li>enter your payment details</li>
 <li>click 'Pay' to activate your engagement</li>

 
 <h4><ins>Test Charter 3 - Creating Engagement via Audio Trigger</ins></h4>
 
 <h5>Choose a Trigger</h5>
 <li>Sign in(or sign up, if not registered) to SSP</li>
 <li>Choose Audio trigger</li>
 <li>Drag and drop or browse for Audio files on your computer to upload</li>
 <li>Audio size must not be more than 150 MB</li>
 <li>Check that Audio format is either *.mp3, *.wav or or *.m4a</li>
 <li>Check validation error when incorrect Audio format or size is uploaded</li>
 <li>Hover over information(i) icon next to Upload an audio label to see how watermarked audio work with Rezolve enabled devices</li>
 <li>Click on Advanced options drop-down at the bottom to set Watermark Strength</li>
 <li>Watermark Strength of 5 is recommended to make your watermark easily scanable</li>
 <li>select choose a Target Page once you are happy with your uploaded image</li>
 

 <h4><ins>Test Charter 4 - Creating Engagement via Beacon Trigger</ins></h4>

 <h4><ins>Test Charter 5 - Creating Engagement via Link Trigger</ins></h4>

