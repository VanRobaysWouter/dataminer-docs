---
uid: GetEditParameter
---

# GetEditParameter

Use this method to retrieve all the information necessary to be able to present users with a control that allows them to update a specific parameter.

## Input

| Item        | Format  | Description                                          |
|-------------|---------|------------------------------------------------------|
| connection  | String  | The connection ID. See [ConnectApp](xref:ConnectApp). |
| dmaID       | Integer | The DataMiner Agent ID.                              |
| elementID   | Integer | The element ID.                                      |
| parameterID | Integer | The parameter ID.                                    |

## Output

| Item                   | Format                                    | Description                                |
|------------------------|-------------------------------------------|--------------------------------------------|
| GetEditParameterResult | [DMAParameterEdit](xref:DMAParameterEdit) | The properties of the specified parameter. |
