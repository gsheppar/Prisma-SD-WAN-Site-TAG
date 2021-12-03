# Prisma SD-WAN Tag (Preview)
The purpose of this script is to update site tags to a set of sites from a CSV file

#### Features
 - ./get_sites.py can be used to get all sites and their current tags. You can then remove any IONs you want or update any site tags before using this 
 
 - ./apply_tag_.py can be used to update tags to a set of sites from a CSV 

#### License
MIT

#### Requirements
* Active CloudGenix Account - Please generate your API token and add it to cloudgenix_settings.py
* Python >=3.6

#### Installation:
 Scripts directory. 
 - **Github:** Download files to a local directory, manually run the scripts. 
 - pip install -r requirements.txt

### Examples of usage:
 Please generate your API token and add it to cloudgenix_settings.py
 
 - Use the get_sites.py to get a list of all sites and their tags
 1. ./get_ions.py
Will produce a csv called site_list.csv which you can sites you don't want to change or change tags for sites before using it
 
 - Use the download_code.py to pre-stage code to the IONs elements in the CSV file
 1. ./apply_tag.py -F site_list.csv
-F is the CSV file
 
### Caveats and known issues:
 - This is a PREVIEW release, hiccups to be expected. Please file issues on Github for any problems.

#### Version
| Version | Build | Changes |
| ------- | ----- | ------- |
| **1.0.0** | **b1** | Initial Release. |


#### For more info
 * Get help and additional Prisma SD-WAN Documentation at <https://docs.paloaltonetworks.com/prisma/cloudgenix-sd-wan.html>
