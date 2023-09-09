# Testing site: http://itcareer.pythonanywhere.com/
## Tests:
|ID|Title|Instruction|ER|
|:--|:--|:--|:--|
|1|Name required field| Left [Name] field empty. Push submit.| Error message required field is empty|
|2|E-mail required field| Left [Email] field empty. Push submit.| Error message required field is empty|
|3|Password required field| Left [Password] field empty. Push submit.| Error message required field is empty|
|4| Name valid input length|type 30 letters|No error message|
|5| Name valid input length|type 4 letters|No error message|
|6| Name valid input length|type 64 letters|No error message|
|7| Name invalid input length|type 3 letters|Error message: name must be at least 4 characters||
|8| Name invalid input length|type 65 letters|Error message|
|9| Name valid input case|type Masha|No error message|
|10| Name valid input sp.ch.|type Masha D|No error message|
|11| Name valid input sp.ch.|type Masha-D|No error message|
|12| Name valid input sp.ch.|type Masha'D|No error message|
|13| Name invalid input sp.ch.|type Masha%|Error message|
|14| Name invalid input sp.ch.|type Masha♣|Error message|
|15| Name valid input paste|paste Masha'D|No error message|
|16| Name invalid input space before Name|type  MashaD|Error message|
|17| Name invalid input space after Name|type Masha D |Error message|
|18| Name invalid input sp.ch.|type Masha--D |Error message|
|17| Name invalid input space after Name|type Masha D |Error message|
|18| Name valid input placeholder|left field empty|Placeholder title displayed|
