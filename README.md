# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

<br>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs that have been copied from outside sources_</sup>

<br>
<br>

Accessibility Reader <sup>_iOS_</sup>
~~~robot
apple-axreader://
~~~
App Store
~~~robot
itms-apps://?action=today
~~~
App Store › Updates
~~~robot
itms-apps://?action=updates
~~~
App Store › search for ‘example’
~~~robot
itms-apps://?action=search&term=example
~~~
App Store › Safari Extensions
~~~robot
itms-apps://safariExtensions
~~~
App Store › Apps for Wallet
~~~robot
itms-apps://?action=passbook
~~~
App Store <sup>_iOS_</sup> › Trending › “Great apps to try with SharePlay”
~~~robot
itms-apps://sharePlayApps
~~~
Apple Configurator <sup>_macOS_</sup>
~~~robot
configurator://
~~~
Apps <sup>_macOS_</sup>
~~~robot
spotlight://apps
~~~
Calculator
~~~robot
calc://
~~~
Calendar <sup>_iOS_</sup>
~~~robot
calshow://
~~~
Calendar <sup>_macOS_</sup>
~~~robot
ical://
~~~
Calendar › add subscription calendar
~~~robot
webcal://
~~~
Calendar <sup>_iOS_</sup> › calendars
~~~robot
calshow://familyCalendar
~~~
Camera <sup>_iOS_</sup>
~~~robot
camera://
~~~
Camera <sup>_iOS_</sup> › photo mode
~~~robot
camera://configuration?capturemode=photo&capturedevice=back
~~~
Camera <sup>_iOS_</sup> › video mode
~~~robot
camera://configuration?capturemode=video&capturedevice=back
~~~
Camera <sup>_iOS_</sup> › photo mode with front-facing camera
~~~robot
camera://configuration?capturemode=photo&capturedevice=front
~~~
Camera <sup>_iOS_</sup> › video mode with front-facing camera
~~~robot
camera://configuration?capturemode=video&capturedevice=front
~~~
Clock
~~~robot
clock-worldclock://
~~~
Contacts
~~~robot
contacts-sensitive://
~~~
Contacts <sup>_iOS_</sup> › List › Other Known
~~~robot
contacts-sensitive:///list/other-known
~~~
Desk View <sup>_macOS_</sup>
~~~robot
deskcam://
~~~
Dictionary <sup>_macOS_</sup>
~~~robot
dict://
~~~
Dictionary <sup>_macOS_</sup> › search for ‘example’
~~~robot
dict://example
~~~
FaceTime
~~~robot
facetimeapp://
~~~
FaceTime › call [contact name/phone number]
~~~robot
facetime://replace_with_name_or_number
~~~
Feedback Assistant
~~~robot
applefeedback://
~~~
Feedback Assistant › New Feedback
~~~robot
applefeedback://new
~~~
Files <sup>_iOS_</sup>
~~~robot
shareddocuments://
~~~
Finder <sup>_macOS_</sup> › Recents
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch
~~~
Finder <sup>_macOS_</sup> › iCloud Drive
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/iCloud%20Drive.app
~~~
Finder <sup>_macOS_</sup> › AirDrop
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/AirDrop.app
~~~
Finder <sup>_macOS_</sup> › [current Mac]
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Computer.app
~~~
Finder <sup>_macOS_</sup> › Network
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Network.app
~~~
Finder <sup>_macOS_</sup> › Shared
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedDocuments.cannedSearch
~~~
Finder <sup>_macOS_</sup> › Shared By Me
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedByMe.cannedSearch	
~~~
Finder <sup>_macOS_</sup> › Shared With Me
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedWithMe.cannedSearch
~~~
Finder <sup>_macOS_</sup> › /Users/Shared
~~~robot
file:///Users/Shared
~~~
Font Book <sup>_macOS_</sup>
~~~robot
fontbook://
~~~
Freeform
~~~robot
freeform://
~~~
Games
~~~robot
games://
~~~
Home <sup>_iOS_</sup>
~~~robot
com.apple.home://
~~~
Home <sup>_iOS_</sup> › Climate
~~~robot
com.apple.home://accessorytype/climate
~~~
Home <sup>_iOS_</sup> › Lights
~~~robot
com.apple.home://accessorytype/lights
~~~
Home <sup>_iOS_</sup> › Security
~~~robot
com.apple.home://accessorytype/security
~~~
Home <sup>_iOS_</sup> › Home Settings › Recognize My Voice › Personal Content
~~~robot
com.apple.home://personalRequestOptIn
~~~
Journal
~~~robot
moments://
~~~
Keynote <sup>_macOS_</sup>
~~~robot
com.apple.iwork.keynote-share://
~~~
Magnifier <sup>_iOS_</sup>
~~~robot
apple-magnifier://
~~~
Mail <sup>_iOS_</sup>
~~~robot
com.apple.mobilemail://
~~~
Mail › new email
~~~robot
mailto://
~~~
Mail › new email with recipient included
~~~robot
mailto:someone@example.com
~~~
Mail › new email with multiple recipients included
~~~robot
mailto:someone@example.com,another@example.com
~~~
Mail › new email with recipient included, using the ‘Name <user</span>@domain.tld>’ form
~~~robot
mailto:Someone%20%3Csomeone@example.com%3E
~~~
Mail › new email with main and Cc recipients included
~~~robot
mailto:someone@example.com?cc=another@example.com
~~~
Mail › new email with main, Cc and Bcc recipients included
~~~robot
mailto:someone@example.com?cc=another@example.com&bcc=different@example.com
~~~
Mail › new email with recipient and subject included
~~~robot
mailto:someone@example.com?subject=Some%20subject
~~~
Mail › new email with recipient and content included
~~~robot
mailto:someone@example.com?body=Some%20message
~~~
Mail › new email with recipient, subject and content included
~~~robot
mailto:someone@example.com?subject=Some%20subject&body=Some%20message
~~~
Maps
~~~robot
maps://
~~~
Messages
~~~robot
iChat://
~~~
Messages › new message
~~~robot
sms://
~~~
Messages › new message to phone number ‘12345’
~~~robot
sms:12345
~~~
Messages › new message to phone numbers ‘12345’ and ‘67890’
~~~robot
sms:?addresses=12345,67890
~~~
Messages › new message with content included
~~~robot
sms:?body=My%20URL%20encoded%20message
~~~
Messages › new message with content included to phone number ‘12345’
~~~robot
sms:12345?body=My%20URL%20encoded%20message
~~~
Messages › new message with content included to phone numbers ‘12345’ and ‘67890’
~~~robot
sms:?addresses=12345,67890&body=My%20URL%20encoded%20message
~~~
Notes
~~~robot
applenotes://
~~~
Notes <sup>_iOS_</sup> › create new note
~~~robot
mobilenotes://newNote
~~~
Notes <sup>_macOS_</sup> › create new note
~~~robot
notes://newNote?displayMode=paper
~~~
Numbers <sup>_macOS_</sup>
~~~robot
com.apple.iwork.numbers-share://
~~~
Pages <sup>_macOS_</sup>
~~~robot
com.apple.iwork.pages-share://
~~~
Panel Editor <sup>_macOS_</sup>
~~~robot
assistivecontrolpanels://
~~~
Passwords
~~~robot
otpauth-migration://
~~~
Phone <sup>_macOS_</sup>
~~~robot
phoneapp://
~~~
Phone <sup>_iOS_</sup>
~~~robot
mobilephone-recents://
~~~
Phone › call phone number ‘12345’
~~~robot
tel:12345
~~~
Phone <sup>_iOS_</sup> › Keypad
~~~robot
mobilephone-keypad://
~~~
Phone <sup>_iOS_</sup> › Contacts
~~~robot
mobilephone-contacts://
~~~
Phone <sup>_iOS_</sup> › Favorites (only available in Classic mode)
~~~robot
mobilephone-favorites://
~~~
Photos
~~~robot
photos://
~~~
Photos <sup>_iOS_</sup> › Library (tab)
~~~robot
photos://library
~~~
Photos <sup>_iOS_</sup> › Collections (tab)
~~~robot
photos://collections
~~~
Photos <sup>_iOS_</sup> › search for ‘example’
~~~robot
photos-navigation://search?searchTerm=example
~~~
Photos › most recent photo
~~~robot
photos://lastasset
~~~
Photos › Recently Saved
~~~robot
photos://album?name=recently-saved
~~~
Photos › Recently Deleted
~~~robot
photos://album?name=recently-deleted
~~~
Photos › Favorites
~~~robot
photos://album?name=favorites
~~~
Photos <sup>_iOS_</sup> › Featured Photos
~~~robot
photos://featuredPhoto
~~~
Photos › Duplicates
~~~robot
photos://album?name=duplicates
~~~
Photos › Memories
~~~robot
photos://memory-generation
~~~
Photos › People & Pets
~~~robot
photos://people
~~~
Photos › Maps
~~~robot
photos://places
~~~
Photos <sup>_macOS_</sup> › Preferences › General
~~~robot
photos://preferences/general
~~~
Photos <sup>_macOS_</sup> › Preferences › iCloud
~~~robot
photos://preferences/icloud
~~~
Photos <sup>_macOS_</sup> › Preferences › Shared Library
~~~robot
photos://preferences/shared-library
~~~
Reminders
~~~robot
x-apple-reminderkit://
~~~
Safari <sup>_iOS_</sup> › search for ‘example’ on DuckDuckGo
~~~robot
x-web-search://duckduckgo/?example
~~~
Safari <sup>_iOS_</sup> › search for ‘example’ on Google
~~~robot
x-web-search://google/?example
~~~
Safari <sup>_iOS_</sup> › search for ‘example’ on Bing
~~~robot
x-web-search://bing/?example
~~~
Safari <sup>_iOS_</sup> › search for ‘example’ on Yahoo
~~~robot
x-web-search://yahoo/?example
~~~
Safari <sup>_iOS_</sup> › search for ‘example’ on Ecosia
~~~robot
x-web-search://ecosia/?example
~~~
Safari <sup>_iOS_</sup> › search for ‘example’ on Wikipedia
~~~robot
x-web-search://wikipedia/?example
~~~
Script Editor <sup>_macOS_</sup>
~~~robot
applescript://
~~~
Settings <sup>_iOS_</sup>
~~~robot
prefs://
~~~
Shortcuts
~~~robot
shortcuts://
~~~
Shortcuts › run shortcut ‘example’
~~~robot
shortcuts://run-shortcut?name=example
~~~
Shortcuts › run shortcut ‘example’ with ‘my text’ as input
~~~robot
shortcuts://run-shortcut?name=example&input=my%20text
~~~
Shortcuts <sup>_iOS_</sup> › run shortcut ‘example’ with the clipboard as input
~~~robot
shortcuts://run-shortcut?name=example&input=clipboard
~~~
Shortcuts › run shortcut and on success, open URL
~~~robot
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-success=my_success_url
~~~
Shortcuts › run shortcut and if the user cancels, open URL
~~~robot
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-cancel=my_cancel_url
~~~
Shortcuts › run shortcut and on error, open URL<br><sub>Note: should be opened from outside Shortcuts app, otherwise the x-error URL may fail to load</sub>
~~~robot
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-error=my_error_url
~~~
Shortcuts › open shortcut ‘example’
~~~robot
shortcuts://open-shortcut?name=example
~~~
Shortcuts › create new shortcut
~~~robot
shortcuts://create-shortcut
~~~
Shortcuts <sup>_iOS_</sup> › create new automation
~~~robot
shortcuts://create-automation
~~~
Shortcuts <sup>_iOS_</sup> › Automations
~~~robot
shortcuts://automations
~~~
Shortcuts › Gallery
~~~robot
shortcuts://gallery
~~~
Shortcuts › install shortcut using ID from iCloud URL
~~~robot
shortcuts://shortcuts/replace_with_id_from_icloud_url
~~~
System Settings <sup>_macOS_</sup>
~~~robot
x-apple.systempreferences://
~~~
Tips
~~~robot
x-apple-tips://
~~~
Voice Memos <sup>_iOS_</sup>
~~~robot
voicememos://
~~~
Wallet <sup>_iOS_</sup>
~~~robot
wallet://
~~~
Weather
~~~robot
weather://
~~~
Web App <sup>_iOS_</sup><br><sub>If you only have a single web app installed/web page added to your Home Screen, this URL will open that one, otherwise it's unpredictable what it opens</sub>
~~~robot
webapp://
~~~
<br>
<br>
<br>
