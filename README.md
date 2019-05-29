# The-ConfigurationPatchCreator-tool
The ConfigurationPatchCreator tool was designed to speed up the process of creating configuration files for Sitecore.


The tool extends the showconfig.aspx page with the following features:

* Patching configuration nodes using any option (Patch:Instead, Patch:Before, Patch:Attribute, Set, etc.).
    * Note: more information about patching options you can find [here](https://doc.sitecore.com/developers/90/platform-administration-and-architecture/en/configuration-patch-file-examples.html).
* Removing already patched node or a set of patched nodes by removing their parent.
* Assigning configuration roles to any patched node, nodes or their parents.
    * Note: more information about patching rules you can find [here](https://doc.sitecore.com/developers/91/platform-administration-and-architecture/en/rule-based-configuration.html).
* Preview the final configuration (showconfig) with already applied changes (do not affect current Sitecore configuration).
* Remove all patched nodes in a single click.
* Wide the list of supported browsers. 
 
The ConfigurationPatchCreator tool has been tested with the browsers:

* Google Chrome.
* Internet Explorer.
* Microsoft Edge.
* Firefox.
* Opera.
