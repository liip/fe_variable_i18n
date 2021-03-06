FE_VARIABLE_I18N
================

A Drupal 7 module to make i18n variables featurable.
More on why and how to use Drupal Features module: [here](https://fosswiki.liip.ch/display/DRUPAL/Drupal+7+using+the+features+module)

This module is closely related to the [fe_variable module](https://github.com/liip/fe_variable).

Dependencies
------------------
 * [Features module](http://drupal.org/project/features)
 * [Internationalization](http://drupal.org/project/i18n)
 * [Variable](http://drupal.org/project/variable)

Why not use Strongarm?
------------------

We experienced quite a few problems with Strongarm, specially when combined with i18n. Strongarm is way more powerful and tries to be much smarter than this module in that it creates strongarm variables to override core variables. This module just let you export and import variables.
