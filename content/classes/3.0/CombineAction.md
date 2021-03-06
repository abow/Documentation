---
ID_PAGE: 25159
PG_TITLE: CombineAction
PG_VERSION: 2.1
TAGS:
    - Action
---
## Description

class [CombineAction](/classes/3.0/CombineAction) extends [Action](/classes/3.0/Action)



## Constructor

## new [CombineAction](/classes/3.0/CombineAction)(triggerOptions, children, condition)

This action is a container. You can use it to execute many actions simultaneously on the same trigger. The children property must be an array of actions

#### Parameters
 | Name | Type | Description
---|---|---|---
 | triggerOptions | any |      The trigger options
 | children | [Action](/classes/3.0/Action)[] |      The childrens actions
optional | condition | [Condition](/classes/3.0/Condition) |      The condition to do the action
## Members

### children : [Action](/classes/3.0/Action)[]

The childrens actions

## Methods

### execute(evt) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | evt | [ActionEvent](/classes/3.0/ActionEvent) |      The event to trigger

### serialize(parent) &rarr; any



#### Parameters
 | Name | Type | Description
---|---|---|---
 | parent | any |   

