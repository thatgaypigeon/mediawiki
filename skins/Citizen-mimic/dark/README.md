# Citizen-mimic
**Citizen** is a MediaWiki skin initially created of the [Star Citizen Wiki](https://starcitizen.tools/). It is very beautiful and clean, as well as being responsive, having a built-in darkmode and customisation options. If you are not familiar with the skin, that may be because it is not currently available on WMF projects as of October 2023.

You can find the skin on [MediaWiki](https://www.mediawiki.org/wiki/Skin:Citizen), or on [GitHub](https://github.com/StarCitizenTools/mediawiki-skins-Citizen).

This folder contains CSS files to mimic the appearance of the Citizen skin. While some of the skin would require JavaScript and/or major HTML layout changes, the general appearance of the skin can be mimicked decently with a couple of CSS files.

## Features

### Darkmode

### Customisation

### Link colours
To help distinguish the various link types on WMF projects, this project includes various different link colours to easily identify where a link will take you. Below are the various types and their properties.

| Link type | Description | CSS selector | CSS variable | Colour | Appearance |
| --------- | ----------- | ------------ | ------------ | ------ |:---------- |
| Default | Default links | `a` (all links)<br/>`.mw-parser-output a` (article links only) | `var(--link-colour)` | `#4775D1`<br/>`rgb(71, 117, 209)`<br/>`hsl(220, 60%, 55%)` | <img src="https://images.placeholders.dev/?width=42&height=18&text=Link&bgColor=%230000&textColor=%234775D1&fontFamily=Rubik&fontSize=16"> |
| Broken  | Broken (new) links (page does not exist) | `a.new` (all links)<br/>`.mw-parser-output a.new` (article links only) | `var(--link-broken-colour)` | `#D5376C`<br/>`rgb(213, 55, 108)`<br/>`hsl(340, 65%, 52.5%)` | <img src="https://images.placeholders.dev/?width=42&height=18&text=Link&bgColor=%230000&textColor=%23D5376C&fontFamily=Rubik&fontSize=16"><img height="18" src="/images/broken-link-display.svg"> |

### Accessibility
