# docker-joomla

## Joomla setup 
Please note this is for a dev setup, not production.
On first login you will need to add passwords to the setup - the docker-compose.yaml contains the username/password that you can use.
Database setup should be as per image:
![Image]{./database-config.png}

## T4 Framework setup
Go to 2. Manual Installation (files are in repo root)
https://www.joomlart.com/documentation/t4-framework/installation-instructions

### Step 1: install T4 framework plugin
From your back-end setting panel, go to: ``Extensions → Extension Manager``, browse T4 plugin installation file then hit the ``Upload and Install``
Now, drag and drop the T4 System plugin (t4-system-plugin_2.2.1.zip) to install.

### Step 2 Install T4 Blank BS5 (Bootstrap 5) or T4 Blank (Bootstrap 4) template.
In the same window, drag and drop the T4 blank template installation package (tpl_t4_bs5_blank_1.1.6.zip) to install.
Now, go to ``System > Site Template Styles`` and set the T4 Blank template as your website default template style.
Click on Filter options, and then Default icon
