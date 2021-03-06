REQUIREMENTS
-------------
total_control
google_analytics_reports
charts
charts_highcharts


INSTALLATION
-------------
Install this module as usual, see
https://www.drupal.org/docs/8/extending-drupal-8/installing-drupal-8-modules

and see https://www.drupal.org/node/2850463#comment-11939958

CONFIGURATION
--------------
Configure user permissions in Administer >> People >> Permissions

  * have total control
    Users in roles with the "have total control" permission will see
    the administration dashboard and all included view pages.

CUSTOMIZATION
--------------
To override the default lists on the dashboard, you have two options:

  1. Edit the settings on the panel pane:
     * Use the cog wheel at the top right of the panel display
     * (or visit Admin > Structure > Pages/Panels)
     * Configure the pane in question (via cog wheel at top right of pane)

  2. Override the default views provided with the total_control module:
     * use the cog wheel at the top right of the view display
     * (or visit Admin > Structure > Views)
