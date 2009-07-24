# BBEdit WordPress Clippings

This is a Clipping bundle for BBEdit 9+ to help make working with WordPress (hopefully) a lot easier. These clippings will be maintained for the current version of WordPress. No conscious effort will be maintained to provide backward compatibility.

## Functions

Clippings are provided for all functions present in the WordPress standard distribution. No attempt is made at intelligent sorting nor is there a distinction at this time between regular functions and class methods. I think a Javascript function even crept in there somewhere. 

## Actions and Filters

Clippings are also provided for all the Actions and Filters contained within WordPress. The Action and Filter names for selection are formatted as `add_action-action_name` and `add_filter-filter_name`. For those Actions and Filters that pass through more than 1 parameter the number of parameters will part of the function completion. If there is only one parameter as part of the Action or Filter then the parameters parameter is left off.

## Carrington Functions

If you're doing hard-core Carrington development these extra function helpers should come in handy.

## Installation

Copy the WordPress.php folder in to your `~/Library/Application Support/BBEdit/Clippings` folder and restart BBEdit.

## Bugs and Suggestions

Should be submitted to: http://github.com/Gipetto/BBEdit-WordPress-Clippings/issues