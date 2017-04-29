## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ricard91/AospExtendend/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ricard91/AospExtendend/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
<p align="center">
<img src="https://github.com/AospExtended/manifest/raw/7.1.1/aex_logo.png" width="320px" height="320px" > 
</p>

AospExtended Nougat
===========
AospExtended is just an extension to AOSP, through which we 
are trying to provide a stock AOSP experience along with some important 
customization features. We have cherry-picked the features from many 
other projects and hence we are very thankful to them.

Credits
-------
* [**JDCTeam (Base)**](https://github.com/AOSP-JF-MM)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**AOSiP**](https://github.com/AOSIP)
* [**ZephyrOS**](https://github.com/Zephyr-OS)
* [**TurboROM**](https://github.com/TurboROM)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**SlimRoms**](https://github.com/SlimRoms)
* [**BlissRoms**](https://github.com/BlissRoms)
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**GZR Community**](https://plus.google.com/communities/109330559573276360638)
* [**AOSiP**](https://github.com/AOSiP)
* [**OmniROM**](https://github.com/omnirom/)

How to Build?
-------------

To initialize your local repository using the AospExtended trees, use a 
command like this:

```bash
  repo init -u git://github.com/AospExtended/manifest.git -b 7.x
```
  
Then to sync up:
----------------

```bash
  repo sync -c -jx --force-sync
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch aosp_device_codename-userdebug
  mka aex 
```
