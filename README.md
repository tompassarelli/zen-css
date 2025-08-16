Configuration Guide

1. Add the userChrome to your zen profile folder 
- in zen search about:config in url bar
- set toolkit.legacyUserProfileCustomizations.stylesheets: true
- in zen search about:profiles in url bar
- open Root Directory and click open folder
-- note the flatpk directory is different
- make chrome folder
- put userChrome.css there

2. Add sideberry css to Sideberry 
- click on sideberry settings
- goto Styles Editor tab at the bottom of the list
- copy and paste the css into the code area at the right of the screen

3. Set Zen's "Look and Feel" to single toolbar. 

4. Adjust about:config settings {

theme.sideberry.hide-zen-tabbar: true
zen.tabs.vertical.right-side: false
zen.theme.content-element-separation: 0
zen.view.compact-should-enable-at-startup: false
zen.view.compact-hide-toolbar: true
zen.urlbar.behavior: normal

}



