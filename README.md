# Task Sort
## Description

This plugin allows a user to retrieve a list of sorted tasks.

## Endpoint
*/task/sort/\*

## Http Request Method
*GET\*

## Parameters
 this request type has no parameters
 
 ## Responses
 Successful Operation
- Status Code: 200.

 Not Found
- Status Code: 400



# Cancel Recurring Task
## Description

This Plugin allows a user to cancel recurring tasks by setting them to null.

## Endpoint
*/cancel_recurringTask/\*

## Http Request Method
*PUT\*

## Parameters
| Name | Data Type | Description |
| ---- | --------- | ----------- |
| _id  | int64     | the current task id to cancel |
 
 ## Responses
 Successful Operation
- Status Code: 200.

 Not Found
- Status Code: 400
