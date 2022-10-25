# apiprotectionstatusakamai
check the high level protections for the API hostnames which are on Akamai.(the hostnames are pulled from the API discovery tool)
You need an input.xlsx file which will have hostnames in Sheet1 as the input and also the SheetX opened in the same xlsx file for the output print.
Read the column names in SheetX as. : hostname, policy,wafcontrolsenabled,botcontrolsenabled,networklayercontrolsenabled,ratecontrolsenabled,clientreputationcontrolsenabled,slowpostcontrolsenabled,apirequestconstraintsenabled


*** THE SCRIPT HAS NOT BEEN TESTED FULLY, IF YOU SEE DISCREPANCIES, PLEASE COMMENT ***
