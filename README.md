# :bowtie:meet-my-old-friends
Build my personal website in Drupal 9 to show my strength in Drupal, hosting it on Pantheon.
https://dev-meet-my-old-friends.pantheonsite.io/. Steps see below. 

### 1. Sign up a free account at Pantheon 
https://pantheon.io/register They offer you: 2 free sandbox sites; Git-Based Dev, Test, And Live Environments; Free HTTPS (SSL) Certificates; Integrated Content Delivery Network (CDN)

### 2. Create a Sandbox site on Pantheon
https://pantheon.io/docs/guides/quickstart/create-new-site/ When done, you should see your site like this: 
<img src="./images/creat_a_new_site.png" alt="create a sandbox site on Pantheon" width="750" /> 

### 3. Deploy Drupal 9
<img src="./images/install_drupal_9.png" alt="install drupal 9" width="750" /> 

### 4. Generate SSH keys in your terminal and add it to Pantheon
https://pantheon.io/docs/ssh-keys

### 5. Git clone the repo from Pantheon to your local machine 
When done, the repo structure will look like this

<img src="./images/git_clone_repo_to_your_local.png" alt="git clone repo to your local machine" width="750" />

### 6. Say goodbye to one of your old friends - Acquia Dev Desktop 

Acquia has stopped support for Dev Desktop on June 30, 2021. Completely uninstall it in your local machine. 
https://www.revouninstaller.com/preview-log/?pid=2469&pname=Acquia+Dev+Desktop

### 7. Install Composer 2 globally 
https://getcomposer.org/download/

### 8. Install Drupal theme which suits your need
I pick dxpr at this moment as I expect it is scalable https://www.drupal.org/project/dxpr_theme

Run the following command line in your terminal:
```
composer require drupal/dxpr_theme
```




