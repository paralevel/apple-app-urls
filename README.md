# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

<br>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs that have been copied from outside sources_</sup>

<br>
<br>

Accessibility Reader ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
apple-axreader://
~~~
App Store
~~~csv
itms-apps://?action=today
~~~
App Store › Updates
~~~csv
itms-apps://?action=updates
~~~
App Store › search for ‘example’
~~~csv
itms-apps://?action=search&term=example
~~~
App Store › Safari Extensions
~~~csv
itms-apps://safariExtensions
~~~
App Store › Apps for Wallet
~~~csv
itms-apps://?action=passbook
~~~
App Store ${\sf\small\color{DeepSkyBlue} iOS}$ › Trending › “Great apps to try with SharePlay”
~~~csv
itms-apps://sharePlayApps
~~~
Apple Configurator ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
configurator://
~~~
Apps ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
spotlight://apps
~~~
Calculator
~~~csv
calc://
~~~
Calendar ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
calshow://
~~~
Calendar ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
ical://
~~~
Calendar › add subscription calendar
~~~csv
webcal://
~~~
Calendar ${\sf\small\color{DeepSkyBlue} iOS}$ › calendars
~~~csv
calshow://familyCalendar
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
camera://
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › photo mode
~~~csv
camera://configuration?capturemode=photo&capturedevice=back
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › video mode
~~~csv
camera://configuration?capturemode=video&capturedevice=back
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › photo mode with front-facing camera
~~~csv
camera://configuration?capturemode=photo&capturedevice=front
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › video mode with front-facing camera
~~~csv
camera://configuration?capturemode=video&capturedevice=front
~~~
Clock
~~~csv
clock-worldclock://
~~~
Contacts
~~~csv
contacts-sensitive://
~~~
Contacts ${\sf\small\color{DeepSkyBlue} iOS}$ › List › Other Known
~~~csv
contacts-sensitive:///list/other-known
~~~
Desk View ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
deskcam://
~~~
Dictionary ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
dict://
~~~
Dictionary ${\sf\small\color{DeepSkyBlue} macOS}$ › search for ‘example’
~~~csv
dict://example
~~~
FaceTime
~~~csv
facetimeapp://
~~~
FaceTime › call [contact name/phone number]
~~~csv
facetime://replace_with_name_or_number
~~~
Feedback Assistant
~~~csv
applefeedback://
~~~
Feedback Assistant › New Feedback
~~~csv
applefeedback://new
~~~
Files ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
shareddocuments://
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Recents
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › iCloud Drive
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Applications/iCloud%20Drive.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › AirDrop
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Applications/AirDrop.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › [current Mac]
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Computer.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Network
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Network.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Shared
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedDocuments.cannedSearch
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Shared By Me
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedByMe.cannedSearch	
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Shared With Me
~~~csv
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedWithMe.cannedSearch
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › /Users/Shared
~~~csv
file:///Users/Shared
~~~
Font Book ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
fontbook://
~~~
Freeform
~~~csv
freeform://
~~~
Games
~~~csv
games://
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
com.apple.home://
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Climate
~~~csv
com.apple.home://accessorytype/climate
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Lights
~~~csv
com.apple.home://accessorytype/lights
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Security
~~~csv
com.apple.home://accessorytype/security
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Home Settings › Recognize My Voice › Personal Content
~~~csv
com.apple.home://personalRequestOptIn
~~~
Journal
~~~csv
moments://
~~~
Keynote ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
com.apple.iwork.keynote-share://
~~~
Magnifier ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
apple-magnifier://
~~~
Mail ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
com.apple.mobilemail://
~~~
Mail › new email
~~~csv
mailto://
~~~
Mail › new email with recipient included
~~~csv
mailto:someone@example.com
~~~
Mail › new email with multiple recipients included
~~~csv
mailto:someone@example.com,another@example.com
~~~
Mail › new email with recipient included, using the ‘Name <user</span>@domain.tld>’ form
~~~csv
mailto:Someone%20%3Csomeone@example.com%3E
~~~
Mail › new email with main and Cc recipients included
~~~csv
mailto:someone@example.com?cc=another@example.com
~~~
Mail › new email with main, Cc and Bcc recipients included
~~~csv
mailto:someone@example.com?cc=another@example.com&bcc=different@example.com
~~~
Mail › new email with recipient and subject included
~~~csv
mailto:someone@example.com?subject=Some%20subject
~~~
Mail › new email with recipient and content included
~~~csv
mailto:someone@example.com?body=Some%20message
~~~
Mail › new email with recipient, subject and content included
~~~csv
mailto:someone@example.com?subject=Some%20subject&body=Some%20message
~~~
Maps
~~~csv
maps://
~~~
Messages
~~~csv
iChat://
~~~
Messages › new message
~~~csv
sms://
~~~
Messages › new message to phone number ‘12345’
~~~csv
sms:12345
~~~
Messages › new message to phone numbers ‘12345’ and ‘67890’
~~~csv
sms:?addresses=12345,67890
~~~
Messages › new message with content included
~~~csv
sms:?body=My%20URL%20encoded%20message
~~~
Messages › new message with content included to phone number ‘12345’
~~~csv
sms:12345?body=My%20URL%20encoded%20message
~~~
Messages › new message with content included to phone numbers ‘12345’ and ‘67890’
~~~csv
sms:?addresses=12345,67890&body=My%20URL%20encoded%20message
~~~
Notes
~~~csv
applenotes://
~~~
Notes ${\sf\small\color{DeepSkyBlue} iOS}$ › create new note
~~~csv
mobilenotes://newNote
~~~
Notes ${\sf\small\color{DeepSkyBlue} macOS}$ › create new note
~~~csv
notes://newNote?displayMode=paper
~~~
Numbers ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
com.apple.iwork.numbers-share://
~~~
Pages ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
com.apple.iwork.pages-share://
~~~
Panel Editor ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
assistivecontrolpanels://
~~~
Passwords
~~~csv
otpauth-migration://
~~~
Phone ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
phoneapp://
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
mobilephone-recents://
~~~
Phone › call phone number ‘12345’
~~~csv
tel:12345
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$ › Keypad
~~~csv
mobilephone-keypad://
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$ › Contacts
~~~csv
mobilephone-contacts://
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$ › Favorites (only available in Classic mode)
~~~csv
mobilephone-favorites://
~~~
Photos
~~~csv
photos://
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › Library (tab)
~~~csv
photos://library
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › Collections (tab)
~~~csv
photos://collections
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’
~~~csv
photos-navigation://search?searchTerm=example
~~~
Photos › most recent photo
~~~csv
photos://lastasset
~~~
Photos › Recently Saved
~~~csv
photos://album?name=recently-saved
~~~
Photos › Recently Deleted
~~~csv
photos://album?name=recently-deleted
~~~
Photos › Favorites
~~~csv
photos://album?name=favorites
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › Featured Photos
~~~csv
photos://featuredPhoto
~~~
Photos › Duplicates
~~~csv
photos://album?name=duplicates
~~~
Photos › Memories
~~~csv
photos://memory-generation
~~~
Photos › People & Pets
~~~csv
photos://people
~~~
Photos › Maps
~~~csv
photos://places
~~~
Photos ${\sf\small\color{DeepSkyBlue} macOS}$ › Preferences › General
~~~csv
photos://preferences/general
~~~
Photos ${\sf\small\color{DeepSkyBlue} macOS}$ › Preferences › iCloud
~~~csv
photos://preferences/icloud
~~~
Photos ${\sf\small\color{DeepSkyBlue} macOS}$ › Preferences › Shared Library
~~~csv
photos://preferences/shared-library
~~~
Reminders
~~~csv
x-apple-reminderkit://
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on DuckDuckGo
~~~csv
x-web-search://duckduckgo/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Google
~~~csv
x-web-search://google/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Bing
~~~csv
x-web-search://bing/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Yahoo
~~~csv
x-web-search://yahoo/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Ecosia
~~~csv
x-web-search://ecosia/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Wikipedia
~~~csv
x-web-search://wikipedia/?example
~~~
Script Editor ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
applescript://
~~~
Settings ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
prefs://
~~~
Shortcuts
~~~csv
shortcuts://
~~~
Shortcuts › run shortcut ‘example’
~~~csv
shortcuts://run-shortcut?name=example
~~~
Shortcuts › run shortcut ‘example’ with ‘my text’ as input
~~~csv
shortcuts://run-shortcut?name=example&input=my%20text
~~~
Shortcuts ${\sf\small\color{DeepSkyBlue} iOS}$ › run shortcut ‘example’ with the clipboard as input
~~~csv
shortcuts://run-shortcut?name=example&input=clipboard
~~~
Shortcuts › run shortcut and on success, open URL
~~~csv
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-success=my_success_url
~~~
Shortcuts › run shortcut and if the user cancels, open URL
~~~csv
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-cancel=my_cancel_url
~~~
Shortcuts › run shortcut and on error, open URL<br><sub>Note: should be opened from outside Shortcuts app, otherwise the x-error URL may fail to load</sub>
~~~csv
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-error=my_error_url
~~~
Shortcuts › open shortcut ‘example’
~~~csv
shortcuts://open-shortcut?name=example
~~~
Shortcuts › create new shortcut
~~~csv
shortcuts://create-shortcut
~~~
Shortcuts ${\sf\small\color{DeepSkyBlue} iOS}$ › create new automation
~~~csv
shortcuts://create-automation
~~~
Shortcuts ${\sf\small\color{DeepSkyBlue} iOS}$ › Automations
~~~csv
shortcuts://automations
~~~
Shortcuts › Gallery
~~~csv
shortcuts://gallery
~~~
Shortcuts › install shortcut using ID from iCloud URL
~~~csv
shortcuts://shortcuts/replace_with_id_from_icloud_url
~~~
System Settings ${\sf\small\color{DeepSkyBlue} macOS}$
~~~csv
x-apple.systempreferences://
~~~
Tips
~~~csv
x-apple-tips://
~~~
Voice Memos ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
voicememos://
~~~
Wallet ${\sf\small\color{DeepSkyBlue} iOS}$
~~~csv
wallet://
~~~
Weather
~~~csv
weather://
~~~
Web App ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>If you only have a single web app installed/web page added to your Home Screen, this URL will open that one, otherwise it's unpredictable what it opens</sub>
~~~csv
webapp://
~~~
<br>
<br>
<br>
