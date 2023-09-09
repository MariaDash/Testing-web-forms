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
|14| Name invalid input emoji|Type Masha♣. Push submit.|Error message|
|15| Name valid input paste|Paste Masha'D. Push submit.|No error message|
|16| Name invalid input space before Name. Push submit.|Type  MashaD|Error message|
|17| Name invalid input space after Name. Push submit.|Type Masha D |Error message|
|18| Name invalid input sp.ch.|Type Masha--D. Push submit. |Error message|
|19| Name valid input placeholder|Left field empty. Push submit.|Placeholder title displayed. No sp.ch. at the end|
|20| Name invalid input language|Type Маша. Push submit.|Error message|
|21| Name invalid input |Left empty. Push submit.|Error message with red background|
|22|Navigation with Tab button|Click on the field. Push Tab|Moving mouse pointer to next line down|
|23|Navigation with Shift+Tab buttons|Click on the field. Push Shift+Tab combination|Moving mouse pointer to the line up|
|24| Surname valid input length|Left field empty Push submit.|No error message|
|25| Surname valid input length|Type 30 letters. Push submit.|No error message|
|26| Surname valid input length|Type 64 letters. Push submit.|No error message|
|27| Surname invalid input length|Type 65 letters. Push submit.|Error message|
|28| Surname valid input case|Type Dash. Push submit.|No error message|
|29| Surname valid input sp.ch.|Type Dash Dash. Push submit.|No error message|
|30| Surname valid input sp.ch.|Type Dash-Shell. Push submit.|No error message|
|31| Surname valid input sp.ch.|Type O'Hara. Push submit.|No error message|
|32| Surname invalid input sp.ch.|Type Dash%. Push submit.|Error message|
|33| Surname invalid input emoji|Type Dash♣. Push submit.|Error message|
|34| Surname valid input paste|Paste O'Hara. Push submit.|No error message|
|35| Surname valid input 2 sp.ch.|Type O'Hara-Butler. Push submit.|No error message|
|36| Surname invalid input space before Surname. Push submit.|Type  Dash|Error message|
|37| Surname invalid input space after Surname. Push submit.|Type Dash |Error message|
|39| Surname invalid input sp.ch.|Type Dash--Deen. Push submit. |Error message|
|40| Surname valid input placeholder|Left field empty. Push submit.|Placeholder title displayed. No sp.ch. at the end|
|41| Surname invalid input language|Type Дашкова. Push submit.|Error message|
|42| Surname invalid input |Left empty. Push submit.|Error message with red background|
