## Translating WooCommerce

### Getting .po and .mo files

* Go to [Translating WordPress for WooCommerce](https://translate.wordpress.org/projects/wp-plugins/woocommerce/)

* Select your language

* Click on `Development (trunk)` or `table (latest release)`

* To export the translation files :
  - select `Portable Object Message Catalog (.po/pot)` and click on `export`
  - select `Machine Object Message Catalog (.mo)` and download it too.

* Rename them with your ISO country code, like this :  
**woocommerce-fr_FR.po** and **woocommerce-fr_FR.mo** (for a french translation)

* Move the files on wp-content/languages/plugins (if the folder `plugins` doesn't exist, create it)

### How to edit a translation

#### Prerequisite
You must have the software [Poedit](https://poedit.net/download)

#### Steps

* Open **Poedit** and click on `Edit a Translation`
* Select **the woocommerce-fr_FR.po** file
* Find the text you want to edit (by using Edit > Research, it's faster)
* Your text appears then on `Source text`, edit the new text on `Translation`
* Click on `Save`

It's done ! By registering the .po file, Poedit has generated the new .mo file.


### Resources  
* [ISO country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements)
* [Poedit](https://poedit.net/), the translation editor

### More
* [Contribute to translate WordPress](https://make.wordpress.org/polyglots/teams/?locale=fr_FR)


_Hope it'll help ;)_  
@csocrate

