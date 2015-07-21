#Training Portal Readme

## Overview
This repository serves as a backup of all the portal customization code that gets updated into the training.freshdesk.com portal.

## List of files currently covered
**_Note_**: *All the html files are located in either the* **_Portal pages_** *or the* **_Portal_ _layout_** *section. The css code will be located in the* **_Stylesheet_** *section. To get to either of these sections, refer to the* **_Update_ _process_** *guidelines below.*
- The **article_view.html** file is the markup for the article pages (listed as *Article view* under the *Solutions* heading in the *Portal pages* section).
- The **article_list.html** file is the markup for the article list pages (listed as *Article list* under the *Solutions* heading in the *Portal pages* section).
- The **solution_category_home.html** file is the markup for the solution category list page (listed as *Solution category home* under the *Solutions* heading in the *Portal pages* section).
- The **training_portal.css** file contains styles common to all of the pages.

## Update process
- To update code on the training portal
  - navigate to *training.freshdesk.com/admin/home*
  - in the top nav menu select **Admin**
  - in the *Admin* page, under **General Settings** heading, click on **Helpdesk**
  - click on the black **Customize portal** button
  - in the three tabs that are available, the **Stylesheet** tab will contain the css.
  - to access the html content, select the **Layout & pages** tab and select the **Portal pages** option in this tab
  
- Once the code is updated in the portal
  - Pull the latest code from Github.
  - Copy each of the code sections (*Article view*, *Article list* etc...) into the resepective html files. Note that you have to **REPLACE the ENTIRE code** in each html file with the code from respective section in the portal. Do **NOT** update changes alone. This repo must be an exact replica of what is present in the live environment.
  - Commit and push the changes to this repo. (please add a description of the changes along with the commit).
