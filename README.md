# Apple app URL schemes for iOS 26 and macOS 26 Tahoe

\
_App Store_
~~~yaml
itms-apps://?action=today
~~~
_App Store > Updates_
~~~yaml
itms-apps://?action=updates
~~~
_App Store > Safari Extensions_
~~~yaml
itms-apps://safariExtensions
~~~
_App Store – search for 'example'_
~~~yaml
itms-apps://?action=search&term=example
~~~
_Apple Configurator <sup>[macOS]</sup>_
~~~yaml
configurator://
~~~
_Apps <sup>[macOS]</sup>_
~~~yaml
spotlight://apps
~~~
_Books_
~~~yaml
ibooks://
~~~
_Calculator_
~~~yaml
calc://
~~~
_Calendar <sup>[iOS]</sup>_
~~~yaml
calshow://
~~~
_Calendar <sup>[macOS]</sup>_
~~~yaml
ical://
~~~
_Calendar – add subscription calendar_
~~~yaml
webcal://
~~~
_Camera <sup>[iOS]</sup>_
~~~yaml
camera://
~~~
_Camera <sup>[iOS]</sup> – take photo with back camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=back
~~~
_Camera <sup>[iOS]</sup> – take photo with front camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=front
~~~
_Camera <sup>[iOS]</sup> – shoot video with back camera_
~~~yaml
camera://configuration?capturemode=video&capturedevice=back
~~~
_Camera <sup>[iOS]</sup> – shoot video with front camera_
~~~yaml
camera://configuration?capturemode=video&capturedevice=front
~~~
_Clock_
~~~yaml
clock-worldclock://
~~~
_Contacts <sup>[iOS]</sup>_
~~~yaml
contact://
~~~
_Contacts <sup>[macOS]</sup>_
~~~yaml
addressbook://
~~~
_Desk View <sup>[macOS]</sup>_
~~~yaml
deskcam://
~~~
_Dictionary <sup>[macOS]</sup>_
~~~yaml
dict://
~~~
_Dictionary <sup>[macOS]</sup> – search for 'example'_
~~~yaml
dict://example
~~~
_FaceTime_
~~~yaml
facetimeapp://
~~~
_FaceTime – call {contact name/phone number}_
~~~yaml
facetime://name_or_number
~~~
_Files <sup>[iOS]</sup>_
~~~yaml
shareddocuments://
~~~
_Find My_
~~~yaml
findmy://
~~~
_Find My > Find My Friends_
~~~yaml
findmyfriends://
~~~
_Finder <sup>[macOS]</sup>_
~~~yaml
file:///Users/Shared
~~~
_Font Book <sup>[macOS]</sup>_
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
_Home <sup>[iOS]</sup>_
~~~yaml
com.apple.home://
~~~
_Home <sup>[iOS]</sup> > Climate_
~~~yaml
com.apple.home://accessorytype/climate
~~~
_Home <sup>[iOS]</sup> > Lights_
~~~yaml
com.apple.home://accessorytype/lights
~~~
_Home <sup>[iOS]</sup> > Security_
~~~yaml
com.apple.home://accessorytype/security
~~~
_Home <sup>[iOS]</sup> > Home Settings > Recognize My Voice > Personal Content_
~~~yaml
com.apple.home://personalRequestOptIn
~~~
_iTunes Store <sup>[iOS]</sup>_
~~~yaml
itms://
~~~
_Journal_
~~~yaml
moments://
~~~
_Keynote <sup>[macOS]</sup>_
~~~yaml
com.apple.iwork.keynote-share://
~~~
_Magnifier <sup>[iOS]</sup>_
~~~yaml
apple-magnifier://
~~~
_Mail <sup>[iOS]</sup>_
~~~yaml
com.apple.mobilemail://
~~~
_Mail – compose new e-mail_
~~~yaml
mailto://
~~~
_Maps_
~~~yaml
maps://
~~~
_Messages_
~~~yaml
iChat://
~~~
_Messages – create new message_
~~~yaml
sms://
~~~
_Notes_
~~~yaml
applenotes://
~~~
_Notes <sup>[iOS]</sup> – create new note_
~~~yaml
mobilenotes://newNote
~~~
_Notes <sup>[macOS]</sup> – create new note_
~~~yaml
notes://newNote?displayMode=paper
~~~
_Numbers <sup>[macOS]</sup>_
~~~yaml
com.apple.iwork.numbers-share://
~~~
_Pages <sup>[macOS]</sup>_
~~~yaml
com.apple.iwork.pages-share://
~~~
_Panel Editor <sup>[macOS]</sup>_
~~~yaml
assistivecontrolpanels://
~~~
_Passwords_
~~~yaml
apple-otpauth://
~~~
_Phone <sup>[macOS]</sup>_
~~~yaml
phoneapp://
~~~
_Phone <sup>[iOS]</sup> > Favorites (only works in Classic mode)_
~~~yaml
mobilephone-favorites://
~~~
_Phone <sup>[iOS]</sup> > Calls (Unified mode) or Recents (Classic mode)_
~~~yaml
mobilephone-recents://
~~~
_Phone <sup>[iOS]</sup> > Contacts_
~~~yaml
mobilephone-contacts://
~~~
_Phone <sup>[iOS]</sup> > Keypad_
~~~yaml
mobilephone-keypad://
~~~
_Photos_
~~~yaml
photos://
~~~
_Photos <sup>[iOS]</sup> > Library (tab)_
~~~yaml
photos://library
~~~
_Photos <sup>[iOS]</sup> > Collections (tab)_
~~~yaml
photos://collections
~~~
_Photos <sup>[iOS]</sup> – search for 'example'_
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
_Photos <sup>[iOS]</sup> > Featured Photos_
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
_Podcasts_
~~~yaml
podcasts://
~~~
_Reminders_
~~~yaml
x-apple-reminderkit://
~~~
_Safari <sup>[iOS]</sup> – search for 'example' on DuckDuckGo_
~~~yaml
x-web-search://duckduckgo/?example
~~~
_Safari <sup>[iOS]</sup> – search for 'example' on Google_
~~~yaml
x-web-search://google/?example
~~~
_Safari <sup>[iOS]</sup> – search for 'example' on Bing_
~~~yaml
x-web-search://bing/?example
~~~
_Safari <sup>[iOS]</sup> – search for 'example' on Yahoo_
~~~yaml
x-web-search://yahoo/?example
~~~
_Safari <sup>[iOS]</sup> – search for 'example' on Ecosia_
~~~yaml
x-web-search://ecosia/?example
~~~
_Safari <sup>[iOS]</sup> – search for 'example' on Wikipedia_
~~~yaml
x-web-search://wikipedia/?example
~~~
_Script Editor <sup>[macOS]</sup>_
~~~yaml
applescript://
~~~
_Settings <sup>[iOS]</sup>_
~~~yaml
prefs://
~~~
_Shortcuts_
~~~yaml
shortcuts://
~~~
_Shortcuts – run shortcut 'example'_
~~~yaml
shortcuts://run-shortcut?name=example
~~~
_Shortcuts – run shortcut 'example' with 'my text' as input_
~~~yaml
shortcuts://run-shortcut?name=example&input=my%20text
~~~
_Shortcuts <sup>[iOS]</sup> – run shortcut 'example' with the clipboard as input_
~~~yaml
shortcuts://run-shortcut?name=example&input=clipboard
~~~
_Shortcuts – open shortcut 'example' <sub>(case-insensitive)</sub>_
~~~yaml
shortcuts://open-shortcut?name=example
~~~
_Shortcuts – create new shortcut_
~~~yaml
shortcuts://create-shortcut
~~~
_Shortcuts <sup>[iOS]</sup> – create new automation_
~~~yaml
shortcuts://create-automation
~~~
_Shortcuts <sup>[iOS]</sup> > Automations_
~~~yaml
shortcuts://automations
~~~
_Shortcuts > Gallery_
~~~yaml
shortcuts://gallery
~~~
_Shortcuts – install shortcut using ID from iCloud shortcut link_
~~~yaml
shortcuts://shortcuts/icloud_link_id
~~~
_Shortcuts `x-callback-url` with for example `create-shortcut`_
~~~yaml
shortcuts://x-callback-url/create-shortcut
~~~
_System Settings <sup>[macOS]</sup>_
~~~yaml
x-apple.systempreferences://
~~~
_Tips_
~~~yaml
x-apple-tips://
~~~
_Voice Memos <sup>[iOS]</sup>_
~~~yaml
voicememos://
~~~
_Wallet <sup>[iOS]</sup>_
~~~yaml
wallet://
~~~
_Watch <sup>[iOS]</sup>_
~~~yaml
bridge://
~~~
_Watch <sup>[iOS]</sup> > Face Gallery_
~~~yaml
facegallery://
~~~
_Weather_
~~~yaml
weather://
~~~
_Web App <sup>[iOS]</sup> – opens the earliest installed web app if there is any, otherwise a blank screen is shown_
~~~yaml
webapp://
~~~
