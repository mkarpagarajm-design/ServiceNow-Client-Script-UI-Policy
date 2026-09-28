# Project Testing

Project: Implement Client Script & UI Policy (Incident)

## Test Case 1: High Impact Validation

An Incident was tested with Impact set to High while the required Assigned To information was not provided.

Expected Result:
The Incident should not be submitted and the validation message should be displayed.

Result:
The validation behavior worked as expected.

## Test Case 2: Valid Incident Submission

The required information was provided for a High Impact Incident.

Expected Result:
The Incident should be submitted successfully.

Result:
The Incident was saved successfully.

## Test Case 3: Condition Reversal

The Impact value was changed from High to Medium.

Expected Result:
The High Impact restrictions should be removed and the affected fields should return to their normal behavior.

Result:
The reverse condition worked as expected.

## Test Case 4: List State Editing

An attempt was made to modify the State directly from the Incident list.

Expected Result:
The edit should be blocked with an alert message.

Result:
The list-edit restriction worked successfully.

## Test Case 5: Form-Based State Update

The State was modified from within the Incident form.

Expected Result:
The update should be permitted.

Result:
The State update was saved successfully.

## Overall Testing Result

The configured controls and validation rules were tested successfully under the required conditions.
