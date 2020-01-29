![MIKES DATA WORK GIT REPO](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_01.png "Mikes Data Work")        

# How To Modify Windows Pagefile On Servers
**Post Date: June 17, 2015**        



## Contents    
- [About Process](##About-Process)  
- [Build Info](#Build-Info)  
- [Author](#Author)  
- [License](#License)       

## About-Process

<p>Sometimes you'll need to clear some space from the OS drive on the Server. One of which is constant, but doesn't have to be that way; is the paging file. Yeah; sure… the page file has a purpose, but it doesn't have to consume more than 10 – 20GB of space. Here's how to modify it.

Go to Start --> Run: systempropertiesadvanced
1. Click 'Advanced'
2. Click 'Settings'
3. Click 'Advanced'
4. Click 'Change'
5. Uncheck the option for 'Automatically manage paging file size for all drives'. (In this case we only have one drive anyway)
6. Select 'Custom size', and make the setting about 10GB ( Type in 10240 )
In order for the change to take affect; a reboot is needed.</p>

![Modify Windows Paging File]( https://mikesdatawork.files.wordpress.com/2015/06/image0013.jpg "Start Run SystemPropertiesAdvanced")
 


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

[![Gist](https://img.shields.io/badge/Gist-MikesDataWork-<COLOR>.svg)](https://gist.github.com/mikesdatawork)
[![Twitter](https://img.shields.io/badge/Twitter-MikesDataWork-<COLOR>.svg)](https://twitter.com/mikesdatawork)
[![Wordpress](https://img.shields.io/badge/Wordpress-MikesDataWork-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)
  
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Mikes Data Work](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_02.png "Mikes Data Work")

