Emlog Pro version:pro 2.2.0 


Backend->Appearance->Plugin to get shell

Link:https://github.com/emlog/emlog/releases/tag/pro-2.2.0

![image](https://github.com/yangliukk/emlog/assets/130351664/8cecfb14-c48d-4716-8c8a-e0ede6a71625)


Make a compressed package containing malicious files yourself. I have provided "Plugin exploit.zip" for direct use.

![image](https://github.com/yangliukk/emlog/assets/130351664/bddb4070-d75c-4c94-94c4-1b43674f0b91)

Upload Plugin exploit.zip
![image](https://github.com/yangliukk/emlog/assets/130351664/12918d49-3a54-4331-918d-c4b7cb51046d)

Success Upload
![image](https://github.com/yangliukk/emlog/assets/130351664/f8c867d8-2cd7-4ba9-9cc5-8079d1a26284)

Our php file containing phpinfo(); can be found at wwwroot/content/plugins/shell/shell.php
![image](https://github.com/yangliukk/emlog/assets/130351664/0ce33b21-24e9-4c81-9bfb-639a69eb777b)

The code where the problem occurs is in /admin/plugin.php:82
![image](https://github.com/yangliukk/emlog/assets/130351664/3dfd4d6e-1a44-435d-a5e8-9c822c102f96)
