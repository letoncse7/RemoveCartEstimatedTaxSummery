-- This extension for remove Estimated Tax Summery from Cart Details page

Installation Steps

Please follow these steps to install -

Step 1: Download module from https://github.com/letoncse7/RemoveCartEstimatedTaxSummery.git

Step 2: Log in to your server using FTP or Cpanel.

Step 3: Upload Fastbazzar inside of app/code dirrectory.

Step 4: Now Run the command line and go to your project root directory.

Step 5: Run The following command into command line: -

5.1: php bin/magento setup:upgrade
5.2: php bin/magento setup:di:compile
5.2: php bin/magento setup:static-content:deploy -f
5.3: php bin/magento cache:clean
5.4: php bin/magento cache:flush
5.5: php bin/magento index:reindex