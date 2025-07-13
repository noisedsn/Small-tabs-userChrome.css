# userChrome.css for Small Firefox Tabs

This is just a tiny userChrome.css file that makes tiny Firefox tabs. It completely eliminates tab scrolling, especially annoying while exiting fullscreen mode.

![Screenshot](/readme_img/screenshot.png)

Tab close button is visible on active tab on hover only, which makes it easy to switch tabs and close the active one.

![Screenshot](/readme_img/screencast.gif)

To learn how to enable custom styles in your Firefox profile, refer to this [userChrome.org instruction](https://www.userchrome.org/how-create-userchrome-css.html). In a few words, you need to:

- Create a new folder named **chrome** inside your Firefox profile folder
- Download **userChrome.css** from this repository to a newly created folder
- In the Firefox, open a new tab, type **about:config**, and set the **toolkit.legacyUserProfileCustomizations.stylesheets** preference to true
- Restart the browser and enjoy!
