# Google Tag Manager API
The repository contains python scripts related to [Google Tag Manager API](https://developers.google.com/tag-platform/tag-manager/api/v2).

## Files

get_gtm_data.py - use this file if you have too many GTM containers in account. There are several variables you need to fill in the code:

* path_to_config - path to the local .json file with the [Google credentials](https://github.com/googleapis/google-api-python-client/blob/main/docs/start.md).
* account_id - GTM account id which you can find in GTM UI under account settings.
* path_to_log_file - path to the local .log file.
* path_to_result_json - path to the local .json file which will contain the result data.

## Dependensies

[google-api-python-client library](https://github.com/googleapis/google-api-python-client).
