#  Default CSS for the contentDock RTE Element

This is a the contentDock system default CSS for the RTE element.

**This CSS file is used while publishing your contentDock project in case the used RTE element does not use its own style with a CSS file.**


For more information about the RTE element, please visit:
* [contentDock RTE element](https://www.contentdock.com/en/support/elements-and-styles/element-rte)


Use this CSS file for your own projects. You are allowed to use it without restrictions and adapt it for yourself.


## About contentDock
With the App Construction Kit from contentDock® you can create iOS apps for your business, organization or educational institution - without programming knowledge. 

By default, contentDock® offers a large of different content elements with which you can design your apps.
If these elements are not sufficient for the desired functions of your app, you can develop additional functions and integrate them into your apps with our contentDock® SDK without limits.

Combine the advantages of our construction kit, the workflow and the contentDock® SDK.
Develop your individual functions for the apps of your customers and transforms the apps into exclusive native apps in a few simple steps. 

For more information, please visit:
* [contentDock at a glance](https://www.contentdock.com/en)
* [contentDock for developer](https://www.contentdock.com/en/for-developer)


## Notice

### Images:
Use images in your CSS with the function: 

´´´contentDock-Image(name-of-your-image)´´´

The image with the defined name has to be stored in your file repository of your contentDock Account.
  
Example:
´´´
  background-image: url('contentDock-Image(my-image-name)');
  background-repeat: repeat-y;
  background-size: 100%; 
´´´

### Fonts
Use the pre-installed fonts of contentDock or load your own fonts into your contentDock account. Use the font name in CSS as it will be displayed for your own font files in the file repository. The CSS font name for the pre-installed fonts can be found at 
[contentDock pre-installed fonts](https://www.contentdock.com/en/support/pre-installed-fonts)

Example:
´´´
  font-family: OpenSans-Regular;
´´´

### Disable Scrolling of the RTE
If you want to prevent the general scrolling of the RTE element, please add the following comment to your CSS file at the beginning:

Example
´´´
/* CONTENTDOCK:DISABLE-SCROLLING */
´´´

### License
This file is licensed under the MIT License