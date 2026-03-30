# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

<br>

<sup>_Credit: https://www.w3.org/People/Berners-Lee/ • https://www.apple.com_</sup>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs copied from other online sources_</sup>

<br>
<br>

_Accessibility Reader_ <sup>${\color{red} iOS}$</sup>
~~~yaml
apple-axreader://
~~~
_App Store_
~~~yaml
itms-apps://?action=today
~~~
_App Store > Updates_
~~~yaml
itms-apps://?action=updates
~~~
_App Store > search for ‘example’_
~~~yaml
itms-apps://?action=search&term=example
~~~
_App Store > Safari Extensions_
~~~yaml
itms-apps://safariExtensions
~~~
_App Store > Apps for Wallet_
~~~yaml
itms-apps://?action=passbook
~~~
_App Store_ <sup>${\color{red} iOS}$</sup> _> Trending > “Great apps to try with SharePlay”_
~~~yaml
itms-apps://sharePlayApps
~~~
_Apple Configurator_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
configurator://
~~~
_Apps_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
spotlight://apps
~~~
_Calculator_
~~~yaml
calc://
~~~
_Calendar_ <sup>${\color{red} iOS}$</sup>
~~~yaml
calshow://
~~~
_Calendar_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
ical://
~~~
_Calendar > add subscription calendar_
~~~yaml
webcal://
~~~
_Calendar_ <sup>${\color{red} iOS}$</sup> _> calendars_
~~~yaml
calshow://familyCalendar
~~~
_Camera_ <sup>${\color{red} iOS}$</sup>
~~~yaml
camera://
~~~
_Camera_ <sup>${\color{red} iOS}$</sup> _> photo mode_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=back
~~~
_Camera_ <sup>${\color{red} iOS}$</sup> _> video mode_
~~~yaml
camera://configuration?capturemode=video&capturedevice=back
~~~
_Camera_ <sup>${\color{red} iOS}$</sup> _> photo mode with front-facing camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=front
~~~
_Camera_ <sup>${\color{red} iOS}$</sup> _> video mode with front-facing camera_
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
_Contacts_ <sup>${\color{red} iOS}$</sup> _> List > Other Known_
~~~yaml
contacts-sensitive:///list/other-known
~~~
_Desk View_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
deskcam://
~~~
_Dictionary_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
dict://
~~~
_Dictionary_ <sup>${\color{blue} macOS}$</sup> _> search for ‘example’_
~~~yaml
dict://example
~~~
_FaceTime_
~~~yaml
facetimeapp://
~~~
_FaceTime > call [contact name/phone number]_
~~~yaml
facetime://replace_with_name_or_number
~~~
_Feedback Assistant_
~~~yaml
applefeedback://
~~~
_Feedback Assistant > New Feedback_
~~~yaml
applefeedback://new
~~~
_Files_ <sup>${\color{red} iOS}$</sup>
~~~yaml
shareddocuments://
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> Recents_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> iCloud Drive_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/iCloud%20Drive.app
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> AirDrop_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/AirDrop.app
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> [current Mac]_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Computer.app
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> Network_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Network.app
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> Shared_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedDocuments.cannedSearch
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> Shared By Me_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedByMe.cannedSearch	
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> Shared With Me_
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedWithMe.cannedSearch
~~~
_Finder_ <sup>${\color{blue} macOS}$</sup> _> /Users/Shared_
~~~yaml
file:///Users/Shared
~~~
_Font Book_ <sup>${\color{blue} macOS}$</sup>
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
_Home_ <sup>${\color{red} iOS}$</sup>
~~~yaml
com.apple.home://
~~~
_Home_ <sup>${\color{red} iOS}$</sup> _> Climate_
~~~yaml
com.apple.home://accessorytype/climate
~~~
_Home_ <sup>${\color{red} iOS}$</sup> _> Lights_
~~~yaml
com.apple.home://accessorytype/lights
~~~
_Home_ <sup>${\color{red} iOS}$</sup> _> Security_
~~~yaml
com.apple.home://accessorytype/security
~~~
_Home_ <sup>${\color{red} iOS}$</sup> _> Home Settings > Recognize My Voice > Personal Content_
~~~yaml
com.apple.home://personalRequestOptIn
~~~
_Journal_
~~~yaml
moments://
~~~
_Keynote_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
com.apple.iwork.keynote-share://
~~~
_Magnifier_ <sup>${\color{red} iOS}$</sup>
~~~yaml
apple-magnifier://
~~~
_Mail_ <sup>${\color{red} iOS}$</sup>
~~~yaml
com.apple.mobilemail://
~~~
_Mail > new email_
~~~yaml
mailto://
~~~
_Mail > new email with recipient included_
~~~yaml
mailto:someone@example.com
~~~
_Mail > new email with multiple recipients included_
~~~yaml
mailto:someone@example.com,another@example.com
~~~
_Mail > new email with recipient included, using the ‘Name <user</span>@domain.tld>’ form_
~~~yaml
mailto:Someone%20%3Csomeone@example.com%3E
~~~
_Mail > new email with main and Cc recipients included_
~~~yaml
mailto:someone@example.com?cc=another@example.com
~~~
_Mail > new email with main, Cc and Bcc recipients included_
~~~yaml
mailto:someone@example.com?cc=another@example.com&bcc=different@example.com
~~~
_Mail > new email with recipient and subject included_
~~~yaml
mailto:someone@example.com?subject=Some%20subject
~~~
_Mail > new email with recipient and content included_
~~~yaml
mailto:someone@example.com?body=Some%20message
~~~
_Mail > new email with recipient, subject and content included_
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
_Messages > new message_
~~~yaml
sms://
~~~
_Messages > new message to phone number ‘12345’_
~~~yaml
sms:12345
~~~
_Messages > new message to phone numbers ‘12345’ and ‘67890’_
~~~yaml
sms:?addresses=12345,67890
~~~
_Messages > new message with content included_
~~~yaml
sms:?body=My%20URL%20encoded%20message
~~~
_Messages > new message with content included to phone number ‘12345’_
~~~yaml
sms:12345?body=My%20URL%20encoded%20message
~~~
_Messages > new message with content included to phone numbers ‘12345’ and ‘67890’_
~~~yaml
sms:?addresses=12345,67890&body=My%20URL%20encoded%20message
~~~
_Notes_
~~~yaml
applenotes://
~~~
_Notes_ <sup>${\color{red} iOS}$</sup> _> create new note_
~~~yaml
mobilenotes://newNote
~~~
_Notes_ <sup>${\color{blue} macOS}$</sup> _> create new note_
~~~yaml
notes://newNote?displayMode=paper
~~~
_Numbers_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
com.apple.iwork.numbers-share://
~~~
_Pages_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
com.apple.iwork.pages-share://
~~~
_Panel Editor_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
assistivecontrolpanels://
~~~
_Passwords_
~~~yaml
otpauth-migration://
~~~
_Phone_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
phoneapp://
~~~
_Phone_ <sup>${\color{red} iOS}$</sup>
~~~yaml
mobilephone-recents://
~~~
_Phone > call phone number ‘12345’_
~~~yaml
tel:12345
~~~
_Phone_ <sup>${\color{red} iOS}$</sup> _> Keypad_
~~~yaml
mobilephone-keypad://
~~~
_Phone_ <sup>${\color{red} iOS}$</sup> _> Contacts_
~~~yaml
mobilephone-contacts://
~~~
_Phone_ <sup>${\color{red} iOS}$</sup> _> Favorites (only available in Classic mode)_
~~~yaml
mobilephone-favorites://
~~~
_Photos_
~~~yaml
photos://
~~~
_Photos_ <sup>${\color{red} iOS}$</sup> _> Library (tab)_
~~~yaml
photos://library
~~~
_Photos_ <sup>${\color{red} iOS}$</sup> _> Collections (tab)_
~~~yaml
photos://collections
~~~
_Photos_ <sup>${\color{red} iOS}$</sup> _> search for ‘example’_
~~~yaml
photos-navigation://search?searchTerm=example
~~~
_Photos > most recent photo_
~~~yaml
photos://lastasset
~~~
_Photos > Recently Saved_
~~~yaml
photos://album?name=recently-saved
~~~
_Photos > Recently Deleted_
~~~yaml
photos://album?name=recently-deleted
~~~
_Photos > Favorites_
~~~yaml
photos://album?name=favorites
~~~
_Photos_ <sup>${\color{red} iOS}$</sup> _> Featured Photos_
~~~yaml
photos://featuredPhoto
~~~
_Photos > Duplicates_
~~~yaml
photos://album?name=duplicates
~~~
_Photos > Memories_
~~~yaml
photos://memory-generation
~~~
_Photos > People & Pets_
~~~yaml
photos://people
~~~
_Photos > Maps_
~~~yaml
photos://places
~~~
_Photos_ <sup>${\color{blue} macOS}$</sup> _> Preferences > General_
~~~yaml
photos://preferences/general
~~~
_Photos_ <sup>${\color{blue} macOS}$</sup> _> Preferences > iCloud_
~~~yaml
photos://preferences/icloud
~~~
_Photos_ <sup>${\color{blue} macOS}$</sup> _> Preferences > Shared Library_
~~~yaml
photos://preferences/shared-library
~~~
_Reminders_
~~~yaml
x-apple-reminderkit://
~~~
_Safari_ <sup>${\color{red} iOS}$</sup> _> search for ‘example’ on DuckDuckGo_
~~~yaml
x-web-search://duckduckgo/?example
~~~
_Safari_ <sup>${\color{red} iOS}$</sup> _> search for ‘example’ on Google_
~~~yaml
x-web-search://google/?example
~~~
_Safari_ <sup>${\color{red} iOS}$</sup> _> search for ‘example’ on Bing_
~~~yaml
x-web-search://bing/?example
~~~
_Safari_ <sup>${\color{red} iOS}$</sup> _> search for ‘example’ on Yahoo_
~~~yaml
x-web-search://yahoo/?example
~~~
_Safari_ <sup>${\color{red} iOS}$</sup> _> search for ‘example’ on Ecosia_
~~~yaml
x-web-search://ecosia/?example
~~~
_Safari_ <sup>${\color{red} iOS}$</sup> _> search for ‘example’ on Wikipedia_
~~~yaml
x-web-search://wikipedia/?example
~~~
_Script Editor_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
applescript://
~~~
_Settings_ <sup>${\color{red} iOS}$</sup>
~~~yaml
prefs://
~~~
_Shortcuts_
~~~yaml
shortcuts://
~~~
_Shortcuts > run shortcut ‘example’_
~~~yaml
shortcuts://run-shortcut?name=example
~~~
_Shortcuts > run shortcut ‘example’ with ‘my text’ as input_
~~~yaml
shortcuts://run-shortcut?name=example&input=my%20text
~~~
_Shortcuts_ <sup>${\color{red} iOS}$</sup> _> run shortcut ‘example’ with the clipboard as input_
~~~yaml
shortcuts://run-shortcut?name=example&input=clipboard
~~~
_Shortcuts > run shortcut and on success, open URL_
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-success=my_success_url
~~~
_Shortcuts > run shortcut and if the user cancels, open URL_
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-cancel=my_cancel_url
~~~
_Shortcuts > run shortcut and on error, open URL <sub>(note: should be opened from outside Shortcuts app, otherwise the error URL may fail to load)</sub>_
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-error=my_error_url
~~~
_Shortcuts > open shortcut ‘example’_
~~~yaml
shortcuts://open-shortcut?name=example
~~~
_Shortcuts > create new shortcut_
~~~yaml
shortcuts://create-shortcut
~~~
_Shortcuts_ <sup>${\color{red} iOS}$</sup> _> create new automation_
~~~yaml
shortcuts://create-automation
~~~
_Shortcuts_ <sup>${\color{red} iOS}$</sup> _> Automations_
~~~yaml
shortcuts://automations
~~~
_Shortcuts > Gallery_
~~~yaml
shortcuts://gallery
~~~
_Shortcuts > install shortcut using ID from iCloud URL_
~~~yaml
shortcuts://shortcuts/replace_with_id_from_icloud_url
~~~
_System Settings_ <sup>${\color{blue} macOS}$</sup>
~~~yaml
x-apple.systempreferences://
~~~
_Tips_
~~~yaml
x-apple-tips://
~~~
_Voice Memos_ <sup>${\color{red} iOS}$</sup>
~~~yaml
voicememos://
~~~
_Wallet_ <sup>${\color{red} iOS}$</sup>
~~~yaml
wallet://
~~~
_Weather_
~~~yaml
weather://
~~~
_Web App_ <sup>${\color{red} iOS}$</sup> <sub>If you only have a single web app installed/web page added to your Home Screen, the URL will open that one (unpredictable otherwise)</sub>_
~~~yaml
webapp://
~~~
<br>
<br>
<br>
