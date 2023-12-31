# Requirements questions and answers
Testing site: http://itcareer.pythonanywhere.com/ 
1. **Q:** Required fields  **A:** Name, Email, Password
+ **Name**  
2. **Q:** Maximum, minimum number of characters **A:** Max=64, min=4
3. **Q:** Case sensitive **A:**  No
4. **Q:** Case vary? **A:** Can be uppercase, can be lowercase
5. **Q:** Types of special characters **A:** Space, hyphen, single quotes
6. **Q:** Can only be printed or can be copied from the clipboard **A:** Can be printed, can be copy-pasted
7. **Q:** Spaces as a special character, spaces at the beginning and at the end of the line **A:** As special character space can be used, but not at the beginning and not in the end
8. **Q:** Line break - special character? **A:** No
9. **Q:** Must not start and end with a special character? **A:** Yes
10. **Q:** Can I use two special characters in a row? **A:** No
11. **Q:** Requirements for a placeholder, the presence of a placeholder **A:** Presence - yes, no special characters at the end
12. **Q:** Language to fill in the field **A:** Latin 
13. **Q:** What is the validation practice? **A:** Appearance of hints, red frame 
14. **Q:** At what point does the validation work, when the focus is removed from the field or when you click on the 'Submit' button **A:** When you push 'submit'
15. **Q:** 'Tab'  works? Support for 'Shift+Tab' **A:** Yes, yes
16. **Q:** How should the field react to the excess of characters (do not allow printing, or give, but then give an error) **A:** Not implemented
+ **Surname** everything as for  **Name** except the minimum of characters - 0
+ **Email field**
18. **Q:** Is the email field filled according to the email standard? Read about email standards **A:** Not standartized
19. **Q:** How many characters before @? min max **A:** Max=32, min=4
20. **Q:** After @ to last point min max **A:** Max=32, min=4
21. **Q:** From point to end **A:** Max=16, min =2
22. **Q:** Max number of characters**A:** 82
23. **Q:** Valid characters up to the @ **A:** Dot, hyphen, underline, digits
24. **Q:** Valid characters after the @ **A:** Dot, hyphen, digits
25. **Q:** Language for email **A:** Latin
26. **Q:** What sp. characters can be used after last dot**A:** Only letters
27. **Q:** Is it possible to use special characters in a row **A:** No
28. **Q:** Align margins on which side or center **A:** Left align
29. **Q:** Character case for email **A:** Both
+ **Password field**
30. **Q:** Max, min number of characters **A:** max=32, min =8
31. **Q:** Types of characters possible **A:** Dot, underline, hyphen
32. **Q:** Filling rules **A:** One number, one letter, one special character, 1 uppercase 
33. **Q:** Should the field be filled with bullets at the time of filling **A:** Yes
34. **Q:** Eye feature **A:** No
35. **Q:** Password verification - second line **A:** No
36. **Q:** Can the password match the mail **A:** No
37. **Q:** Capslock indicator **A:** No
38. **Q:** If an error message occurs, should the fields be erased or remain filled in? **A:** Should remain filled in
39. **Q:** If all the fields are filled in, the submit is not clicked, the page is refreshed, should the data remain? **A:** Data shoul remain
40. **Q:** How errors are displayed in the error message: one at a time or all at once if there are several **A:** Message one at a time in order asc
41. **Q:** Password cannot be copied from password field, but it can be copy from anothe place and pasted into password field **A:** Yes, yes
