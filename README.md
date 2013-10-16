jConfirmAction is a minimalistic jQuery plugin for replacing default confirmation. 

Creating confirmation box :
$(yourElement).jConfirmAction();

Options currently only for localization, there are :
question -> Text question of confirmation
yesAnswer -> 'Yes' text
cancelAnswer -> 'Cancel' text

Example usage using options :
$(yourElement).jConfirmAction({
	question : 'Are you sure to delete?', 
	yesAnswer : "Yes", 
	cancelAnswer : "Cancel"
});