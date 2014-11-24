SNH Settings CategoryParentUrl
=========

Simple small Magento extension

If enabled removes all parent categories from the URL path, so that `/clothing/shoes` becomes `/shoes`.

Install using 
```
cd /path/to/web/root
modman init
modman clone https://github.com/seansan/snh_settings_CategoryParentUrl.git
```

Make sure to reindex the `Catalog URL Rewrites` after changing the setting under `System - Configuration - Catalog - Search Engine Optimizations - Remove Parent Category Path for Category URLs`.

Changelog
=========
1. Inital code and tested on Magento 1.8.1 (10-9-2014)

