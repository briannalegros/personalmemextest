Go to [https://github.com/jobindjohn/obsidian-publish-mkdocs](https://can01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2Fjobindjohn%2Fobsidian-publish-mkdocs&data=05%7C01%7CBRIANNALEGROS%40cmail.carleton.ca%7C86e4b3c531a4458fd24508db0bd2bea7%7C6ad91895de06485ebc51fce126cc8530%7C0%7C0%7C638116771980151243%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=4Z5PWpUGJ9PS60ZzIszxEaQOu%2Fxqzw0re%2BLa0X9J0fo%3D&reserved=0 "Original URL: https://github.com/jobindjohn/obsidian-publish-mkdocs. Click or tap if you trust this link.")
- Make sure you're logged in
- Hit use this template; create new repository; make it public; leave the ‘include all branches’ box empty
- Go to settings > actions > general, and change the permissions to the following:
  ![[settingschanges.PNG]]
- Drag and drop your notes onto the /docs/ folder. No subfolders! Delete the current ones.
- Wait for all current actions to complete
- Then go to settings > pages > build from branch – select gh-pages branch. Make sure the root folder is selected.
- ![[rootonly.PNG]]
- When the action completes, you should be golden this time.