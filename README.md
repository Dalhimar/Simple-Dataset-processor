This is a simple HTML program I wrote to let me quickly iterate through conversational logs and change them into a JSON format.

The program loads a text file from your computer and puts the contents into a text box on the left textbox, or the user can copy and paste the data into the left textbox.
The user can then highlight the text within the left window, and transfer it to the upper middle window with a button, or they can type in their own data into the upper middle textbox.
The program will take the text within the upper middle textbox, and perform live updates to the lower middle textbox, converting it into a predefined JSON format.
The user can then press the "Approve Entry" button to transfer the contents of the lower middle textbox over to the right side. It does a quick JSON parse check to see if the entry is valid before moving it.
As the user iterates through more entries, it will append the approved entries to the right textbox, separating each entry with a comma. Each time an entry is approved, it increases the message counter by 1. Each time the user changes the Conversation counter, it resets the message counter to 1.
