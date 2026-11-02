First Wrong Value:
When the button is clicked, the text inside the button does not change.
Hypothesis:
The html is put in after the script so the script is being overwritten.
Fix: 
I moved the Html before the script.
Explianation: 
Now the html is before the script, the button is created with the text "Save" then changed to "Ready" by the script.
Tests:
1. Button existed at execution
2. Error message is given if button is found null
3. All matching elements are handled




