#DRUSH COMMAND TO MNPP

### Quickly management to MNPP

**Examples:**

<pre><code> 	drush mnpp start                          Start all services    
 	 drush mnpp stop                           Stop all services     
  	 drush mnpp --nginx=start|stop             Start or Stop nginx   
 	 drush mnpp --percona=start|stop           Start or Stop percona 
 	 drush mnpp --php-fpm=start|stop           Start or Stop php-fpm 
</code></pre>
**Arguments:**
<pre><code> 	start                                     Start MNPP services 
  	 stop                                      Stop MNPP services  
</code></pre>

**Options:**
<pre><code> 	--nginx                                    
 	 --percona                                  
 	 --php-fpm
</code></pre>