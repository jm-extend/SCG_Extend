# SCG_Extend
Add on specific for SCG


## Installation 
- drop the content of this repo in app/code/SCG/Extend

enable the module:
- bin/magento module:enable SCG_Extend

and run all magento commands:
- bin/magento setup:upgrade 
- bin/magento setup:di:compile 
- bin/magento setup:static-content:deploy -f -j5 
- bin/magento cache:clean
