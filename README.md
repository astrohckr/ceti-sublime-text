# Ceti Theme

This is designed to match the [Ceti-2](https://github.com/horst3180/Ceti-2-theme) GTK+ theme by [horst3180](https://horst3180.deviantart.com).

This is a mod of [piatto](https://github.com/samuelrafo/piatto) by [samuelrafo](https://github.com/samuelrafo).

## Design

![Ceti Theme](https://raw.github.com/hckr/ceti-sublime-text/master/images/ceti.png)

![Ceti 3 Theme](https://raw.github.com/hckr/ceti-sublime-text/master/images/ceti3.png)

## Installation

Ceti theme is designed to work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Ceti`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Ceti.sublime-theme"`

**Example Sublime Text 2 User Settings**

    {
        "theme": "Ceti.sublime-theme"
    }

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Ceti 3.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Ceti 3.sublime-theme"
    }

### Sidebar Folder Icons

Ceti Theme has the ability to use folder icons in the sidebar.

If you'd like to use folder icons in the sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

    "ceti_folder_icons": true

### Overlay Scrollbars

If you'd like to use the overlay scrollbar, add the following custom setting to your Settings - User file:

```javascript
{
    "overlay_scroll_bars": "enabled"
}
```

## Optional


### Bold folder labels

```javascript
{
    "bold_folder_labels": true
}
```


### Color Scheme

```javascript
{
    "color_scheme": "Packages/Theme - Ceti/Ceti.tmTheme"
}
```
