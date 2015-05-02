# Ceti Theme

 Ceti is a very simple flat style theme for Sublime Text 2 and Sublime Text 3.

Based on Soda Theme by Ian Hill [http://buymeasoda.com/](http://buymeasoda.com/)

## Design

![Ceti Light Theme](https://raw.github.com/samuelrafo/Ceti/master/images/Ceti_light.png)

![Ceti Dark Theme](https://raw.github.com/samuelrafo/Ceti/master/images/Ceti_dark.png)

![Ceti Mandarine Theme](https://raw.github.com/samuelrafo/Ceti/master/images/Ceti_mandarine.png)

## Installation

Ceti theme is designed to work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Ceti Theme via the `Package Control: Install Package` menu item. The Ceti Theme package is listed as `Theme - Ceti` in the packages list.

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Ceti`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Ceti Light.sublime-theme"`

**Example Sublime Text 2 User Settings**

    {
        "theme": "Ceti Light.sublime-theme"
    }

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Ceti Light 3.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Ceti Dark 3.sublime-theme"
    }

### Sidebar Folder Icons

Ceti Theme has the ability to use folder icons in the sidebar.

If you'd like to use folder icons in the sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

    "Ceti_folder_icons": true

![Ceti Folder Icons](https://raw.github.com/samuelrafo/Ceti/master/images/Ceti_folder_icons.png)

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
    "color_scheme": "Packages/Theme - Ceti/Ceti Light.tmTheme"
}
```
