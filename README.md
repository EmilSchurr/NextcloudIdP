# Use Nextcloud as identity provider
The <auth.php> is designed to access Nextclouds oc_* database to authenticate users created within Nextcloud on a site outside of Nextcloud. Both sessions are handled seperately, only login data and groups are fetched.
SSO is currently not working, so you would have to log in twice if you want to access nextcloud and the other site, but they work at the same time using different sessions.
Works with newer Nextcloud releases from 21.x.x - current
Older versions will work, but disabled users will still be able to log in.
