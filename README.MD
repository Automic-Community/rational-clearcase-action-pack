## Getting Started:


###### Description
 
 Rational ClearCase is a family of computer software tools for supporting software configuration management (SCM) of source code and other software development assets, including revision control. ClearCase forms the base for configuration management for many large and medium sized businesses and can handle projects with hundreds or thousands of developers. It is developed by the Rational Software division of IBM.

###### Actions
 
1. Check-in code
2. Check-out code
3. Uncheck-out code
4. Make view
5. End view
6. Remove view
7. Start view
8. Generic cleartool call
9. Make attribute
10. Make attribute type
11. Make branch
12. Make branch type
13. Make element
14. Make label
15. Make label type
16. Mount VOB (Versioned Object Base) 
17. Unmount VOB (Versioned Object Base)
18. Set config spec
19. Move
 
###### Compatibility:
 
1. IBM ClearCase 7.1.2 


###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.
3. ITPA Shared Action Pack should be installed. 

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):
Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**

###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_CLEARCASE.PUB.DOC.xml)


###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)

###### Questions or Need Help? 

Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
