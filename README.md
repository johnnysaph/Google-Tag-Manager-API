# Google Tag Manager API Scripts
The repository contains python scripts related to [Google Tag Manager API](https://developers.google.com/tag-platform/tag-manager/api/v2).
These scripts are helpfull if you have GTM account with multiple containers in it.

## Files

**get_gtm_data.py** - use this code if you have too many GTM containers in your account. There are several variables you need to fill in the code:

* path_to_config - path to the local .json file with the [Google credentials](https://github.com/googleapis/google-api-python-client/blob/main/docs/start.md).
* account_id - GTM account id which you can find in GTM UI under account settings.
* path_to_log_file - path to the local .log file.
* path_to_result_json - path to the local .json file which will contain the result data.

pause_tags_from_file - use this code if you have too many GTM containers in your account and you need to pause several tags in different containers. It is assumed that you already have an excel file with the tags you need to pause. There are several variables you need to fill in the code:

* path_to_config - path to the local .json file with the [Google credentials](https://github.com/googleapis/google-api-python-client/blob/main/docs/start.md).
* account_id - GTM account id which you can find in GTM UI under account settings.
* path_to_log_file - path to the local .log file.
* path_to_file_with_tags - path to the local excel file with tags you want to pause. It is necessary to have at least two atrributes for each tag in file: container id and tag's name.

## Dependensies

[google-api-python-client library](https://github.com/googleapis/google-api-python-client).
