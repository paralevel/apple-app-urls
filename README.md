# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

<br>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs that have been copied from outside sources_</sup>

<br>
<br>

Accessibility Reader ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
apple-axreader://
~~~
App Store
~~~yaml
itms-apps://?action=today
~~~
App Store › Updates
~~~yaml
itms-apps://?action=updates
~~~
App Store › search for ‘example’
~~~yaml
itms-apps://?action=search&term=example
~~~
App Store › Safari Extensions
~~~yaml
itms-apps://safariExtensions
~~~
App Store › Apps for Wallet
~~~yaml
itms-apps://?action=passbook
~~~
App Store ${\sf\small\color{DeepSkyBlue} iOS}$ › Trending › “Great apps to try with SharePlay”
~~~yaml
itms-apps://sharePlayApps
~~~
Apple Configurator ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
configurator://
~~~
Apps ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
spotlight://apps
~~~
Calculator
~~~yaml
calc://
~~~
Calendar ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
calshow://
~~~
Calendar ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
ical://
~~~
Calendar › add subscription calendar
~~~yaml
webcal://
~~~
Calendar ${\sf\small\color{DeepSkyBlue} iOS}$ › calendars
~~~yaml
calshow://familyCalendar
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
camera://
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › photo mode
~~~yaml
camera://configuration?capturemode=photo&capturedevice=back
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › video mode
~~~yaml
camera://configuration?capturemode=video&capturedevice=back
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › photo mode with front-facing camera
~~~yaml
camera://configuration?capturemode=photo&capturedevice=front
~~~
Camera ${\sf\small\color{DeepSkyBlue} iOS}$ › video mode with front-facing camera
~~~yaml
camera://configuration?capturemode=video&capturedevice=front
~~~
Clock
~~~yaml
clock-worldclock://
~~~
Contacts
~~~yaml
contacts-sensitive://
~~~
Contacts ${\sf\small\color{DeepSkyBlue} iOS}$ › List › Other Known
~~~yaml
contacts-sensitive:///list/other-known
~~~
Desk View ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
deskcam://
~~~
Dictionary ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
dict://
~~~
Dictionary ${\sf\small\color{DeepSkyBlue} macOS}$ › search for ‘example’
~~~yaml
dict://example
~~~
FaceTime
~~~yaml
facetimeapp://
~~~
FaceTime › call [contact name/phone number]
~~~yaml
facetime://replace_with_name_or_number
~~~
Feedback Assistant
~~~yaml
applefeedback://
~~~
Feedback Assistant › New Feedback
~~~yaml
applefeedback://new
~~~
Files ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
shareddocuments://
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Recents
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › iCloud Drive
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/iCloud%20Drive.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › AirDrop
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/AirDrop.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › [current Mac]
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Computer.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Network
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Applications/Network.app
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Shared
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedDocuments.cannedSearch
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Shared By Me
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedByMe.cannedSearch	
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › Shared With Me
~~~yaml
file:///System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/SharedWithMe.cannedSearch
~~~
Finder ${\sf\small\color{DeepSkyBlue} macOS}$ › /Users/Shared
~~~yaml
file:///Users/Shared
~~~
Font Book ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
fontbook://
~~~
Freeform
~~~yaml
freeform://
~~~
Games
~~~yaml
games://
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
com.apple.home://
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Climate
~~~yaml
com.apple.home://accessorytype/climate
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Lights
~~~yaml
com.apple.home://accessorytype/lights
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Security
~~~yaml
com.apple.home://accessorytype/security
~~~
Home ${\sf\small\color{DeepSkyBlue} iOS}$ › Home Settings › Recognize My Voice › Personal Content
~~~yaml
com.apple.home://personalRequestOptIn
~~~
Journal
~~~yaml
moments://
~~~
Keynote ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
com.apple.iwork.keynote-share://
~~~
Magnifier ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
apple-magnifier://
~~~
Mail ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
com.apple.mobilemail://
~~~
Mail › new email
~~~yaml
mailto://
~~~
Mail › new email with recipient included
~~~yaml
mailto:someone@example.com
~~~
Mail › new email with multiple recipients included
~~~yaml
mailto:someone@example.com,another@example.com
~~~
Mail › new email with recipient included, using the ‘Name <user</span>@domain.tld>’ form
~~~yaml
mailto:Someone%20%3Csomeone@example.com%3E
~~~
Mail › new email with main and Cc recipients included
~~~yaml
mailto:someone@example.com?cc=another@example.com
~~~
Mail › new email with main, Cc and Bcc recipients included
~~~yaml
mailto:someone@example.com?cc=another@example.com&bcc=different@example.com
~~~
Mail › new email with recipient and subject included
~~~yaml
mailto:someone@example.com?subject=Some%20subject
~~~
Mail › new email with recipient and content included
~~~yaml
mailto:someone@example.com?body=Some%20message
~~~
Mail › new email with recipient, subject and content included
~~~yaml
mailto:someone@example.com?subject=Some%20subject&body=Some%20message
~~~
Maps
~~~yaml
maps://
~~~
Messages
~~~yaml
iChat://
~~~
Messages › new message
~~~yaml
sms://
~~~
Messages › new message to phone number ‘12345’
~~~yaml
sms:12345
~~~
Messages › new message to phone numbers ‘12345’ and ‘67890’
~~~yaml
sms:?addresses=12345,67890
~~~
Messages › new message with content included
~~~yaml
sms:?body=My%20URL%20encoded%20message
~~~
Messages › new message with content included to phone number ‘12345’
~~~yaml
sms:12345?body=My%20URL%20encoded%20message
~~~
Messages › new message with content included to phone numbers ‘12345’ and ‘67890’
~~~yaml
sms:?addresses=12345,67890&body=My%20URL%20encoded%20message
~~~
Notes
~~~yaml
applenotes://
~~~
Notes ${\sf\small\color{DeepSkyBlue} iOS}$ › create new note
~~~yaml
mobilenotes://newNote
~~~
Notes ${\sf\small\color{DeepSkyBlue} macOS}$ › create new note
~~~yaml
notes://newNote?displayMode=paper
~~~
Numbers ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
com.apple.iwork.numbers-share://
~~~
Pages ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
com.apple.iwork.pages-share://
~~~
Panel Editor ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
assistivecontrolpanels://
~~~
Passwords
~~~yaml
otpauth-migration://
~~~
Phone ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
phoneapp://
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
mobilephone-recents://
~~~
Phone › call phone number ‘12345’
~~~yaml
tel:12345
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$ › Keypad
~~~yaml
mobilephone-keypad://
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$ › Contacts
~~~yaml
mobilephone-contacts://
~~~
Phone ${\sf\small\color{DeepSkyBlue} iOS}$ › Favorites (only available in Classic mode)
~~~yaml
mobilephone-favorites://
~~~
Photos
~~~yaml
photos://
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › Library (tab)
~~~yaml
photos://library
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › Collections (tab)
~~~yaml
photos://collections
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’
~~~yaml
photos-navigation://search?searchTerm=example
~~~
Photos › most recent photo
~~~yaml
photos://lastasset
~~~
Photos › Recently Saved
~~~yaml
photos://album?name=recently-saved
~~~
Photos › Recently Deleted
~~~yaml
photos://album?name=recently-deleted
~~~
Photos › Favorites
~~~yaml
photos://album?name=favorites
~~~
Photos ${\sf\small\color{DeepSkyBlue} iOS}$ › Featured Photos
~~~yaml
photos://featuredPhoto
~~~
Photos › Duplicates
~~~yaml
photos://album?name=duplicates
~~~
Photos › Memories
~~~yaml
photos://memory-generation
~~~
Photos › People & Pets
~~~yaml
photos://people
~~~
Photos › Maps
~~~yaml
photos://places
~~~
Photos ${\sf\small\color{DeepSkyBlue} macOS}$ › Preferences › General
~~~yaml
photos://preferences/general
~~~
Photos ${\sf\small\color{DeepSkyBlue} macOS}$ › Preferences › iCloud
~~~yaml
photos://preferences/icloud
~~~
Photos ${\sf\small\color{DeepSkyBlue} macOS}$ › Preferences › Shared Library
~~~yaml
photos://preferences/shared-library
~~~
Reminders
~~~yaml
x-apple-reminderkit://
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on DuckDuckGo
~~~yaml
x-web-search://duckduckgo/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Google
~~~yaml
x-web-search://google/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Bing
~~~yaml
x-web-search://bing/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Yahoo
~~~yaml
x-web-search://yahoo/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Ecosia
~~~yaml
x-web-search://ecosia/?example
~~~
Safari ${\sf\small\color{DeepSkyBlue} iOS}$ › search for ‘example’ on Wikipedia
~~~yaml
x-web-search://wikipedia/?example
~~~
Script Editor ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
applescript://
~~~
Settings ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
prefs://
~~~
Shortcuts
~~~yaml
shortcuts://
~~~
Shortcuts › run shortcut ‘example’
~~~yaml
shortcuts://run-shortcut?name=example
~~~
Shortcuts › run shortcut ‘example’ with ‘my text’ as input
~~~yaml
shortcuts://run-shortcut?name=example&input=my%20text
~~~
Shortcuts ${\sf\small\color{DeepSkyBlue} iOS}$ › run shortcut ‘example’ with the clipboard as input
~~~yaml
shortcuts://run-shortcut?name=example&input=clipboard
~~~
Shortcuts › run shortcut and on success, open URL
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-success=my_success_url
~~~
Shortcuts › run shortcut and if the user cancels, open URL
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-cancel=my_cancel_url
~~~
Shortcuts › run shortcut and on error, open URL<br><sub>Note: should be opened from outside Shortcuts app, otherwise the x-error URL may fail to load</sub>
~~~yaml
shortcuts://x-callback-url/run-shortcut?name=My%20Shortcut&x-error=my_error_url
~~~
Shortcuts › open shortcut ‘example’
~~~yaml
shortcuts://open-shortcut?name=example
~~~
Shortcuts › create new shortcut
~~~yaml
shortcuts://create-shortcut
~~~
Shortcuts ${\sf\small\color{DeepSkyBlue} iOS}$ › create new automation
~~~yaml
shortcuts://create-automation
~~~
Shortcuts ${\sf\small\color{DeepSkyBlue} iOS}$ › Automations
~~~yaml
shortcuts://automations
~~~
Shortcuts › Gallery
~~~yaml
shortcuts://gallery
~~~
Shortcuts › install shortcut using ID from iCloud URL
~~~yaml
shortcuts://shortcuts/replace_with_id_from_icloud_url
~~~
System Settings ${\sf\small\color{DeepSkyBlue} macOS}$
~~~yaml
x-apple.systempreferences://
~~~
Tips
~~~yaml
x-apple-tips://
~~~
Voice Memos ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
voicememos://
~~~
Wallet ${\sf\small\color{DeepSkyBlue} iOS}$
~~~yaml
wallet://
~~~
Weather
~~~yaml
weather://
~~~
Web App ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>If you only have a single web app installed/web page added to your Home Screen, this URL will open that one, otherwise it's unpredictable what it opens</sub>
~~~yaml
webapp://
~~~
<br>
<br>
<br>
