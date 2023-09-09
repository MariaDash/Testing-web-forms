# Testing site: http://itcareer.pythonanywhere.com/
## Tests:
|ID|Title|Instruction|ER|
|:--|:--|:--|:--|
|1|Name required field| Left [Name] field empty. Push submit.| Error message required field is empty|
|2|E-mail required field| Left [Email] field empty. Push submit.| Error message required field is empty|
|3|Password required field| Left [Password] field empty. Push submit.| Error message required field is empty|
|4| Name valid input length|Type 30 letters. Push submit.|No error message|
|5| Name valid input length|Type 4 letters. Push submit.|No error message|
|6| Name valid input length|Type 64 letters. Push submit.|No error message|
|7| Name invalid input length|Type 3 letters. Push submit.|Error message: name must be at least 4 characters||
|8| Name invalid input length|Type 65 letters. Push submit.|Error message|
|9| Name valid input case|Type Masha. Push submit.|No error message|
|10| Name valid input sp.ch.|Type Masha D. Push submit.|No error message|
|11| Name valid input sp.ch.|Type Masha-D. Push submit.|No error message|
|12| Name valid input sp.ch.|Type Masha'D. Push submit.|No error message|
|13| Name invalid input sp.ch.|Type Masha%. Push submit.|Error message|
|14| Name invalid input sp.ch.|Type Masha♣. Push submit.|Error message|
|15| Name valid input paste|Paste Masha'D. Push submit.|No error message|
|16| Name invalid input space before Name. Push submit.|Type  MashaD|Error message|
|17| Name invalid input space after Name. Push submit.|Type Masha D |Error message|
|18| Name invalid input sp.ch.|type Masha--D. Push submit. |Error message|
|19| Name invalid input space after Name. Push submit.|Type Masha D |Error message|
|20| Name valid input placeholder|left field empty. Push submit.|Placeholder title displayed. No sp.ch. at the end|
|21| Name invalid input language|Type Маша. Push submit.|Error message|
|21| Name invalid input |Left empty. Push submit.|Error message with red background|
