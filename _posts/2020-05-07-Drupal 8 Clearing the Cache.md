---
layout: post
title: Drupal 8 Clearing the Cache
subtitle: by Mo Helmy
image: /img/D8.jpg
bigimg: /img/Drupal8.jpg
---

## Clearing the Cache Drupal 8 <br/>

Using the rebuild script.
Open settings.php (/sites/default/settings.php) in any text editor. Add this line to the end of the file and save it:<br/>

{: .box-error}
$settings['rebuild_access'] = TRUE;<br/>

After saving visit the next link.<br/>

{: .box-error}
http://www.YourDomainName.com/core/rebuild.php <br/>

In your browser (where www.YourDomainName.com is your site’s URL).<br/> 
After a short pause, you should be redirected to the home page of your site, and the cache should be rebuilt.<br/>
Open settings.php (/sites/default/settings.php) in a text editor.<br/>
Find the line you added with (( $settings[rebuild_access] )) remove this line, and save the file.<br/>

