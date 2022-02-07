# FragmentLibrary Version 2022.02.07
SCOM - Management Pack VSAE and Silect Fragment Library

## [Download Here][Download]

[Download]: https://github.com/thekevinholman/FragmentLibrary/archive/refs/heads/master.zip

https://kevinholman.com/2016/06/04/authoring-management-packs-the-fast-and-easy-way-using-visual-studio/

Version History:
* 2022.02.07
	* New Fragments:
		* Monitor.Process.ProcessCount.Wildcard.PowerShell.mpx
		* Monitor.TimedScript.PowerShell.FileCountInFolderThreshold.mpx
		* Class.Group.ADGroupWindowsComputersAndWatchers.mpx
* 2021.08.22
	* New Fragments:
		* Class.Group.ADGroupWindowsComputers.WithClusters.mpx
		* Monitor.Process.Performance.ConsecSamples.TwoState.mpx
		* Monitor.Performance.MultiInstance.ConsecSamples.TwoState.mpx
	* Bug Fixes and Updates:
		* Monitor.Process.mpx
* 4.8 - (08-06-2021)
	* New Fragments:
		* Recovery.Script.PowerShell.Simple.mpx
		* Recovery.Script.PowerShell.Advanced.mpx
		* Monitor.PortCheck
* 4.7 - (08-04-2021)
	* New Fragments:
		* Monitor.TimedScript.PowerShell.LocalPortCheck.mpx
		* Monitor.TimedScript.PowerShell.ParseTextFile.mpx
	* Bug Fixes and Updates:
		* Monitor.TimedScript.PowerShell.SQLQuery.mpx
* 4.6 - (06-17-2021)
	* New Fragments:
		* Monitor.TimedScript.PowerShell.FileSize.mpx
		* Monitor.TimedScript.PowerShell.UNCPathFreeSpace.mpx
	* Bug Fixes and Updates:
		* Class.And.Discovery.Script.PowerShell.FileExists.mpx
* 4.5 - (01-06-2021)
	* New Fragments:
		* Class.And.Discovery.Unix.ShellCommand.Properties.mpx
		* Class.And.Discovery.Unix.ShellCommand.mpx
		* Class.Group.Unix.Computers.mpx
		* Task.Unix.ShellCommand.mpx
		* Class.And.Discovery.WMIQuery.ChooseBaseClass.mpx
		* Class.And.Discovery.Script.PowerShell.FileExists.mpx
		* Combo.Class.Discovery.ServiceMonitor.Wildcard.WMIQuery.PSRecovery.mpx
		* Class.And.Discovery.WMIQuery.FileExists.mpx
		* Monitor.TimedScript.PowerShell.FolderLastWriteTimeOlderThanThreshold.mpx
		* Rule.TextLog.ThenScript.Alert.mpx
	* Bug Fixes and Updates:
		* Class.And.Discovery.MultiRoleHostedByParentClass.mpx
		* Rule.Performance.Collection.Perfmon.mpx
		* Rule.AlertGenerating.EventLog.TwoCorrelatedEvents.mpx
		* Class.And.Discovery.MultiRole.mpx
		* Monitor.Process.mpx
		* Class.And.Discovery.Registry.ValueExists.mpx
* 4.4 - (11-13-2019)
	* New Fragments:
		* Rule.TimedScript.DistributeFile.mpx
	* Bug Fixes and Updates:
		* Enhanced Monitor.Process.mpx to use MatchCount and enforce lower case process name
		* Enhanced Monitor.Performance.ConsecSamples.ThenScript.TwoState.mpx CPU example and fixed core count mistake
* 4.3 - (09-05-2019)
	* New Fragments:
		* Combo.Class.Discovery.ServiceMonitor.Wildcard.WMIQuery.mpx
		* Monitor.Service.WithAlert.FreqAndSamples.IgnoreDisabled.mpx
		* Monitor.Service.WithAlert.FreqAndSamples.IgnoreDisabled.PSRecovery.mpx
	* Bug Fixes and Updates:
		* Streamlined all service monitor fragments to be more consistent and understandable
		* Removed redundant service monitor fragments
* 4.2 - (08-31-2019)
	* New Fragments:
		* Class.And.Discovery.MultiRole.mpx
		* Class.And.Discovery.MultiRoleHostedByParentClass.mpx
		* Class.And.Discovery.Registry.ValueSimpleExpression.mpx
		* Class.And.Discovery.Registry.ValueRegExpression.mpx
		* Views.Alert.mpx
		* Views.State.mpx
	* Bug Fixes and Updates:
		* Multiple fragments mostly just making XML syntax more consistent with all fragments
* 4.1 - (08-25-2019)
	* Bug Fixes and Updates:
		Rule.AlertGenerating.TextLog.Fragment.mpx
		Monitor.Service.WithRecovery.WithAlertRules.mpx
* 4.0 - (07-25-2019)
	* New Fragments:
		* Class.Group.SQLQueryBasedGroupWindowsComputersAndWatchers.mpx
		* Rule.AlertGenerating.EventLog.EventIdEquals.mpx
		* Rule.AlertGenerating.EventLog.EventIdEquals.SourceEquals.DescriptionContains.mpx
		* Rule.AlertGenerating.EventLog.EventIdEquals.SourceEquals.mpx
		* Rule.AlertGenerating.EventLog.EventIdExpression.DescriptionContains.mpx
		* Rule.AlertGenerating.EventLog.EventIdExpression.mpx
		* Rule.AlertGenerating.EventLog.EventIdExpression.SourceEquals.DescriptionContains.mpx
		* Rule.AlertGenerating.EventLog.EventIdEquals.DescriptionContains.mpx
		* Rule.AlertGenerating.EventLog.EventIdExpression.SourceEquals.mpx
		* Class.And.Discovery.Script.ByServerName.mpx
	* Bug Fixes and Updates:
		* Class.And.Discovery.Script.PowerShell.Params.mpx
* 3.9 - (6-07-2019)
	* New Fragments:
		* Monitor.TimedScript.PowerShell.FileAge.mpx
		* Monitor.TimedScript.PowerShell.WithParams.mpx
		* Class.And.Discovery.Unix.CatFileProperties.mpx
	* Bug Fixes and Updates:
		* Multiple fragments - fixing displaynames, enhancing scripts
* 3.8 - (2-12-2019)
	* New Fragments:
		* Monitor.TimedScript.PowerShell.FolderFilesChanged.mpx
		* Folder.mpx
	* Bug Fixes and Updates:
		* Added UniqueID to class and discovery workflows to allow reuse in the same MP
* 3.7 - (1-27-2019)
	* New Fragments:
		* Rule.TimedScript.PowerShellDS.Filter.PowerShellWA.mpx
* 3.6 - (1-22-2019)
	* New Fragments:
		* Class.And.Discovery.Script.PowerShell.Params.mpx
* 3.5 - (12-10-2018)
	* New Fragments:
		* Class.And.Discovery.ClusteredApp.RegistrySeed.mpx
		* Combo.Class.Discovery.ClusteredApp.RegistrySeed.ComputerWatcherGroup.Views.Folder.mpx
* 3.4 - (11-20-2018)
	* New Fragments:
		* Class.Group.PowerShellWindowsComputers.mpx
		* Rule.AlertGenerating.EventLog.TwoCorrelatedEvents.mpx		
		* Combo.Class.Discovery.ServiceMonitor.Recovery.mpx
		* Combo.Class.Discovery.ServiceMonitor.Recovery.ComputerWatcherGroup.Views.Folder.mpx
	* Bug Fixes and Updates:
		* Minor fixes in displaystrings and IDs for consistency across fragments
3.3 - (10-14-2018)
	* New Fragments:
		* Folder.State.Alert.Views.mpx
		* Monitor.Service.Alert.PSRecovery.AlertRules.FreqSamples.IgnoreDisabled.mpx
	* Bug Fixes and Updates:
		* All service monitors now use UniqueID
* 3.2 - (12-11-2017)
	* New Fragments:
		* Rule.TextLog.ScriptResponse.mpx
* 3.1 - (12-11-2017)
	* New Fragments:
		* Rule.TimedScript.PowerShell.OverrideableParams.mpx
	* Bug Fixes and Updates:
		* Class.And.Discovery.Script.PowerShell.mpx
		* Class.And.Discovery.Script.VBScript.mpx
* 3.0 - (11-5-2017)
	* New fragments:
		* Class.And.Discovery.Registry.KeyExists.With.Properties.mpx
		* Class.And.Discovery.Registry.ValueExists.With.Properties.mpx
	* Bug Fixes and Updates:
		* Major update to comments section in all fragments.
		* Added ##UniqueID## to many fragments to allow for multiple reuse of the same fragment over and over in the same management pack
		* Updated several powershell script fragments to be more standardized.
* 2.6 - (10-10-2017)
	* Bug Fixes and Updates:
		* Fix timeout issues with Class.Group.ADGroupWindowsComputers.mpx and Class.Group.SQLQueryBasedGroupWindowsComputers.mpx, improved logging
		* Fixed bug in double quotes around script name in Rule.Performance.Collection.PowerShellScript.mpx
* 2.5 - (9-5-2017)
	* Bug Fixes and Updates:
		* Improved error handling and logging for Class.Group.ADGroupWindowsComputers.mpx for when a DNS name is not found for a computer object
* 2.4 - (8-26-2017)
	* New fragments:
		* Class.Group.ADGroupWindowsComputers.mpx
* 2.3 - (8-13-2017)
	* New fragments:
		Rule.AlertGenerating.TimedScript.Powershell.NoParams.mpx
		Rule.AlertGenerating.TimedScript.Powershell.WithParams.mpx
	* Bug Fixes and Updates:
		* Updated comments to streamline for reading in MP Author pro in all frags
* 2.2 - (8-13-2017)
	* New fragments:
		* Rule Rule.TimedScript.PowerShell.WithParams.mpx
	* Bug Fixes and Updates:
		* Changed Rule.TimedScript.PowerShell.mpx to Rule.TimedScript.PowerShell.NoParams.mpx
		* Updated default example script in Rule.TimedScript.PowerShell.NoParams.mpx
* 2.1 - (8-12-2017)
	* New fragments:
		* Monitor.Service.WithAlert.FreqAndSamples.mpx for service monitoring example with overrides for frequency and samples
* 2.0 - (6-5-2017)
	* Bug Fixes and Updates:
		* Updated 4 Registry Monitors to work correctly with MPAuthor
* 1.9 - (5-29-2017)
	* New fragments:
		* Monitor.RegistryValue.Content.Simple.mpx
		* Task.Agent.Command.mpx
		* Task.Agent.PowerShell.NoParams.mpx
		* Task.Agent.PowerShell.WithParams.mpx
		* Task.Agent.VBScript.mpx
		* Task.Console.mpx
	* Bug Fixes and Updates:
		* Changed comment section to a new standard format to better support Silect MP Author Pro
		* Changed Monitor.RegistryValue.Content.mpx to Monitor.RegistryValue.Content.Regex.mpx
* 1.8 - (3-22-2017)
	* New fragments:
		* Rule.AlertGenerating.SNMPTrap.AlertOnOIDandVarbind.mpx
	* Bug Fixes and Updates:
		* Minor bug fixes
		* Changed LanguagePack ENU IsDefault=true for all fragments
* 1.7 - (03-10-2017)
	* New fragments:
		* Class.And.Discovery.Unix.FileExists.mpx
		* Monitor.Unix.ShellCommand.mpx
	* Bug Fixes and Updates:
		* Minor bug fixes
* 1.6 - (03-05-2017)
	* New fragments:
		* Monitor.Performance.ConsecSamples.ThenScript.TwoState.mpx
		* Rule.TimedScript.PowerShell.mpx
	* Bug Fixes and Updates:
		* New format for comment section to support MPAuthor Pro
		* Bug fixes and comments added to all Fragments
		* Removed default language setting in LanguagePacks section
* 1.5 - (01-30-2017)
	* New fragments:
		* Class.And.Discovery.WMIQuery.mpx
		* Rule.AlertGenerating.TextLog.Fragment.mpx
		* Monitor.Service.WithAlert.IgnoreDisabled.mpx
		* Monitor.TimedScript.PowerShell.SQLQuery.mpx
	* Bug Fixes and Updates:
		* Minor bug fixes
* 1.4 - (11-20-2016)
      	* New fragments:
		* Monitor.Process.mpx
		* Class.And.Discovery.Script.PowerShell.mpx
		* Class.And.Discovery.Script.VBScript.mpx
	* Bug Fixes and Updates:
		* Renamed/Shortended all Fragment names
      		* Updated the Empty Fragment to have structure examples for proper ordering
      		* Fixed Powershell script monitor bugs 
* 1.3 - (08-15-2016)
	* Bug Fixes and Updates:
		* Generic.Monitor.RegistryValue.Content.Fragment.mpx
		* Generic.Monitor.Service.WithRecovery.WithAlertRules.Fragment.mpx
* 1.2 - (08-07-2016)
	* New Fragments:
		* Generic.Monitor.RegistryKey.Exists.Fragment.mpx
		* Generic.Monitor.RegistryValue.Exists.Fragment.mpx
		* Generic.Monitor.RegistryValue.Content.Fragment.mpx
		* Generic.Class.And.Discovery.SNMP.Device.byOID.Fragment.mpx
		* Generic.Monitor.SNMP.Poll.OIDValue.Integer.Performance.Fragment.mpx
		* Generic.Rule.AlertGenerating.SNMPTrap.AlertOnOID.Fragment.mpx
		* Generic.Class.Group.ClassInstances.WithRollup.Fragment.mpx
* 1.1 - (06-04-2016)
	* Major updates, added comments, new frags, bug fixes
* 1.0 - (05-29-2016)
	* Original release
