#  Support for password authentication was removed on August 13, 2021. Please use a personal access token instead. remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.

# Problem solution step by step

Now we have need Token authentication requirements for Git operations becouse Github has made changes in password authentication for security purpose.

There are some you need follow to generate Personal access tokens.

> **direct link https://github.com/settings/tokens/new for create personal
> access token**

Step 1 - Open GitHub and **sign in** with your credentials.

Step 2 - Click on the **Setting** menu.

Step 3 - In Setting menu you click on **Developer Settings**, there are two option avaialable for OAuth apps and Personal access tokens.

Step 4 - We need to click on **Personal access token**
[![enter image description here][1]][1]


step 5 - click on the Generate new Token button.

[![enter image description here][2]][2]


[![enter image description here][3]][3]


Step 7 - After that generate new token. Copy that generated token and use this token to access git with username and token.

**Now Manage your credentials in system**

**For window user**

1.) Open Control Panel => User Accounts => Manage your credentials => Windows Credentials.

[![enter image description here][4]][4]


[![enter image description here][5]][5]


  [1]: https://i.stack.imgur.com/ClREj.png
  [2]: https://i.stack.imgur.com/R0Zhi.png
  [3]: https://i.stack.imgur.com/eSSE1.png
  [4]: https://i.stack.imgur.com/D6MX6.png
  [5]: https://i.stack.imgur.com/zqz9S.png

In password box paste your access token and click to save button and reference your desktop.

Now you can access git.

If you are access git in android studio, if ask for a password then add GitHub Personal access token instead of your password.

And if you want use android terminal then paste cammand in terminal 

This is my prsonal access token **ghp_FVLWF8rjU4HdsfsdgqSCjzIZh71yoF5N** don't use my token paste your token

 

     git push  https://ghp_FVLWF8rjU4HdsfsdgqSCjzIZh71yoF5N@github.com/username/yourrep.git
