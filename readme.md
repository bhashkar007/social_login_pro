Solving issues with passing through firewall
-----------------------------------------------------------------

Change proxy settings in the following files:

```
system/expressionengine/third_party/social_login_pro/facebook_sdk/base_facebook.php
system/expressionengine/third_party/social_login_pro/libraries/facebook_oauth.php
system/expressionengine/third_party/social_login_pro/google-api-php-client/Google/IO/curl.php
system/expressionengine/third_party/social_login_pro/libraries/google_oauth.php
system/expressionengine/third_party/social_login_pro/libraries/twitter_oauth.php

```

1. Search for "SET PROXY"
2. Add your proxy url + port number.
3. Save files and re-install Social Login Pro on Express Engine. 