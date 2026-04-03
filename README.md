# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

<br>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs that have been copied from outside sources_</sup>

<br>
<br>

_Accessibility Reader <sup>iOS</sup>_
~~~robot
apple-axreader://
~~~
_App Store_
~~~robot
itms-apps://?action=today
~~~
_App Store › Updates_
~~~robot
itms-apps://?action=updates
~~~
_App Store › search for ‘example’_
~~~robot
itms-apps://?action=search&term=example
~~~
_App Store › Safari Extensions_
~~~robot
itms-apps://safariExtensions
~~~
_App Store › Apps for Wallet_
~~~robot
itms-apps://?action=passbook
~~~
_App Store <sup>iOS</sup> › Trending › “Great apps to try with SharePlay”_
~~~robot
itms-apps://sharePlayApps
~~~
_Apple Configurator <sup>macOS</sup>_
~~~robot
configurator://
~~~
_Apps <sup>macOS</sup>_
~~~robot
spotlight://apps
~~~
_Calculator_
~~~robot
calc://
~~~
_Calendar <sup>iOS</sup>_
~~~robot
calshow://
~~~
_Calendar <sup>macOS</sup>_
~~~robot
ical://
~~~
_Calendar › add subscription calendar_
~~~robot
webcal://
~~~
_Calendar <sup>iOS</sup> › calendars_
~~~robot
calshow://familyCalendar
~~~
_Camera <sup>iOS</sup>_
~~~robot
camera://
~~~
_Camera <sup>iOS</sup> › photo mode_
~~~robot
camera://configuration?capturemode=photo&capturedevice=back
~~~
_Camera <sup>iOS</sup> › video mode_
~~~robot
camera://configuration?capturemode=video&capturedevice=back
~~~
_Camera <sup>iOS</sup> › photo mode with front-facing camera_
~~~robot
camera://configuration?capturemode=photo&capturedevice=front
~~~
_Camera <sup>iOS</sup> › video mode with front-facing camera_
~~~robot
camera://configuration?capturemode=video&capturedevice=front
~~~
_Clock_
~~~robot
clock-worldclock://
~~~
_Contacts_
~~~robot
contacts-sensitive://
~~~
_Contacts <sup>iOS</sup> › List › Other Known_
~~~robot
contacts-sensitive:///list/other-known
~~~
_Desk View <sup>macOS</sup>_
~~~robot
deskcam://
~~~
_Dictionary <sup>macOS</sup>_
~~~robot
dict://
~~~
_Dictionary <sup>macOS</sup> › search for ‘example’_
~~~robot
dict://example
~~~
_FaceTime_
~~~robot
facetimeapp://
~~~
_FaceTime › call [contact name/phone number]_
~~~robot
facetime://replace_with_name_or_number
~~~
_Feedback Assistant_
~~~robot
applefeedback://
~~~
_Feedback Assistant › New Feedback_
~~~robot
applefeedback://new
~~~
_Files <sup>iOS</sup>_
~~~robot
shareddocuments://
~~~
_Finder <sup>macOS</sup> › Recents_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch
~~~
_Finder <sup>macOS</sup> › iCloud Drive_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/iCloud%20Drive.app
~~~
_Finder <sup>macOS</sup> › AirDrop_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/AirDrop.app
~~~
_Finder <sup>macOS</sup> › [current Mac]_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Computer.app
~~~
_Finder <sup>macOS</sup> › Network_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Network.app
~~~
_Finder <sup>macOS</sup> › Shared_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedDocuments.cannedSearch
~~~
_Finder <sup>macOS</sup> › Shared By Me_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedByMe.cannedSearch	
~~~
_Finder <sup>macOS</sup> › Shared With Me_
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedWithMe.cannedSearch
~~~
_Finder <sup>macOS</sup> › /Users/Shared_
~~~robot
file:///Users/Shared
~~~
_Font Book <sup>macOS</sup>_
~~~robot
fontbook://
~~~
_Freeform_
~~~robot
freeform://
~~~
_Games_
~~~robot
games://
~~~
_Home <sup>iOS</sup>_
~~~robot
com.apple.home://
~~~
_Home <sup>iOS</sup> › Climate_
~~~robot
com.apple.home://accessorytype/climate
~~~
_Home <sup>iOS</sup> › Lights_
~~~robot
com.apple.home://accessorytype/lights
~~~
_Home <sup>iOS</sup> › Security_
~~~robot
com.apple.home://accessorytype/security
~~~
_Home <sup>iOS</sup> › Home Settings › Recognize My Voice › Personal Content_
~~~robot
com.apple.home://personalRequestOptIn
~~~
_Journal_
~~~robot
moments://
~~~
_Keynote <sup>macOS</sup>_
~~~robot
com.apple.iwork.keynote-share://
~~~
_Magnifier <sup>iOS</sup>_
~~~robot
apple-magnifier://
~~~
_Mail <sup>iOS</sup>_
~~~robot
com.apple.mobilemail://
~~~
_Mail › new email_
~~~robot
mailto://
~~~
_Mail › new email with recipient included_
~~~robot
mailto:someone@example.com
~~~
_Mail › new email with multiple recipients included_
~~~robot
mailto:someone@example.com,another@example.com
~~~
_Mail › new email with recipient included, using the ‘Name <user</span>@domain.tld>’ form_
~~~robot
mailto:Someone%20%3Csomeone@example.com%3E
~~~
_Mail › new email with main and Cc recipients included_
~~~robot
mailto:someone@example.com?cc=another@example.com
~~~
_Mail › new email with main, Cc and Bcc recipients included_
~~~robot
mailto:someone@example.com?cc=another@example.com&bcc=different@example.com
~~~
_Mail › new email with recipient and subject included_
~~~robot
mailto:someone@example.com?subject=Some%20subject
~~~
_Mail › new email with recipient and content included_
~~~robot
mailto:someone@example.com?body=Some%20message
~~~
_Mail › new email with recipient, subject and content included_
~~~robot
mailto:someone@example.com?subject=Some%20subject&body=Some%20message
~~~
_Maps_
~~~robot
maps://
~~~
_Messages_
~~~robot
iChat://
~~~
_Messages › new message_
~~~robot
sms://
~~~
_Messages › new message to phone number ‘12345’_
~~~robot
sms:12345
~~~
_Messages › new message to phone numbers ‘12345’ and ‘67890’_
~~~robot
sms:?addresses=12345,67890
~~~
_Messages › new message with content included_
~~~robot
sms:?body=My%20URL%20encoded%20message
~~~
_Messages › new message with content included to phone number ‘12345’_
~~~robot
sms:12345?body=My%20URL%20encoded%20message
~~~
_Messages › new message with content included to phone numbers ‘12345’ and ‘67890’_
~~~robot
sms:?addresses=12345,67890&body=My%20URL%20encoded%20message
~~~
_Notes_
~~~robot
applenotes://
~~~
_Notes <sup>iOS</sup> › create new note_
~~~robot
mobilenotes://newNote
~~~
_Notes <sup>macOS</sup> › create new note_
~~~robot
notes://newNote?displayMode=paper
~~~
_Numbers <sup>macOS</sup>_
~~~robot
com.apple.iwork.numbers-share://
~~~
_Pages <sup>macOS</sup>_
~~~robot
com.apple.iwork.pages-share://
~~~
_Panel Editor <sup>macOS</sup>_
~~~robot
assistivecontrolpanels://
~~~
_Passwords_
~~~robot
otpauth-migration://
~~~
_Phone <sup>macOS</sup>_
~~~robot
phoneapp://
~~~
_Phone <sup>iOS</sup>_
~~~robot
mobilephone-recents://
~~~
_Phone › call phone number ‘12345’_
~~~robot
tel:12345
~~~
_Phone <sup>iOS</sup> › Keypad_
~~~robot
mobilephone-keypad://
~~~
_Phone <sup>iOS</sup> › Contacts_
~~~robot
mobilephone-contacts://
~~~
_Phone <sup>iOS</sup> › Favorites (only available in Classic mode)_
~~~robot
mobilephone-favorites://
~~~
_Photos_
~~~robot
photos://
~~~
_Photos <sup>iOS</sup> › Library (tab)_
~~~robot
photos://library
~~~
_Photos <sup>iOS</sup> › Collections (tab)_
~~~robot
photos://collections
~~~
_Photos <sup>iOS</sup> › search for ‘example’_
~~~robot
photos-navigation://search?searchTerm=example
~~~
_Photos › most recent photo_
~~~robot
photos://lastasset
~~~
_Photos › Recently Saved_
~~~robot
photos://album?name=recently-saved
~~~
_Photos › Recently Deleted_
~~~robot
photos://album?name=recently-deleted
~~~
_Photos › Favorites_
~~~robot
photos://album?name=favorites
~~~
_Photos <sup>iOS</sup> › Featured Photos_
~~~robot
photos://featuredPhoto
~~~
_Photos › Duplicates_
~~~robot
photos://album?name=duplicates
~~~
_Photos › Memories_
~~~robot
photos://memory-generation
~~~
_Photos › People & Pets_
~~~robot
photos://people
~~~
_Photos › Maps_
~~~robot
photos://places
~~~
_Photos <sup>macOS</sup> › Preferences › General_
~~~robot
photos://preferences/general
~~~
_Photos <sup>macOS</sup> › Preferences › iCloud_
~~~robot
photos://preferences/icloud
~~~
_Photos <sup>macOS</sup> › Preferences › Shared Library_
~~~robot
photos://preferences/shared-library
~~~
_Reminders_
~~~robot
x-apple-reminderkit://
~~~
_Safari <sup>iOS</sup> › search for ‘example’ on DuckDuckGo_
~~~robot
x-web-search://duckduckgo/?example
~~~
_Safari <sup>iOS</sup> › search for ‘example’ on Google_
~~~robot
x-web-search://google/?example
~~~
_Safari <sup>iOS</sup> › search for ‘example’ on Bing_
~~~robot
x-web-search://bing/?example
~~~
_Safari <sup>iOS</sup> › search for ‘example’ on Yahoo_
~~~robot
x-web-search://yahoo/?example
~~~
_Safari <sup>iOS</sup> › search for ‘example’ on Ecosia_
~~~robot
x-web-search://ecosia/?example
~~~
_Safari <sup>iOS</sup> › search for ‘example’ on Wikipedia_
~~~robot
x-web-search://wikipedia/?example
~~~
_Script Editor <sup>macOS</sup>_
~~~robot
applescript://
~~~
_Settings <sup>iOS</sup>_
~~~robot
prefs://
~~~
_Shortcuts_
~~~robot
shortcuts://
~~~
_Shortcuts › run shortcut ‘example’_
~~~robot
shortcuts://run-shortcut?name=example
~~~
_Shortcuts › run shortcut ‘example’ with ‘my text’ as input_
~~~robot
shortcuts://run-shortcut?name=example&input=my%20text
~~~
_Shortcuts <sup>iOS</sup> › run shortcut ‘example’ with the clipboard as input_
~~~robot
shortcuts://run-shortcut?name=example&input=clipboard
~~~
_Shortcuts › run shortcut and on success, open URL_
~~~robot
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-success=my_success_url
~~~
_Shortcuts › run shortcut and if the user cancels, open URL_
~~~robot
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-cancel=my_cancel_url
~~~
_Shortcuts › run shortcut and on error, open URL<br><sub>Note: should be opened from outside Shortcuts app, otherwise the x-error URL may fail to load</sub>_
~~~robot
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-error=my_error_url
~~~
_Shortcuts › open shortcut ‘example’_
~~~robot
shortcuts://open-shortcut?name=example
~~~
_Shortcuts › create new shortcut_
~~~robot
shortcuts://create-shortcut
~~~
_Shortcuts <sup>iOS</sup> › create new automation_
~~~robot
shortcuts://create-automation
~~~
_Shortcuts <sup>iOS</sup> › Automations_
~~~robot
shortcuts://automations
~~~
_Shortcuts › Gallery_
~~~robot
shortcuts://gallery
~~~
_Shortcuts › install shortcut using ID from iCloud URL_
~~~robot
shortcuts://shortcuts/replace_with_id_from_icloud_url
~~~
_System Settings <sup>macOS</sup>_
~~~robot
x-apple.systempreferences://
~~~
_Tips_
~~~robot
x-apple-tips://
~~~
_Voice Memos <sup>iOS</sup>_
~~~robot
voicememos://
~~~
_Wallet <sup>iOS</sup>_
~~~robot
wallet://
~~~
_Weather_
~~~robot
weather://
~~~
_Web App <sup>iOS</sup><br><sub>If you only have a single web app installed/web page added to your Home Screen, this URL will open that one, otherwise it's unpredictable what it opens</sub>_
~~~robot
webapp://
~~~
<br>
<br>
<br>
