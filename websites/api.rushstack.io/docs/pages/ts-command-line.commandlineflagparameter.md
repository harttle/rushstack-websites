---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [CommandLineFlagParameter](./ts-command-line.commandlineflagparameter.md)

## CommandLineFlagParameter class

The data type returned by [CommandLineParameterProvider.defineFlagParameter()](./ts-command-line.commandlineparameterprovider.defineflagparameter.md) .

<b>Signature:</b>

```typescript
export declare class CommandLineFlagParameter extends CommandLineParameter
```

<b>Extends:</b> [CommandLineParameter](./ts-command-line.commandlineparameter.md)

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `CommandLineFlagParameter` class.

## Properties

| Property                                                     | Modifiers | Type                                                                      | Description                                                                          |
| ------------------------------------------------------------ | --------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| [kind](./ts-command-line.commandlineflagparameter.kind.md)   |           | [CommandLineParameterKind](./ts-command-line.commandlineparameterkind.md) | Indicates the type of parameter.                                                     |
| [value](./ts-command-line.commandlineflagparameter.value.md) |           | boolean                                                                   | Returns a boolean indicating whether the parameter was included in the command line. |

## Methods

| Method                                                                                    | Modifiers | Description                                            |
| ----------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------ |
| [appendToArgList(argList)](./ts-command-line.commandlineflagparameter.appendtoarglist.md) |           | Append the parsed values to the provided string array. |