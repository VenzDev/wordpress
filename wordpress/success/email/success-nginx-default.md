**WordPress environment**: [${globals.PROTOCOL}://${env.domain}/](${globals.PROTOCOL}://${env.domain}/)

TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST TEST 

Use the following credentials to access the admin panel:

**Admin Panel**: [${globals.PROTOCOL}://${env.domain}/wp-admin/](${globals.PROTOCOL}://${env.domain}/wp-admin/)  
**Login**: ${user.email}  
**Password**: ${globals.WP_ADMIN_PASS}  

Manage the database nodes using the next credentials:

**phpMyAdmin Panel**: [https://${env.domain}:8443/](https://${env.domain}:8443/)  
**Username**: ${globals.DB_USER}    
**Password**: ${globals.DB_PASS}  

