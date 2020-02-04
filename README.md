# ZenCart1.3-Newsman - Email Integration
[Newsman](https://www.newsmanapp.com) integration for ZendCart 1.3. Send your customers subscribed to newsletter into NewsMan platform.

# Installation

Installation:
1.  Copy files `newsman.php` & `newsmanclient.php` and paste to your ZenCart root directory in your `admin` folder
2.  - Edit file `{{zencart_root}}/{{your_admin_folder}}/includes/header_navigation.php`
    - Paste the following code `echo '<li><a href="newsman.php" target="_blank">Newsman Import</a></li>';` right under 
     `<ul class="nde-menu-system" onmouseover="hide_dropdowns('in')" onmouseout="hide_dropdowns('out')"> <?php`

2.  Click on `Newsman` on your navigation bar in ADMIN panel

# Setup

1. Fill in your Newsman API KEY and User ID and click `Save`
2. If credentials are correct, select a list and click `Save`
3. Synchronize your customers with active newsletter by clicking `Sync Now`


![](https://raw.githubusercontent.com/Newsman/ZenCart1.3-Newsman/master/assets/1.png)
