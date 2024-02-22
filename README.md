# IBM Storage CLI Support README

IBM Storage CLI Support contains what I consider to be the most important CLI commands for dealing with IBM Storage. 
I created the collection to make my life easier when creating scripts with [PowerShell][] for [Visual Studio Code][].
I currently use [PowerShell][] Version 7.4.x for this purpose.
The easiest and better way is to download the extensions directly in the VS code under Extensions, 
as this is the quickest way to get the latest version without having to do anything.

All commands that you find here correspond to the commands that you find in the IBM documentation here e.g. for the [IBM SAN Volume Controller][]. 
Not all options for all commands are available here, but the most common ones should be available, at least the ones I deal with most of the time.
If you miss something please feel free and contact me.

## Categorization List
| Categorization            | Subcategory                          | Content                                                                    |
| ------------------------- | ------------------------------------ | -------------------------------------------------------------------------- |
| ibm_usefull_thing         | firmware_install_cli                 | A step by step guide on how to update the firmware via CLI                 |
| ibm_usefull_thing         | drivefirmware_install_cli            | A step by step guide on how to update the drive firmware via CLI           |
| ibm_usefull_thing         | backup_system_configuration_cli      | One way to Backing up the system configuration                             |
| ibm_usefull_thing         | setup_basic_system_configuration     | One way to setup up a new system configuration for IBM Storage             |
| ibm_usefull_thing         | setup_user_configuration             | One way to setup or modify up a new user on IBM Storage                    |
| ibm_usefull_thing         | setup_basic_system_configuration     | One way to setup up a new system configuration for IBM Storage             |
| ibm_usefull_thing         | setup_encryption_configuration       | One way to setup up a new encryption configuration for storage             |
| ---------------------     | ------------------------------------ | -------------------------------------------------------------------------- |
| ibm_array                 |                                      | A step by step guide on how to update the firmware via CLI                 |
| ibm_log                   |                                      | The audit log commands to track command specifications and related data.   |
| ibm_svcconfig             |                                      | Backup and restore commands                                                |
| ibm_cluster_mgmt          |                                      | Use the system commands to monitor and modify systems and their properties.|
| ibm_cluster_service       |                                      | Clustered system diagnostic and service-aid commands                       |
| ibm_copy_service          |                                      | Copy Service commands                                                      |
| ibm_drive_service         |                                      | Drive commands to capture information to assist with managing drives.      |
| ibm_enclosure_mgmt        |                                      | Enclosure commands to manage enclosures and their properties.              |
| ibm_callhome              |                                      | Email and event notification commands                                      |
| ibm_security              |                                      | Security commands are used to create, change, or list system               |
| ibm_encryption            |                                      | Encryption commands are used to create, change, or list system             |
| ibm_fc_portset            |                                      | Set of commands to associate a Fibre Channel I/O port ID with portset      |
| ibm_flashcopy             |                                      | FlashCopy commands to work with FlashCopy                                  |
| ibm_hostcluster           |                                      | Hostcluster commands to work with Hostcluster objects on your system       |
| ibm_host                  |                                      | Host commands to work with host objects on your system                     |
| ibm_license               |                                      | Licensing and featurization commands to work with licensed system functions|
| ibm_livedump              |                                      | Livedump commands                                                          |
| ibm_mdisk                 |                                      | Managed disk commands to work with managed disk options on your system     |
| ibm_migrate               |                                      | Migration commands to work with migration options for the system.          |
| ibm_multifactor           |                                      | Configure system-wide IBM Security Verify and Duo Security multifactor     |
| ibm_ethernet              |                                      | Configure or create portset, IP objects and associate them with hosts      |
| ibm_provisioning_policies |                                      | Commands to simplify the provisioning of storage                           |
| ibm_safeguarded           |                                      | Simplify the copies that are made on IBM Copy Services Manager             |
| ibm_service               |                                      | Service information commands                                               |
| ibm_servicetask           |                                      | Service task commands                                                      |
| ibm_snapshot              |                                      | Snapshot commands                                                          |
| ibm_snapshotpolicy        |                                      | Commands to set a schedule for snapshot creation and retention             |
| ibm_storageinsights       |                                      | Commands to monitor and optimize the storage resources in the system       |
| ibm_pool                  |                                      | Storage pool commands to work with storage pool options on the system      |
| ibm_twoperson             |                                      | Two person integrity commands                                              |
| ibm_user_mgmt             |                                      | User management and access control commands                                |
| ibm_vdisk_mgmt            |                                      | Volume commands to work with volume options for the system                 |
| ibm_system_certifi        |                                      | System certificates commands                                               |
| ibm_policy_based          |                                      | Policy-based replication commands                                          |

...more are still in the pipeline

## What comes next
* more useful sinippets
* more useful Subcategories
* better integration in VSCode, if possible
* integrated Powershell functions for direct use.

## Requirements

Use [Visual Studio Code][] with recommendation in connection with the current [PowerShell][] module.

It also works in combination with my [FabricOS-Support][] Snippet


## Known Issues

* Some prefixes are hard to find
* Some tab stops do not work as desired
* Some explanations are not clear enough


## Release Notes

See [changelog](CHANGELOG.md) for all changes and releases.

## Important for use
If you are not sure about the effects of individual commands, please read the official [IBM documentation][] for your product before using it. 
I will not accept any liability for damage or loss of data.



## Working with Markdown

Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**

[FabricOS-Support]: https://github.com/DocCLF/FabricOS-Support
[PowerShell]: https://github.com/PowerShell/PowerShell
[Visual Studio Code]: https://github.com/Microsoft/vscode
[IBM SAN Volume Controller]: https://www.ibm.com/docs/en/sanvolumecontroller
[IBM documentation]: https://www.ibm.com/docs/en/