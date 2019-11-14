# SimpleTwitchChat
Personal Project that I am hoping to create my personal twitch chat that reads the chat from my stream and allows me to respond back to my chat via my program.

Initiated a new repo, and copied my current code for twitchChat into this repository.

twitchChat v1.0 -> Currently experiences issues closing the application.
.
.
.
.
twitchChat v1.5 -> Changed application name to "SimpleTwitchChat"
.
SimpleTwitchChat v1.5 -> First started using wxWebConnect library to create a static browser that only viewed hardcoded url, however, due to compilation issues,
						 switched to wxWebView that comes in built in with the wxWidgets source code.

SimpleTwitchChat v.1.6 -> Constantly running into an event handling syntax issue due to Visual Studio changing the way it deals with the event handlers. Still can't figure out the
						  right format to use. Below is the error I am keep running into:

						"Severity	Code	Description	Project	File	Line	Suppression State
						Error	C2664	'void wxEventFunctorMethod<EventTag,wxWindowBase,EventArg,EventHandler>::CheckHandlerArgument(EventArg *)': cannot convert argument from 'wxCommandEvent *' to 'EventArg *'
        				with
        				[
            				EventTag=wxEventTypeTag<wxCommandEvent>,
            				EventArg=wxHelpEvent,
            				EventHandler=WebFrame
        				]
        				and
        				[
            				EventArg=wxHelpEvent
        				]	wxTwitchChatApp	C:\Program Files (x86)\wxWidgets-3.1.2\include\wx\event.h	374	"


