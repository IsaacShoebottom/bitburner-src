<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Bladeburner](./bitburner.bladeburner.md) &gt; [getActionMaxLevel](./bitburner.bladeburner.getactionmaxlevel.md)

## Bladeburner.getActionMaxLevel() method

Get the maximum level of an action.

<b>Signature:</b>

```typescript
getActionMaxLevel(type: string, name: string): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  type | string | Type of action. |
|  name | string | Name of action. Must be an exact match. |

<b>Returns:</b>

number

Maximum level of the specified action.

## Remarks

RAM cost: 4 GB

Returns the maximum level for this action.

Returns -1 if an invalid action is specified.
