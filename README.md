# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

\
_Accessibility Reader <sub><sup>__iOS__</sup></sub>_
~~~yaml
apple-axreader://
~~~
_App Store_
~~~yaml
itms-apps://?action=today
~~~
_App Store ··· Updates_
~~~yaml
itms-apps://?action=updates
~~~
_App Store ··· search for ‘example’_
~~~yaml
itms-apps://?action=search&term=example
~~~
_App Store ··· Safari Extensions_
~~~yaml
itms-apps://safariExtensions
~~~
_App Store ··· Apps for Wallet_
~~~yaml
itms-apps://?action=passbook
~~~
_App Store <sub><sup>__iOS__</sup></sub> ··· Trending ··· “Great apps to try with SharePlay”_
~~~yaml
itms-apps://sharePlayApps
~~~
_Apple Configurator <sub><sup>__macOS__</sup></sub>_
~~~yaml
configurator://
~~~
_Apps <sub><sup>__macOS__</sup></sub>_
~~~yaml
spotlight://apps
~~~
_Calculator_
~~~yaml
calc://
~~~
_Calendar <sub><sup>__iOS__</sup></sub>_
~~~yaml
calshow://
~~~
_Calendar <sub><sup>__macOS__</sup></sub>_
~~~yaml
ical://
~~~
_Calendar ··· add subscription calendar_
~~~yaml
webcal://
~~~
_Calendar <sub><sup>__iOS__</sup></sub> ··· calendars_
~~~yaml
calshow://familyCalendar
~~~
_Camera <sub><sup>__iOS__</sup></sub>_
~~~yaml
camera://
~~~
_Camera <sub><sup>__iOS__</sup></sub> ··· photo mode_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=back
~~~
_Camera <sub><sup>__iOS__</sup></sub> ··· video mode_
~~~yaml
camera://configuration?capturemode=video&capturedevice=back
~~~
_Camera <sub><sup>__iOS__</sup></sub> ··· photo mode with front-facing camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=front
~~~
_Camera <sub><sup>__iOS__</sup></sub> ··· video mode with front-facing camera_
~~~yaml
camera://configuration?capturemode=video&capturedevice=front
~~~
_Clock_
~~~yaml
clock-worldclock://
~~~
_Contacts_
~~~yaml
contacts-sensitive://
~~~
_Contacts <sub><sup>__iOS__</sup></sub> ··· List ··· Other Known_
~~~yaml
contacts-sensitive:///list/other-known
~~~
_Desk View <sub><sup>__macOS__</sup></sub>_
~~~yaml
deskcam://
~~~
_Dictionary <sub><sup>__macOS__</sup></sub>_
~~~yaml
dict://
~~~
_Dictionary <sub><sup>__macOS__</sup></sub> ··· search for ‘example’_
~~~yaml
dict://example
~~~
_FaceTime_
~~~yaml
facetimeapp://
~~~
_FaceTime ··· call [contact name/phone number]_
~~~yaml
facetime://replace_with_name_or_number
~~~
_Feedback Assistant_
~~~yaml
applefeedback://
~~~
_Feedback Assistant ··· New Feedback_
~~~yaml
applefeedback://new
~~~
_Files <sub><sup>__iOS__</sup></sub>_
~~~yaml
shareddocuments://
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· Recents_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· iCloud Drive_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/iCloud%20Drive.app
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· AirDrop_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/AirDrop.app
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· [current Mac]_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Computer.app
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· Network_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Network.app
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· Shared_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedDocuments.cannedSearch
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· Shared By Me_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedByMe.cannedSearch	
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· Shared With Me_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedWithMe.cannedSearch
~~~
_Finder <sub><sup>__macOS__</sup></sub> ··· /Users/Shared_
~~~yaml
file:///Users/Shared
~~~
_Font Book <sub><sup>__macOS__</sup></sub>_
~~~yaml
fontbook://
~~~
_Freeform_
~~~yaml
freeform://
~~~
_Games_
~~~yaml
games://
~~~
_Home <sub><sup>__iOS__</sup></sub>_
~~~yaml
com.apple.home://
~~~
_Home <sub><sup>__iOS__</sup></sub> ··· Climate_
~~~yaml
com.apple.home://accessorytype/climate
~~~
_Home <sub><sup>__iOS__</sup></sub> ··· Lights_
~~~yaml
com.apple.home://accessorytype/lights
~~~
_Home <sub><sup>__iOS__</sup></sub> ··· Security_
~~~yaml
com.apple.home://accessorytype/security
~~~
_Home <sub><sup>__iOS__</sup></sub> ··· Home Settings ··· Recognize My Voice ··· Personal Content_
~~~yaml
com.apple.home://personalRequestOptIn
~~~
_Journal_
~~~yaml
moments://
~~~
_Keynote <sub><sup>__macOS__</sup></sub>_
~~~yaml
com.apple.iwork.keynote-share://
~~~
_Magnifier <sub><sup>__iOS__</sup></sub>_
~~~yaml
apple-magnifier://
~~~
_Mail <sub><sup>__iOS__</sup></sub>_
~~~yaml
com.apple.mobilemail://
~~~
_Mail ··· new email_
~~~yaml
mailto://
~~~
_Mail ··· new email with recipient supplied_
~~~yaml
mailto:someone@example.com
~~~
_Mail ··· new email with multiple recipients supplied_
~~~yaml
mailto:someone@example.com,another@example.com
~~~
_Mail ··· new email with recipient supplied, using the ‘Name <user</span>@domain.tld>’ form_
~~~yaml
mailto:Someone%20%3Csomeone@example.com%3E
~~~
_Mail ··· new email with main and Cc recipients supplied_
~~~yaml
mailto:someone@example.com?cc=another@example.com
~~~
_Mail ··· new email with main, Cc and Bcc recipients supplied_
~~~yaml
mailto:someone@example.com?cc=another@example.com&bcc=different@example.com
~~~
_Mail ··· new email with recipient and subject supplied_
~~~yaml
mailto:someone@example.com?subject=Some%20subject
~~~
_Mail ··· new email with recipient and content supplied_
~~~yaml
mailto:someone@example.com?body=Some%20message
~~~
_Mail ··· new email with recipient, subject and content supplied_
~~~yaml
mailto:someone@example.com?subject=Some%20subject&body=Some%20message
~~~
_Maps_
~~~yaml
maps://
~~~
_Messages_
~~~yaml
iChat://
~~~
_Messages ··· new message_
~~~yaml
sms://
~~~
_Messages ··· new message to phone number ‘12345’_
~~~yaml
sms:12345
~~~
_Messages ··· new message to phone numbers ‘12345’ and ‘67890’_
~~~yaml
sms:?addresses=12345,67890
~~~
_Messages ··· new message with content supplied_
~~~yaml
sms:?body=My%20URL%20encoded%20message
~~~
_Messages ··· new message with content supplied to phone number ‘12345’_
~~~yaml
sms:12345?body=My%20URL%20encoded%20message
~~~
_Messages ··· new message with content supplied to phone numbers ‘12345’ and ‘67890’_
~~~yaml
sms:?addresses=12345,67890&body=My%20URL%20encoded%20message
~~~
_Notes_
~~~yaml
applenotes://
~~~
_Notes <sub><sup>__iOS__</sup></sub> ··· create new note_
~~~yaml
mobilenotes://newNote
~~~
_Notes <sub><sup>__macOS__</sup></sub> ··· create new note_
~~~yaml
notes://newNote?displayMode=paper
~~~
_Numbers <sub><sup>__macOS__</sup></sub>_
~~~yaml
com.apple.iwork.numbers-share://
~~~
_Pages <sub><sup>__macOS__</sup></sub>_
~~~yaml
com.apple.iwork.pages-share://
~~~
_Panel Editor <sub><sup>__macOS__</sup></sub>_
~~~yaml
assistivecontrolpanels://
~~~
_Passwords_
~~~yaml
apple-otpauth://
~~~
_Phone <sub><sup>__macOS__</sup></sub>_
~~~yaml
phoneapp://
~~~
_Phone <sub><sup>__iOS__</sup></sub>_
~~~yaml
mobilephone-recents://
~~~
_Phone ··· call phone number ‘12345’_
~~~yaml
tel:12345
~~~
_Phone <sub><sup>__iOS__</sup></sub> ··· Keypad_
~~~yaml
mobilephone-keypad://
~~~
_Phone <sub><sup>__iOS__</sup></sub> ··· Contacts_
~~~yaml
mobilephone-contacts://
~~~
_Phone <sub><sup>__iOS__</sup></sub> ··· Favorites (only available in Classic mode)_
~~~yaml
mobilephone-favorites://
~~~
_Photos_
~~~yaml
photos://
~~~
_Photos <sub><sup>__iOS__</sup></sub> ··· Library (tab)_
~~~yaml
photos://library
~~~
_Photos <sub><sup>__iOS__</sup></sub> ··· Collections (tab)_
~~~yaml
photos://collections
~~~
_Photos <sub><sup>__iOS__</sup></sub> ··· search for ‘example’_
~~~yaml
photos-navigation://search?searchTerm=example
~~~
_Photos ··· most recent photo_
~~~yaml
photos://lastasset
~~~
_Photos ··· Recently Saved_
~~~yaml
photos://album?name=recently-saved
~~~
_Photos ··· Recently Deleted_
~~~yaml
photos://album?name=recently-deleted
~~~
_Photos ··· Favorites_
~~~yaml
photos://album?name=favorites
~~~
_Photos <sub><sup>__iOS__</sup></sub> ··· Featured Photos_
~~~yaml
photos://featuredPhoto
~~~
_Photos ··· Duplicates_
~~~yaml
photos://album?name=duplicates
~~~
_Photos ··· Memories_
~~~yaml
photos://memory-generation
~~~
_Photos ··· People & Pets_
~~~yaml
photos://people
~~~
_Photos ··· Maps_
~~~yaml
photos://places
~~~
_Photos <sub><sup>__macOS__</sup></sub> ··· Preferences ··· General_
~~~yaml
photos://preferences/general
~~~
_Photos <sub><sup>__macOS__</sup></sub> ··· Preferences ··· iCloud_
~~~yaml
photos://preferences/icloud
~~~
_Photos <sub><sup>__macOS__</sup></sub> ··· Preferences ··· Shared Library_
~~~yaml
photos://preferences/shared-library
~~~
_Reminders_
~~~yaml
x-apple-reminderkit://
~~~
_Safari <sub><sup>__iOS__</sup></sub> ··· search for ‘example’ on DuckDuckGo_
~~~yaml
x-web-search://duckduckgo/?example
~~~
_Safari <sub><sup>__iOS__</sup></sub> ··· search for ‘example’ on Google_
~~~yaml
x-web-search://google/?example
~~~
_Safari <sub><sup>__iOS__</sup></sub> ··· search for ‘example’ on Bing_
~~~yaml
x-web-search://bing/?example
~~~
_Safari <sub><sup>__iOS__</sup></sub> ··· search for ‘example’ on Yahoo_
~~~yaml
x-web-search://yahoo/?example
~~~
_Safari <sub><sup>__iOS__</sup></sub> ··· search for ‘example’ on Ecosia_
~~~yaml
x-web-search://ecosia/?example
~~~
_Safari <sub><sup>__iOS__</sup></sub> ··· search for ‘example’ on Wikipedia_
~~~yaml
x-web-search://wikipedia/?example
~~~
_Script Editor <sub><sup>__macOS__</sup></sub>_
~~~yaml
applescript://
~~~
_Settings <sub><sup>__iOS__</sup></sub>_
~~~yaml
prefs://
~~~
_Shortcuts_
~~~yaml
shortcuts://
~~~
_Shortcuts ··· run shortcut ‘example’_
~~~yaml
shortcuts://run-shortcut?name=example
~~~
_Shortcuts ··· run shortcut ‘example’ with ‘my text’ as input_
~~~yaml
shortcuts://run-shortcut?name=example&input=my%20text
~~~
_Shortcuts <sub><sup>__iOS__</sup></sub> ··· run shortcut ‘example’ with the clipboard as input_
~~~yaml
shortcuts://run-shortcut?name=example&input=clipboard
~~~
_Shortcuts ··· run shortcut and on success, open URL_
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-success=my_success_url
~~~
_Shortcuts ··· run shortcut and if the user cancels, open URL_
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-cancel=my_cancel_url
~~~
_Shortcuts ··· run shortcut and on error, open URL <sub>(note: should be opened from outside Shortcuts app, otherwise the error URL may fail to load)</sub>_
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-error=my_error_url
~~~
_Shortcuts ··· open shortcut ‘example’_
~~~yaml
shortcuts://open-shortcut?name=example
~~~
_Shortcuts ··· create new shortcut_
~~~yaml
shortcuts://create-shortcut
~~~
_Shortcuts <sub><sup>__iOS__</sup></sub> ··· create new automation_
~~~yaml
shortcuts://create-automation
~~~
_Shortcuts <sub><sup>__iOS__</sup></sub> ··· Automations_
~~~yaml
shortcuts://automations
~~~
_Shortcuts ··· Gallery_
~~~yaml
shortcuts://gallery
~~~
_Shortcuts ··· install shortcut using ID from iCloud URL_
~~~yaml
shortcuts://shortcuts/replace_with_id_from_icloud_url
~~~
_System Settings <sub><sup>__macOS__</sup></sub>_
~~~yaml
x-apple.systempreferences://
~~~
_Tips_
~~~yaml
x-apple-tips://
~~~
_Voice Memos <sub><sup>__iOS__</sup></sub>_
~~~yaml
voicememos://
~~~
_Wallet <sub><sup>__iOS__</sup></sub>_
~~~yaml
wallet://
~~~
_Weather_
~~~yaml
weather://
~~~
_Web App <sub><sup>__iOS__</sup></sub> <sub>If you only have a single web page added to your Home Screen, opens that one, otherwise it's quite unpredictable</sub>_
~~~yaml
webapp://
~~~
<br>
<br>
<br>
