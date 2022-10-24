---
title: How to install wordpress on windows
slug: /how-to-install-wordpress-websites-on-windows/
post_id: 907
image: http://www.ideasmen.com.au/wp-content/uploads/Hi_Chris1.png
---

Original Link to IdeasMen [how-to-install-wordpress-websites-on-windows](http://www.ideasmen.com.au/how-to-install-wordpress-websites-on-windows/)



[vc_widget_sidebar sidebar_id="toc-development-site"]How to install wordpress on windows development machine. This step by step guide to setting up a new installation on a WP, on my pre-configured WAMP devlopment computer



In this example I will be working with 
[**www.FirstHomeBuyers.co**](http://www.FirstHomeBuyers.co)



This is part of the "
**How to create a website**
" professional series, this includes best practices that and processes that we follow to 
**"Make a wordpress website**
" for building out the 
[IdeasMen - Content Constellation](/content-constellation) system which allows niche markets such as Financial Broker Networks, Accounting Groups and Medical Practices to dominate SERP's (Search Engine Ranking Positions) within their local & geographic regions.
	
		
### Download latest wordpress

		
![wpid928-wpid-Download_latest_wordpress.png](https://www.ideasmen.com.au/wp-content/uploads/wpid928-wpid-Download_latest_wordpress1.png) 
Download and uncompress the latest version of wordpress.

*Google 
**Download Wordpress**


*Select Download link


*Un-compress .zip file
	
### Copy wordpress files to development folder

		
![wpid926-wpid-Copy_wordpress_files_to_development_folder.png](https://www.ideasmen.com.au/wp-content/uploads/wpid926-wpid-Copy_wordpress_files_to_development_folder1.png) 
Copy wordpress files to target folder

*Select all files and folders from 
**wordpress**
 folder


*Create a folder that is exactly the same as the target website, eg 
[www.FirstHomeBuyers.co](www.FirstHomeBuyers.co) within your root development folder


*Paste files and folders to this location
	
### Edit Hosts File

		
![wpid929-wpid-Edit_Hosts_File.png](https://www.ideasmen.com.au/wp-content/uploads/wpid929-wpid-Edit_Hosts_File1.png) 
By editing the hosts file you can let Windows & your Browsers know that a particular Domain Name is dealt with by a local server instead of an external server

*Navigate to 
**C:WindowsSystem32driversetc**


*Edit the 
**hosts**
 file with a text editor


*Create an entry to point to 127.0.0.1 (aka local host) with the Domain Name you would like to use to access local host


**Note**
: On Windows 8, you may need to open the file using the Administrator Account as this file is not editable from an ordinary user account
	
### Create a Database to store your Wordpress tables

		
![wpid927-wpid-Create_a_Database_to_store_your_Wordpress_tables.png](https://www.ideasmen.com.au/wp-content/uploads/wpid927-wpid-Create_a_Database_to_store_your_Wordpress_tables1.png) 
*Go to Database Tab


*Type in the name of your database, try to go with the name of the website if possible


*Click Create


*You will now see an empty database ready to be initalized with tables during the wordpress installation process (later)
	
### Modify httpd.conf

		
![wpid930-wpid-Modify_httpd.conf_.png](https://www.ideasmen.com.au/wp-content/uploads/wpid930-wpid-Modify_httpd.conf_1.png) 
The Apache httdp.conf file allows you to add the alias to a server (Domain Name) and the path on the computer where that website resides

*Edit 
**httpd.conf**


*Add an entry for a virtual host, include the Domain Name (same as in 
**hosts**
 file from earlier) and full path to the wordpress website


*Restart all the Apache web services
	
### Start the Wordpress Installation

		
![wpid933-Start_the_Wordpress_Installation.png](https://www.ideasmen.com.au/wp-content/uploads/wpid933-Start_the_Wordpress_Installation1.png) 
*Navigate to the domain name you specified in 
**hosts**
, this should start the Wordpress Installation


*Click 
**Create a Configuration File**


*Fill in the details for the Database you just created
	
### Wordpress Tables will be Created

		
![wpid934-Wordpress_Tables_will_be_Created.png](https://www.ideasmen.com.au/wp-content/uploads/wpid934-Wordpress_Tables_will_be_Created1.png) 
*Click 
**Run the Install**
 to start generating default wordpress tables


*Fill in the Administrator User Name & Password and other details you would like for this Website
	
### Navigate to your local Website

		
![wpid931-Navigate_to_your_local_Website.png](https://www.ideasmen.com.au/wp-content/uploads/wpid931-Navigate_to_your_local_Website1.png) 
In this example it was 
[dev.FirstHomeBuyers.co](http://www.FirstHomeBuyers.co)
	
### Navigate to your local Website Administration

		
![wpid932-Navigate_to_your_local_Website_Administration.png](https://www.ideasmen.com.au/wp-content/uploads/wpid932-Navigate_to_your_local_Website_Administration1.png) 
In this example it was 
[dev.FirstHomeBuyers.co/wp-admin](# )

Fill in the user/password and Log In

<!--
[vc_widget_sidebar sidebar_id="toc-development-site"]<!--  --><div class="LessonContent">
		<div class="LessonSummary">
		<p>How to install wordpress on windows development machine. This step by step guide to setting up a new installation on a WP, on my pre-configured WAMP devlopment computer</p>


<p>In this example I will be working with <a href="http://www.FirstHomeBuyers.co" target="_blank"><strong>www.FirstHomeBuyers.co</strong></a></p>


<p>This is part of the "<strong>How to create a website</strong>" professional series, this includes best practices that and processes that we follow to <strong>"Make a wordpress website</strong>" for building out the <a href="/content-constellation" target="_blank">IdeasMen - Content Constellation</a> system which allows niche markets such as Financial Broker Networks, Accounting Groups and Medical Practices to dominate SERP's (Search Engine Ranking Positions) within their local &amp; geographic regions.</p>	
	</div>
	
		<div class="LessonStep top">
	        <h3 class="StepTitle">Download latest wordpress</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid928-wpid-Download_latest_wordpress1.png" width="540" height="247" alt="wpid928-wpid-Download_latest_wordpress.png" />
</div> <div class="StepInstructions">
	<p>Download and uncompress the latest version of wordpress.</p>
<ol>
<li>Google <strong>Download Wordpress</strong></li>
<li>Select Download link</li>
<li>Un-compress .zip file</li>
</ol>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Copy wordpress files to development folder</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid926-wpid-Copy_wordpress_files_to_development_folder1.png" width="540" height="343" alt="wpid926-wpid-Copy_wordpress_files_to_development_folder.png" />
</div> <div class="StepInstructions">
	<p>Copy wordpress files to target folder</p>
<ol>
<li>Select all files and folders from <strong>wordpress</strong> folder</li>
<li>Create a folder that is exactly the same as the target website, eg <a href="www.FirstHomeBuyers.co" target="_blank">www.FirstHomeBuyers.co</a> within your root development folder</li>
<li>Paste files and folders to this location</li>
</ol>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Edit Hosts File</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid929-wpid-Edit_Hosts_File1.png" width="540" height="330" alt="wpid929-wpid-Edit_Hosts_File.png" />
</div> <div class="StepInstructions">
	<p>By editing the hosts file you can let Windows &amp; your Browsers know that a particular Domain Name is dealt with by a local server instead of an external server</p>
<ol>
<li>Navigate to <strong>C:WindowsSystem32driversetc</strong></li>
<li>Edit the <strong>hosts</strong> file with a text editor</li>
<li>Create an entry to point to 127.0.0.1 (aka local host) with the Domain Name you would like to use to access local host</li>
</ol>

<p><strong>Note</strong>: On Windows 8, you may need to open the file using the Administrator Account as this file is not editable from an ordinary user account</p>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Create a Database to store your Wordpress tables</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid927-wpid-Create_a_Database_to_store_your_Wordpress_tables1.png" width="540" height="357" alt="wpid927-wpid-Create_a_Database_to_store_your_Wordpress_tables.png" />
</div> <div class="StepInstructions">
	<ol>
<li>Go to Database Tab</li>
<li>Type in the name of your database, try to go with the name of the website if possible</li>
<li>Click Create</li>
<li>You will now see an empty database ready to be initalized with tables during the wordpress installation process (later)</li>
</ol>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Modify httpd.conf</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid930-wpid-Modify_httpd.conf_1.png" width="540" height="358" alt="wpid930-wpid-Modify_httpd.conf_.png" />
</div> <div class="StepInstructions">
	<p>The Apache httdp.conf file allows you to add the alias to a server (Domain Name) and the path on the computer where that website resides</p>
<ol>
<li>Edit <strong>httpd.conf</strong></li>
<li>Add an entry for a virtual host, include the Domain Name (same as in <strong>hosts</strong> file from earlier) and full path to the wordpress website</li>
<li>Restart all the Apache web services</li>
</ol>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Start the Wordpress Installation</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid933-Start_the_Wordpress_Installation1.png" width="540" height="311" alt="wpid933-Start_the_Wordpress_Installation.png" />
</div> <div class="StepInstructions">
	<ol>
<li>Navigate to the domain name you specified in <strong>hosts</strong>, this should start the Wordpress Installation</li>
<li>Click <strong>Create a Configuration File</strong></li>
<li>Fill in the details for the Database you just created</li>
</ol>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Wordpress Tables will be Created</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid934-Wordpress_Tables_will_be_Created1.png" width="540" height="393" alt="wpid934-Wordpress_Tables_will_be_Created.png" />
</div> <div class="StepInstructions">
	<ol>
<li>Click <strong>Run the Install</strong> to start generating default wordpress tables</li>
<li>Fill in the Administrator User Name &amp; Password and other details you would like for this Website</li>
</ol>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Navigate to your local Website</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid931-Navigate_to_your_local_Website1.png" width="540" height="508" alt="wpid931-Navigate_to_your_local_Website.png" />
</div> <div class="StepInstructions">
	<p>In this example it was <a href="http://www.FirstHomeBuyers.co" target="_blank">dev.FirstHomeBuyers.co</a></p>
</div>
	</div>
	<div class="LessonStep top">
	        <h3 class="StepTitle">Navigate to your local Website Administration</h3>
		<div class="StepImage">
	<img src="https://www.ideasmen.com.au/wp-content/uploads/wpid932-Navigate_to_your_local_Website_Administration1.png" width="540" height="326" alt="wpid932-Navigate_to_your_local_Website_Administration.png" />
</div> <div class="StepInstructions">
	<p>In this example it was <a href="#" target="_blank">dev.FirstHomeBuyers.co/wp-admin</a><br />
Fill in the user/password and Log In</p>
</div>
	</div>

</div>
<!--  -->
-->

<!--
slide_template - default
_x_quote_quote - 
_x_quote_cite - 
_x_link_url - 
_x_video_aspect_ratio - 16:9
_x_video_m4v - 
_x_video_ogv - 
_x_video_embed - 
_x_audio_mp3 - 
_x_audio_ogg - 
_x_audio_embed - 
_x_entry_body_css_class - 
_x_post_layout - off
_x_entry_bg_image_full - 
_x_entry_bg_image_full_fade - 750
_x_entry_bg_image_full_duration - 7500
_yoast_wpseo_focuskw - install wordpress
_yoast_wpseo_metadesc - How to install wordpress on windows development machine. This step by step guide to setting up a new installation on a WP, on my pre-configured WAMP
_yoast_wpseo_linkdex - 83
_wpas_done_all - 1
_thumbnail_id - 1576
_x_entry_alternate_index_title - 
_wp_rp_related_posts_query_result_cache_expiration - 1597443239
_wp_rp_related_posts_query_result_cache_5 - a:10:{i:0;O:8:"stdClass":2:{s:7:"post_id";s:4:"1013";s:5:"score";s:17:"65.60548375500957";}i:1;O:8:"stdClass":2:{s:7:"post_id";s:4:"1189";s:5:"score";s:17:"65.30779250075062";}i:2;O:8:"stdClass":2:{s:7:"post_id";s:3:"989";s:5:"score";s:17:"60.91334334522711";}i:3;O:8:"stdClass":2:{s:7:"post_id";s:4:"1135";s:5:"score";s:18:"57.017898216974324";}i:4;O:8:"stdClass":2:{s:7:"post_id";s:4:"1192";s:5:"score";s:18:"56.535574103595856";}i:5;O:8:"stdClass":2:{s:7:"post_id";s:4:"1152";s:5:"score";s:18:"55.586658143639674";}i:6;O:8:"stdClass":2:{s:7:"post_id";s:4:"1196";s:5:"score";s:18:"54.113393559491364";}i:7;O:8:"stdClass":2:{s:7:"post_id";s:4:"2020";s:5:"score";s:17:"39.53579358341908";}i:8;O:8:"stdClass":2:{s:7:"post_id";s:4:"1314";s:5:"score";s:17:"38.06244669162494";}i:9;O:8:"stdClass":2:{s:7:"post_id";s:4:"1477";s:5:"score";s:18:"36.589182107476645";}}

-->
