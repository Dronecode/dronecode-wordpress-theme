# dronecode-salient-child

Dronecode uses Wordpress along with a *Salient* child theme for most websites
(using a child theme makes it easier to make non GUI customisations without 
having to modify the core theme).

This repo contains the theme used by dronecode: *dronecode-salient-child*

The theme adds a menu header bar to wordpress ABOVE the official top menu. 
The menu has links to all Dronecode websites (QGC, Dronecode, DroneCore, MAVLink) and to the support forum and docs. 
It is designed to provide better inter-linking between the main Dronecore websites.

## Using the Theme

Simply zip up the **dronecode-salient-child** folder. The **dronecode-salient-child.zip** can then be uploaded and activated on 
a wordpress installation that already has Salient installed. 

Currently this adds logo images. The HTML changes are [here](https://github.com/Dronecode/dronecode-wordpress-theme/blob/master/dronecode-salient-child/header.php#L146-L171) (search for `common_dronecode_menu` in header.php)

## Known issues

- Salient is highly configurable, and this addition has only be tested against our current configuration.
- The bar does not work well for logged in users on mobile devices. Generally there are few admin and even less working on mobile, so this is considered minor.
