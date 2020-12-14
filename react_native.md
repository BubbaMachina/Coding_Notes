# React Native Notes

* [Main Menu](index.md)

### Setting Up
The following code is used to startup react native project.

```
npx react-native init projectName

```

### Standard Custom Components
Here are files to a list of custom components i regularly use for all of my projects. I now use a MVC approach:
src =>
  - Assets: Images, icons etc
  - Components: Individual UI components to help build pages
  - Pages: Pages used in the app, the "Controllers"
  - Scripts: Function scripts that do stuff like calculate distance, scale utilties etc 
  - Views: the "html" views of each controller. May consist of smaller sub-views.

Some of these files incldue
* ScaleUtilities.s
* Page.js
*Button.js
