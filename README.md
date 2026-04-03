# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

<br>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs that have been copied from outside sources_</sup>

<br>
<br>

Accessibility Reader ${\sf\small\color{rgb(256, 128, 256)} iOS}$
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
App Store ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Trending › “Great apps to try with SharePlay”
~~~robot
itms-apps://sharePlayApps
~~~
Apple Configurator ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
configurator://
~~~
Apps ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
spotlight://apps
~~~
Calculator
~~~robot
calc://
~~~
Calendar ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
calshow://
~~~
Calendar ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
ical://
~~~
Calendar › add subscription calendar
~~~robot
webcal://
~~~
Calendar ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › calendars
~~~robot
calshow://familyCalendar
~~~
Camera ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
camera://
~~~
Camera ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › photo mode
~~~robot
camera://configuration?capturemode=photo&capturedevice=back
~~~
Camera ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › video mode
~~~robot
camera://configuration?capturemode=video&capturedevice=back
~~~
Camera ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › photo mode with front-facing camera
~~~robot
camera://configuration?capturemode=photo&capturedevice=front
~~~
Camera ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › video mode with front-facing camera
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
Contacts ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › List › Other Known
~~~robot
contacts-sensitive:///list/other-known
~~~
Desk View ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
deskcam://
~~~
Dictionary ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
dict://
~~~
Dictionary ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › search for ‘example’
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
Files ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
shareddocuments://
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Recents
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › iCloud Drive
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/iCloud%20Drive.app
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › AirDrop
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/AirDrop.app
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › [current Mac]
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Computer.app
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Network
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Network.app
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Shared
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedDocuments.cannedSearch
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Shared By Me
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedByMe.cannedSearch	
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Shared With Me
~~~robot
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedWithMe.cannedSearch
~~~
Finder ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › /Users/Shared
~~~robot
file:///Users/Shared
~~~
Font Book ${\sf\small\color{rgb(256, 128, 256)} macOS}$
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
Home ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
com.apple.home://
~~~
Home ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Climate
~~~robot
com.apple.home://accessorytype/climate
~~~
Home ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Lights
~~~robot
com.apple.home://accessorytype/lights
~~~
Home ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Security
~~~robot
com.apple.home://accessorytype/security
~~~
Home ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Home Settings › Recognize My Voice › Personal Content
~~~robot
com.apple.home://personalRequestOptIn
~~~
Journal
~~~robot
moments://
~~~
Keynote ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
com.apple.iwork.keynote-share://
~~~
Magnifier ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
apple-magnifier://
~~~
Mail ${\sf\small\color{rgb(256, 128, 256)} iOS}$
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
Notes ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › create new note
~~~robot
mobilenotes://newNote
~~~
Notes ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › create new note
~~~robot
notes://newNote?displayMode=paper
~~~
Numbers ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
com.apple.iwork.numbers-share://
~~~
Pages ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
com.apple.iwork.pages-share://
~~~
Panel Editor ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
assistivecontrolpanels://
~~~
Passwords
~~~robot
otpauth-migration://
~~~
Phone ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
phoneapp://
~~~
Phone ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
mobilephone-recents://
~~~
Phone › call phone number ‘12345’
~~~robot
tel:12345
~~~
Phone ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Keypad
~~~robot
mobilephone-keypad://
~~~
Phone ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Contacts
~~~robot
mobilephone-contacts://
~~~
Phone ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Favorites (only available in Classic mode)
~~~robot
mobilephone-favorites://
~~~
Photos
~~~robot
photos://
~~~
Photos ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Library (tab)
~~~robot
photos://library
~~~
Photos ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Collections (tab)
~~~robot
photos://collections
~~~
Photos ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › search for ‘example’
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
Photos ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Featured Photos
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
Photos ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Preferences › General
~~~robot
photos://preferences/general
~~~
Photos ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Preferences › iCloud
~~~robot
photos://preferences/icloud
~~~
Photos ${\sf\small\color{rgb(256, 128, 256)} macOS}$ › Preferences › Shared Library
~~~robot
photos://preferences/shared-library
~~~
Reminders
~~~robot
x-apple-reminderkit://
~~~
Safari ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › search for ‘example’ on DuckDuckGo
~~~robot
x-web-search://duckduckgo/?example
~~~
Safari ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › search for ‘example’ on Google
~~~robot
x-web-search://google/?example
~~~
Safari ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › search for ‘example’ on Bing
~~~robot
x-web-search://bing/?example
~~~
Safari ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › search for ‘example’ on Yahoo
~~~robot
x-web-search://yahoo/?example
~~~
Safari ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › search for ‘example’ on Ecosia
~~~robot
x-web-search://ecosia/?example
~~~
Safari ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › search for ‘example’ on Wikipedia
~~~robot
x-web-search://wikipedia/?example
~~~
Script Editor ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
applescript://
~~~
Settings ${\sf\small\color{rgb(256, 128, 256)} iOS}$
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
Shortcuts ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › run shortcut ‘example’ with the clipboard as input
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
Shortcuts ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › create new automation
~~~robot
shortcuts://create-automation
~~~
Shortcuts ${\sf\small\color{rgb(256, 128, 256)} iOS}$ › Automations
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
System Settings ${\sf\small\color{rgb(256, 128, 256)} macOS}$
~~~robot
x-apple.systempreferences://
~~~
Tips
~~~robot
x-apple-tips://
~~~
Voice Memos ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
voicememos://
~~~
Wallet ${\sf\small\color{rgb(256, 128, 256)} iOS}$
~~~robot
wallet://
~~~
Weather
~~~robot
weather://
~~~
Web App ${\sf\small\color{rgb(256, 128, 256)} iOS}$<br><sub>If you only have a single web app installed/web page added to your Home Screen, this URL will open that one, otherwise it's unpredictable what it opens</sub>
~~~robot
webapp://
~~~
<br>
<br>
<br>
