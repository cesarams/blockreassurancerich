# PrestaShop blockreassurancerich
### Customer reassurance, with rich text
Same as original *blockreassurnace* by PrestaShop, but supports rich text, allowing the formatting of reassurence items, with links and stuff. *Attention: you should disable or uninstall the orignal blockreassurance module as this module replaces it.*

**Based on blockreassurance 3.0.1 for Prestashop 1.7**

**Instructions**
* Disable/uninstall original blockreassurance module (I would recommend to uninstall it)
* Install blockreassurancerich as usual
* Configure reassurance items like usual, while making use of the rich text editor to add links and stuff *(for design consistency, I would personally refrain from adding anything else but links, but you can go nuts if you want)*
* Clear cache if you can't see the changes in the FO

**One more thing:** the original blockreassurance module is hooked in the theme.yml file (themes/classic/config/theme.yml), meaning that if you upgrade Prestashop and you use the Classic theme, the original module will be reenabled after upgrade or if you switch themes. If you don't upgrade the theme, you can just replace "blockreassurance" with "blockreassurancerich" in theme.yml.
