SNH Settings CategoryParentUrl
=========

Simple small Magento extension

If enabled removes all parent categories from the URL path, so that `/clothing/shoes` becomes `/shoes`. You can still manually write `/clothing/shoes`.

Install using 
```
cd /path/to/web/root
modman init
modman clone https://github.com/fullbl/snh_settings_CategoryParentUrl.git
```

Make sure to reindex the `Catalog URL Rewrites` after changing the setting under `System - Configuration - Catalog - Search Engine Optimizations - Remove Parent Category Path for Category URLs`.

Changelog
=========
1. Inital code and tested on Magento 1.8.1 (10-9-2014)
2. Move to community (and tested and working on Magento 1.9.0.1 (24-11-2014)

