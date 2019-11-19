# research_project_summary

## Files
* [Diffs_old](https://github.com/shihualu/research_project_summary/tree/master/Diffs_old) contains commits that the owners of the forks made on the master branch, including merges from original repo. Format of filename is: *owner_of_fork*:*hash_value*.txt

* [Diffs_new](https://github.com/shihualu/research_project_summary/tree/master/Diffs_new) takes branches into consideration and removes most merges. It includes commits that the owners of the forks made on other branches or newly-created branches. It also considers the case where the owners change the name of the fork. Format of filename is: *owner_of_fork*:*fork_name*:*hash_value*

* [Samples](https://github.com/shihualu/research_project_summary/tree/master/Samples) contains malware samples provided by Google, downloaded via virustotal API

## Sensitive API Calls attempted
* getDeviceId
* getSubscriberId
* getSimSerialNumber
* getLine1Number
* abortBroadcast
* sendTextMessage
* exec
* addFlags
* getDisplayMetrics
* getDefaultDisplay
* dispatchTouchEvent
* performAction(AccessibilityNodeInfo.ACTION_CLICK)
* getLatitude
* getLongitude

## Sensitive permissions attempted
* SEND_SMS
* READ_CONTACTS
* WRITE_CONTACTS
* CALL_PHONE
* ADD_VOICEMAIL
* READ_CALENDAR
* WRITE_CALENDAR
* ACCESS_FINE_LOCATION
* ACCESS_COARSE_LOCATION
* RECORD_AUDIO

## Link to some weird commits
<https://docs.google.com/spreadsheets/d/1hSdGv0WPw3DTZ0zlsTNycfHRjOs6xfPCRcL-yTpc-j8/edit#gid=611728173>
