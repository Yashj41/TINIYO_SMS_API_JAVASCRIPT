<h1 style="text-align: left;"><span style="font-family: verdana; font-size: large;">How to Send SMS With JavaScript Using Tiniyo</span></h1>
<div class="separator" style="clear: both; text-align: center;"><a href="JavaScript_Tiniyo_cover.jpg" style="margin-left: 1em; margin-right: 1em;"><img alt="Cover Photo" border="0" data-original-height="609" data-original-width="1280" height="auto" src="JavaScript_Tiniyo_cover.jpg" style="border: 1px solid black;" title="Sign Up" width="auto" /></a></div>

<div>
  <div><br /></div>
  <div>
    <span face="Whitney SSm A, Whitney SSm B, Helvetica Neue, Helvetica, Arial, sans-serif"><span style="font-family: verdana; font-size: medium;">Using Tiniyo's REST API, you can send outgoing SMS messages from your Verified Tiniyo Phone number to mobile phones around the globe.</span><br /></span>
    <div><span style="font-family: verdana; font-size: large;"><br /></span></div>
  </div>
  <div><span style="font-family: verdana; font-size: large;">What you need&nbsp;</span></div>
</div>
<div><span style="font-family: verdana; font-size: large;"><br /></span></div>
<div><span style="font-family: verdana;">To follow this tutorial you will need :&nbsp;</span></div>
<div><span style="font-family: verdana;"><br /></span></div>
<div><span style="font-family: verdana;">1. A Tiniyo Account&nbsp;</span></div>
<div><span style="font-family: verdana;"><br /></span></div>
<div><span style="font-family: verdana;">2. JavaScript Code</span></div>
<div><br /></div>
<div><span style="font-family: arial; font-size: medium;"><span face="&quot;Whitney SSm A&quot;, &quot;Whitney SSm B&quot;, &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif" style="background-color: white; letter-spacing: -0.16px;">Tiniyo generates an AuthID&nbsp;</span><span face="&quot;Whitney SSm A&quot;, &quot;Whitney SSm B&quot;, &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif" style="background-color: white; letter-spacing: -0.16px;">and an AuthSecretID when you create a Tiniyo account.</span></span></div>
<div><span style="font-size: medium;"><span face="&quot;Whitney SSm A&quot;, &quot;Whitney SSm B&quot;, &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif" style="background-color: white; color: #0d112b; letter-spacing: -0.16px;"><br /></span></span></div>
<div><span style="font-size: medium;"><span face="&quot;Whitney SSm A&quot;, &quot;Whitney SSm B&quot;, &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif" style="background-color: white; color: #0d112b; letter-spacing: -0.16px;"><br /></span></span></div>
<div>
  <h3 style="background-color: white; box-sizing: inherit; clear: both; color: #333333; font-family: Raleway, Helvetica, Arial, sans-serif; font-size: 1.25rem; line-height: 1.1; margin: 0px auto 0.9375rem; max-width: 100%; overflow-wrap: break-word; padding-left: 0px; padding-right: 0px; word-break: break-word;">Step 1 – Create a Tiniyo Account.</h3>
</div>
<div><br /></div>
<div><span style="font-family: arial; font-size: medium;">If you already have a Tiniyo account, great!&nbsp; Feel free to skip to Step 2.&nbsp; If not, no worries !&nbsp;</span><span style="font-family: arial; font-size: medium;">Go to&nbsp;<a href="https://www.tiniyo.com/" target="_blank">Tiniyo Official Website</a>. Click on Sign Up.</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div>
  <div class="separator" style="clear: both; text-align: center;"><a href="image1.png" style="margin-left: 1em; margin-right: 1em;"><img alt="Sign Up" border="0" data-original-height="609" data-original-width="1280" height="auto" src="image1.png" style="border: 1px solid black;" title="Sign Up" width="auto" /></a></div>
</div>
<div><span style="font-family: arial;"><span style="font-size: medium;"><span>&nbsp;&nbsp; &nbsp;</span></span></span></div>
<div><span style="font-family: arial;"><span style="font-size: medium;">You will redirect to Sign Up page. FIll your details and click on "SignUp" Button.</span></span></div>
<div><br /></div>
<div><br /></div>
<div class="separator" style="clear: both; text-align: center;"><a href="image2.png" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="609" data-original-width="1280" height="auto" src="image2.png" style="border: 1px solid black;" width="auto" /></a></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;">Now, Your Account is Successfully Created. Verify your Phone Number using OTP.</span></div>
<div><span><span><br /></span></span></div>
<div><span style="font-family: arial; font-size: medium;">After that Login into your Account using your Email Id and Password.</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div>
  <div class="separator" style="clear: both; text-align: center;"><a href="image3.png" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="873" data-original-width="1043" height="auto" src="image3.png" style="border: 1px solid black;" width="auto" /></a></div>
  <span style="font-family: arial; font-size: medium;"><br /></span>
</div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div>
  <h3 style="background-color: white; box-sizing: inherit; clear: both; color: #333333; font-family: Raleway, Helvetica, Arial, sans-serif; font-size: 1.25rem; line-height: 1.1; margin: 0px auto 0.9375rem; max-width: 100%; overflow-wrap: break-word; padding-left: 0px; padding-right: 0px; word-break: break-word;">Step 2 – Get Your AuthID and AuthSecretID from Tiniyo Account.</h3>
</div>
<div><br /></div>
<div><span style="font-family: arial; font-size: medium;">Once you are logged into your account you will see Dashboard Like below Image.</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;">Here, You will Find your AuthID and AuthSecretID for Request API.</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div>
  <div class="separator" style="clear: both; text-align: center;"><a href="image4.png" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="913" data-original-width="1920" height="auto" src="image4.png" style="border: 1px solid black;" width="auto" /></a></div>
  <br /><span style="font-family: arial; font-size: medium;"><br /></span>
</div>
<div><span style="font-family: arial; font-size: medium;">Copy Your Key and Secet provided by Tiniyo and Store it.</span></div>
<div><br /></div>
<div><span style="background-color: white; letter-spacing: -0.16px;"><span style="font-family: arial; font-size: medium;">Once you've got all that, let's dive into the code.</span></span></div>
<div>
  <h2 style="background-color: white; box-sizing: border-box; color: #444444; font-family: Whitney SSm A, Whitney SSm B, Helvetica Neue, Helvetica, Arial, sans-serif; font-size: 2rem; font-weight: 300; letter-spacing: -0.16px; line-height: 1.4; margin: 1.7rem 0px 15px; padding: 0px;">Getting started with JavaScript</h2>
</div>
<div><br /></div>
<div><span style="font-family: arial; font-size: medium;">Here is the code for call SMS API using JavaScript. You can use this code with some changes.</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div>
  <div class="separator" style="clear: both; text-align: center;"><a href="codeimage.png" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="770" data-original-width="1034" height="auto" src="codeimage.png" style="border: 1px solid black;" width="auto" /></a></div>
</div>
<div class="separator" style="clear: both; text-align: center;"><br /></div>
<div><span style="font-family: arial; font-size: large;">Save this code with .js extension.</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;">When creating a new message via the API, include the parameters :</span></div>
<p style="text-align: left;"><b><span style="font-size: medium;"><span style="font-family: arial;">To , From , Body,&nbsp;</span><span style="font-family: arial;">TemplateId.</span></span></b></p>
<p style="text-align: left;"><b><span style="font-size: medium;"><span style="font-family: arial;"><br /></span></span></b></p>
<div><span style="font-family: arial; font-size: medium;"><b>To :-&nbsp;</b></span><span style="font-family: arial; font-size: medium;">This parameter determines the destination phone number for your SMS message. Format this number with country code, e.g., 91XXXXXXXXXX.</span></div>
<div><br /></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;"><b>From :-</b>&nbsp;Specifies the Tiniyo Verified Phone number (or)&nbsp; TINIYO that sends this message. This must be a Tiniyo Verified phone number that you own, formatted with country code,&nbsp;</span><span style="font-family: arial; font-size: medium;">e.g., 91XXXXXXXXXX.</span><span style="font-family: arial; font-size: medium;">&nbsp;</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;"><b>Body :-</b>&nbsp;The Body Parameter&nbsp;</span><span style="font-size: medium;"><span style="font-family: arial;">includes the full text of the message you want to send, limited to 1600 characters.</span></span></div>
<div><span style="font-size: medium;"><span style="font-family: arial;"><br /></span></span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;"><b>TemplateID :-</b>&nbsp;TemplateID is mandatory field for the country india.</span></div>
<div><span style="font-family: arial; font-size: medium;">You can get this Id from Verify -&gt; Verify-Template using tiniyo account.</span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<div><span style="font-family: arial; font-size: medium;"><br /></span></div>
<h1 style="text-align: left;"><span face="Roboto, sans-serif"><span style="font-size: large;">&nbsp;Output :</span></span></h1>
<div><span face="Roboto, sans-serif"><span style="font-size: large;"><br /></span></span></div>
<div>
  <span face="Roboto, sans-serif">
    <div class="separator" style="clear: both; text-align: center;"><a href="msgimage.jpg" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="auto" data-original-width="1080" height="761" src="msgimage.jpg" style="border: 1px solid black;" width="auto" /></a></div>
    <div class="separator" style="clear: both; text-align: center;"><br /></div>
  </span>
  <span style="background-color: white; color: #0d112b; font-family: arial; font-size: large; letter-spacing: -0.16px;">That's it, you've sent an SMS message using JavaScript and Tiniyo API.</span>
</div>
<div><span style="background-color: white; color: #0d112b; letter-spacing: -0.16px;"><span style="font-family: arial; font-size: medium;"><br /></span></span></div>
<div><span style="color: #0d112b; font-family: arial; font-size: medium;"><span style="background-color: white; letter-spacing: -0.16px;">Thank You,</span></span></div>
<div><span style="color: #0d112b; font-family: arial; font-size: medium;"><span style="background-color: white; letter-spacing: -0.16px;"><br /></span></span></div>
<div><span style="color: #0d112b; font-family: arial;"><span style="background-color: white; font-size: medium; letter-spacing: -0.16px;"><b>Yash Joshi.</b></span></span></div>
