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
_Apple Configurator <sub>(macOS)</sub>_
~~~yaml
configurator://
~~~
_Apps <sub>(macOS)</sub>_
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
_Calendar <sub>(iOS)</sub>_
~~~yaml
calshow://
~~~
_Calendar <sub>(macOS)</sub>_
~~~yaml
ical://
~~~
_Calendar – add subscription calendar_
~~~yaml
webcal://
~~~
_Camera <sub>(iOS)</sub>_
~~~yaml
camera://
~~~
_Camera <sub>(iOS)</sub> – take photo with back camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=back
~~~
_Camera <sub>(iOS)</sub> – take photo with front camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=front
~~~
_Camera <sub>(iOS)</sub> – shoot video with back camera_
~~~yaml
camera://configuration?capturemode=video&capturedevice=back
~~~
_Camera <sub>(iOS)</sub> – shoot video with front camera_
~~~yaml
camera://configuration?capturemode=video&capturedevice=front
~~~
_Clock_
~~~yaml
clock-worldclock://
~~~
_Contacts <sub>(iOS)</sub>_
~~~yaml
contact://
~~~
_Contacts <sub>(macOS)</sub>_
~~~yaml
addressbook://
~~~
_Dictionary <sub>(macOS)</sub>_
~~~yaml
dict://
~~~
_Dictionary <sub>(macOS)</sub> – search for 'example'_
~~~yaml
dict://example
~~~
_FaceTime_
~~~yaml
facetime://
~~~
_Files <sub>(iOS)</sub>_
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
_Finder <sub>(macOS)</sub>_
~~~yaml
file:///Users/Shared
~~~
_Fitness <sub>(iOS)</sub>_
~~~yaml
fitnessapp://
~~~
_Font Book <sub>(macOS)</sub>_
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
_Health <sub>(iOS)</sub>_
~~~yaml
x-argonaut-app://
~~~
_iTunes Store <sub>(iOS)</sub>_
~~~yaml
itms://
~~~
_Journal_
~~~yaml
moments://
~~~
_Keynote <sub>(macOS)</sub>_
~~~yaml
com.apple.iwork.keynote-share://
~~~
_Magnifier <sub>(iOS)</sub>_
~~~yaml
apple-magnifier://
~~~
_Mail <sub>(iOS)</sub>_
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
_Music_
~~~yaml
music://
~~~
_Notes_
~~~yaml
applenotes://
~~~
_Notes <sub>(iOS)</sub> – create new note_
~~~yaml
mobilenotes://newNote
~~~
_Notes <sub>(macOS)</sub> – create new note_
~~~yaml
notes://newNote?displayMode=paper
~~~
_Numbers <sub>(macOS)</sub>_
~~~yaml
com.apple.iwork.numbers-share://
~~~
_Pages <sub>(macOS)</sub>_
~~~yaml
com.apple.iwork.pages-share://
~~~
_Passwords_
~~~yaml
apple-otpauth://
~~~
_Phone <sub>(macOS)</sub>_
~~~yaml
phoneapp://
~~~
_Phone <sub>(iOS)</sub> > Favorites (only works in Classic mode)_
~~~yaml
mobilephone-favorites://
~~~
_Phone <sub>(iOS)</sub> > Calls (Unified mode) or Recents (Classic mode)_
~~~yaml
mobilephone-recents://
~~~
_Phone <sub>(iOS)</sub> > Contacts_
~~~yaml
mobilephone-contacts://
~~~
_Phone <sub>(iOS)</sub> > Keypad_
~~~yaml
mobilephone-keypad://
~~~
_Photos_
~~~yaml
photos://
~~~
_Photos <sub>(iOS)</sub> > Library (tab)_
~~~yaml
photos://library
~~~
_Photos <sub>(iOS)</sub> > Collections (tab)_
~~~yaml
photos://collections
~~~
_Photos <sub>(iOS)</sub> – search for 'example'_
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
_Photos <sub>(iOS)</sub> > Featured Photos_
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
_Safari <sub>(iOS)</sub> – search for 'example' on DuckDuckGo_
~~~yaml
x-web-search://duckduckgo/?example
~~~
_Safari <sub>(iOS)</sub> – search for 'example' on Google_
~~~yaml
x-web-search://google/?example
~~~
_Safari <sub>(iOS)</sub> – search for 'example' on Bing_
~~~yaml
x-web-search://bing/?example
~~~
_Safari <sub>(iOS)</sub> – search for 'example' on Yahoo_
~~~yaml
x-web-search://yahoo/?example
~~~
_Safari <sub>(iOS)</sub> – search for 'example' on Ecosia_
~~~yaml
x-web-search://ecosia/?example
~~~
_Safari <sub>(iOS)</sub> – search for 'example' on Wikipedia_
~~~yaml
x-web-search://wikipedia/?example
~~~
_Settings <sub>(iOS)</sub>_
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
_Shortcuts <sub>(iOS)</sub> – run shortcut 'example' with the clipboard as input_
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
_Shortcuts <sub>(iOS)</sub> – create new automation_
~~~yaml
shortcuts://create-automation
~~~
_Shortcuts <sub>(iOS)</sub> > Automations_
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
_Stocks_
~~~yaml
stocks://
~~~
_System Settings <sub>(macOS)</sub>_
~~~yaml
x-apple.systempreferences://
~~~
_Tips_
~~~yaml
x-apple-tips://
~~~
_TV_
~~~yaml
videos://
~~~
_Voice Memos <sub>(iOS)</sub>_
~~~yaml
voicememos://
~~~
_Wallet <sub>(iOS)</sub>_
~~~yaml
wallet://
~~~
_Watch <sub>(iOS)</sub>_
~~~yaml
bridge://
~~~
_Watch > Face Gallery <sub>(iOS)</sub>_
~~~yaml
facegallery://
~~~
_Weather_
~~~yaml
weather://
~~~
_Web App <sub>(iOS)</sub> – opens the earliest installed web app if there is any, otherwise a blank screen is shown_
~~~yaml
webapp://
~~~
