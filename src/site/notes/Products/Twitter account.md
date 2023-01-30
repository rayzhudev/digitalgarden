---
{"dg-publish":true,"permalink":"/products/twitter-account/"}
---

# Twitter bot
Replies with 🚯 to everyone in the [[GriftList\|grift list]] every time they tweet.


Reread the config file
```
sudo supervisorctl reread
```
Update the process to use the new config file
```
sudo supervisorctl update
```
Restart the process
```
sudo supervisorctl restart replyguy
```