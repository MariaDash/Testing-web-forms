# Testing site: http://itcareer.pythonanywhere.com/
## Tests:
|ID|Title|Instruction|ER|
|:--|:--|:--|:--|
|1|[Name] required field| Left [Name] field empty. Push [Submit] button.| Error message required field is empty|
|2|[Email] required field| Left [[Email] field] field empty. Push [Submit] button.| Error message required field is empty|
|3|[Password] required field| Left [Password] field empty. Push [Submit] button.| Error message required field is empty|
|4| [Name] field valid input length|Type 30 letters. Push [Submit] button.|No error message|
|5| [Name] field valid input length|Type 4 letters. Push [Submit] button.|No error message|
|6| [Name] field valid input length|Type 64 letters. Push [Submit] button.|No error message|
|7| [Name] field invalid input length|Type 3 letters. Push [Submit] button.|Error message: name must be at least 4 characters|
|8| [Name] field invalid input length|Type 65 letters. Push [Submit] button.|Error message|
|9| [Name] field valid input case|Type 'Masha'. Push [Submit] button.|No error message|
|10| [Name] field valid input sp.ch.|Type 'Masha D'. Push [Submit] button.|No error message|
|11| [Name] field valid input sp.ch.|Type 'Masha-D'. Push [Submit] button.|No error message|
|12| [Name] field valid input sp.ch.|Type 'Masha'D'. Push [Submit] button.|No error message|
|13| [Name] field invalid input sp.ch.|Type 'Masha%'. Push [Submit] button.|Error message|
|14| [Name] field invalid input emoji|Type 'Masha♣'. Push [Submit] button.|Error message|
|15| [Name] field valid input paste|Paste 'Masha'D'. Push [Submit] button.|No error message|
|16| [Name] field invalid input space before [Name] field.| Type ' MashaD'. Push [Submit] button.|Error message|
|17| [Name] field invalid input space after [Name] field. |Type 'MashaD '. Push [Submit] button.|Error message|
|18| [Name] field invalid input sp.ch.|Type 'Masha--D'. Push [Submit] button. |Error message|
|19| [Name] field valid input placeholder|Left field empty. Push [Submit] button.|Placeholder title displayed. No sp.ch. at the end|
|20| [Name] field invalid input language|Type 'Masшa'. Push [Submit] button.|Error message|
|21| [Name] field invalid input |Left empty. Push [Submit] button.|Error message with red background|
|22|Navigation with Tab button|Click on the field. Push Tab|Moving mouse pointer to next line down|
|23|Navigation with Shift+Tab buttons|Click on the field. Push Shift+Tab combination|Moving mouse pointer to the line up|
|24| [Surname] field valid input length|Left field empty Push [Submit] button.|No error message|
|25| [Surname] field valid input length|Type 30 letters. Push [Submit] button.|No error message|
|26| [Surname] field valid input length|Type 64 letters. Push [Submit] button.|No error message|
|27| [Surname] field invalid input length|Type 65 letters. Push [Submit] button.|Error message|
|28| [Surname] field valid input case|Type 'Dash'. Push [Submit] button.|No error message|
|29| [Surname] field valid input sp.ch.|Type 'Dash Dash'. Push [Submit] button.|No error message|
|30| [Surname] field valid input sp.ch.|Type 'Dash-Shell'. Push [Submit] button.|No error message|
|31| [Surname] field valid input sp.ch.|Type 'O'Hara'. Push [Submit] button.|No error message|
|32| [Surname] field invalid input sp.ch.|Type 'Dash%'. Push [Submit] button.|Error message|
|33| [Surname] field invalid input emoji|Type 'Dash♣'. Push [Submit] button.|Error message|
|34| [Surname] field valid input paste|Paste 'O'Hara'. Push [Submit] button.|No error message|
|35| [Surname] field valid input 2 sp.ch.|Type 'O'Hara-Butle'r. Push [Submit] button.|No error message|
|36| [Surname] field invalid input space before [Surname] field. Push [Submit] button.|Type  Dash|Error message|
|37| [Surname] field invalid input space after [Surname] field. Push [Submit] button.|Type Dash |Error message|
|38| [Surname] field invalid input sp.ch.|Type 'Dash--Deen'. Push [Submit] button. |Error message|
|39| [Surname] field valid input placeholder|Left field empty. Push [Submit] button.|Placeholder title displayed. No sp.ch. at the end|
|40| [Surname] field invalid input language|Type 'Дashkova'. Push [Submit] button.|Error message|
|41| [Surname] field invalid input |Left empty. Push [Submit] button.|Error message with red background|
|42| [Email] field valid input before @ |Type 'catycatycatycaty@gmail.com'. Push [Submit] button.|No error message|
|43| [Email] field valid input before @ |Type 'caty@gmail.com'. Push [Submit] button.|No error message|
|44| [Email] field valid input before @ |Type 'catycatycatycatycatycatycatycaty@gmail.com'. Push [Submit] button.|No error message|
|45| [Email] field invalid input before @ |Type 'cat@gmail.com'. Push [Submit] button.|Error message|
|46| [Email] field invalid input before @ |Type 'catycatycatycatycatycatycatycatyc@gmail.com'. Push [Submit] button.|Error message|
|47| [Email] field valid input after @ before dot |Type 'catycatycatycaty@gmailgmailgmailgmail.com'. Push [Submit] button.|No error message|
|48| [Email] field valid input after @ before dot |Type 'catycatycatycaty@mail.com'. Push [Submit] button.|No error message|
|49| [Email] field valid input after @ before dot |Type 'catycatycatycaty@gmailgmailgmailgmailgmailgmailgm.com'. Push [Submit] button.|No error message|
|50| [Email] field invalid input after @ before dot|Type 'catycatycatycaty@gma.com'. Push [Submit] button.|Error message|
|51| [Email] field invalid input after @ before dot |Type 'catycatycatycaty@gmailgmailgmailgmailgmailgmailgma.com'. Push [Submit] button.|Error message|
|52| [Email] field valid input from dot to end |Type 'catycatycatycaty@gmailgmail.com'. Push [Submit] button.|No error message|
|53| [Email] field valid input from dot to end |Type 'catycatycatycaty@gmail.co'. Push [Submit] button.|No error message|
|54| [Email] field valid input from dot to end |Type 'catycatycatycaty@gmailgmailgmailgmailgmailgmailgm.comcomcomcomcoma'. Push [Submit] button.|No error message|
|55| [Email] field invalid input from dot to end|Type 'catycatycatycaty@gma.c'. Push [Submit] button.|Error message|
|56| [Email] field invalid input from dot to end |Type 'catycatycatycaty@gmailgmailgmailgmailgmailgmailgma.comcomcomcomcomaa'. Push [Submit] button.|Error message|
|57| [Email] field valid input max number of ch. |Type 'catycatycatycatycatycatycatycaty@gmailgmailgmailgmailgmailgmailgm.comcomcomcomcoma'. Push [Submit] button.|No error message|
|58| [Email] field valid input before @ + sp.ch. |Type 'caty.catycatycaty@gmail.com'. Push [Submit] button.|No error message|
|59| [Email] field valid input before @ + sp.ch. |Type 'caty-catycatycaty@gmail.com'. Push [Submit] button.|No error message|
|60| [Email] field valid input before @ + sp.ch. |Type 'caty_catycatycaty@gmail.com'. Push [Submit] button.|No error message|
|61| [Email] field valid input before @ + sp.ch. |Type 'catycaty7catycaty@gmail.com'. Push [Submit] button.|No error message|
|62| [Email] field invalid input before @ + sp.ch. |Type 'caty%catycatycaty@gmail.com'. Push [Submit] button.|Error message|
|63| [Email] field invalid input before @ + sp.ch. |Type 'caty♣catycatycaty@gmail.com'. Push [Submit] button.|Error message|
|64| [Email] field valid input after @ + sp.ch. |Type 'catycatycatycaty@g.mail.com'. Push [Submit] button.|No error message|
|65| [Email] field valid input after @ + sp.ch. |Type 'catycatycatycaty@g-mail.com'. Push [Submit] button.|No error message|
|66| [Email] field valid input after @ + sp.ch. |Type 'catycatycatycaty@g7mail.com'. Push [Submit] button.|No error message|
|67| [Email] field invalid input after @ + sp.ch. |Type 'catycatycatycaty@g%mail.com'. Push [Submit] button.|Error message|
|68| [Email] field invalid input after @ + sp.ch. |Type 'catycatycatycaty@g♣mail.com'. Push [Submit] button.|Error message|
|69| [Email] field invalid Cyrillic |Type 'catycatycatycatт@gmail.com'. Push [Submit] button.|Error message|
|70| [Email] field invalid input after . sp.ch. |Type 'catycatycatycaty@gmail.%om'. Push [Submit] button.|Error message|
|71| [Email] field invalid input after . digit |Type 'catycatycatycaty@gmail.4om'. Push [Submit] button.|Error message|
|72| [Email] field invalid input sp.ch. in a row |Type 'caty--catycatycaty@gmail.com'. Push [Submit] button.|Error message|
|73| [Email] field content alignment |Type 'catycatycatycaty@gmail.com'. Push [Submit] button.|Alignment to the left side|
|74| [Email] field valid input upper case |Type 'Catycatycatycaty@gmail.com'. Push [Submit] button.|No error message|
|75| [Password] field valid input length|Type '12345678910Abc-'. Push [Submit] button.|No error message|
|76| [Password] field valid input length |Type'1234Abc-'. Push [Submit] button.|No error message|
|77| [Password] field valid input length|Type '123456789012345678901234567890A-'. Push [Submit] button.|No error message|
|78| [Password] field valid input hide with bullets|Type anything.|Password is hidden with bullets|
|79| [Password] field invalid input length|Type '123Abc-'. Push [Submit] button.|Error message|
|80| [Password] field invalid input length|Type '123456789012345678901234567890Ab-'. Push [Submit] button.|Error message|
|81| [Password] field valid input length|Type '12345678910Abc.' . Push [Submit] button.|No error message|
|82| [Password] field valid input length|Type '12345678910Abc_'. Push [Submit] button.|No error message|
|83| [Password] field valid input length|Type '12345678910Abc%'. Push [Submit] button.|Error message|
|84| [Password] field valid input length|Type '12345678910Abc♣'. Push [Submit] button.|Error message|
|85| [Password] field copy|Type anything in the field. Copy data you typed.|Can not copy data in the field|
|86| [Password] field valid input paste|Paste any data in the field.|User is enable to paste data|
|87| Refresh page check|All fields filled in. Do not push [Submit] button. Refresh page|Data remained in the fields|
|88| Error messages|Type invalid data in all fields. Push [Submit] button.|One error message is displayed at a time for the first field with invalid data|
|89| Error messages|Correct data in the first field to meet requirements. Push [Submit] button.|Error message is displayed for the second field with invalid data|
|90| Error messages|Type invalid data in [Name] field. Push [Submit] button.|Error message. No data erased in the field|
|91| Error messages|Type invalid data in [Surname] field. Push [Submit] button.|Error message. No data erased in the field|
|92| Error messages|Type invalid data in [Email] field. Push [Submit] button.|Error message. No data erased in the field|
|93| Error messages|Type invalid data in [Password] field. Push [Submit] button.|Error message. No data erased in the field|

