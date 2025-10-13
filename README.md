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
_Apple Configurator <sup>(macOS)</sup>_
~~~yaml
configurator://
~~~
_Apps <sup>(macOS)</sup>_
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
_Calendar <sup>(iOS)</sup>_
~~~yaml
calshow://
~~~
_Calendar <sup>(macOS)</sup>_
~~~yaml
ical://
~~~
_Calendar – add subscription calendar_
~~~yaml
webcal://
~~~
_Camera <sup>(iOS)</sup>_
~~~yaml
camera://
~~~
_Camera – take photo with back camera <sup>(iOS)</sup>_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=back
~~~
_Camera – take photo with front camera <sup>(iOS)</sup>_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=front
~~~
_Camera – shoot video with back camera <sup>(iOS)</sup>_
~~~yaml
camera://configuration?capturemode=video&capturedevice=back
~~~
_Camera – shoot video with front camera <sup>(iOS)</sup>_
~~~yaml
camera://configuration?capturemode=video&capturedevice=front
~~~
_Clock_
~~~yaml
clock-worldclock://
~~~
_Contacts <sup>(iOS)</sup>_
~~~yaml
contact://
~~~
_Contacts <sup>(macOS)</sup>_
~~~yaml
addressbook://
~~~
_Dictionary <sup>(macOS)</sup>_
~~~yaml
dict://
~~~
_Dictionary – search for 'example' <sup>(macOS)</sup>_
~~~yaml
dict://example
~~~
_FaceTime_
~~~yaml
facetime://
~~~
_Files <sup>(iOS)</sup>_
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
_Finder <sup>(macOS)</sup>_
~~~yaml
file:///Users/Shared
~~~
_Fitness <sup>(iOS)</sup>_
~~~yaml
fitnessapp://
~~~
_Font Book <sup>(macOS)</sup>_
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
_Health <sup>(iOS)</sup>_
~~~yaml
x-argonaut-app://
~~~
_iTunes Store <sup>(iOS)</sup>_
~~~yaml
itms://
~~~
_Journal_
~~~yaml
moments://
~~~
_Keynote <sup>(macOS)</sup>_
~~~yaml
com.apple.iwork.keynote-share://
~~~
_Magnifier <sup>(iOS)</sup>_
~~~yaml
apple-magnifier://
~~~
_Mail <sup>(iOS)</sup>_
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
_Notes – create new note <sup>(iOS)</sup>_
~~~yaml
mobilenotes://newNote
~~~
_Notes – create new note <sup>(macOS)</sup>_
~~~yaml
notes://newNote?displayMode=paper
~~~
_Numbers <sup>(macOS)</sup>_
~~~yaml
com.apple.iwork.numbers-share://
~~~
_Pages <sup>(macOS)</sup>_
~~~yaml
com.apple.iwork.pages-share://
~~~
_Passwords_
~~~yaml
apple-otpauth://
~~~
_Phone <sup>(macOS)</sup>_
~~~yaml
phoneapp://
~~~
_Phone > Favorites (only works in Classic mode) <sup>(iOS)</sup>_
~~~yaml
mobilephone-favorites://
~~~
_Phone > Calls (Unified mode) or Recents (Classic mode) <sup>(iOS)</sup>_
~~~yaml
mobilephone-recents://
~~~
_Phone > Contacts <sup>(iOS)</sup>_
~~~yaml
mobilephone-contacts://
~~~
_Phone > Keypad <sup>(iOS)</sup>_
~~~yaml
mobilephone-keypad://
~~~
_Photos_
~~~yaml
photos://
~~~
_Photos > Library (tab) <sup>(iOS)</sup>_
~~~yaml
photos://library
~~~
_Photos > Collections (tab) <sup>(iOS)</sup>_
~~~yaml
photos://collections
~~~
_Photos – search for 'example' <sup>(iOS)</sup>_
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
_Photos > Featured Photos <sup>(iOS)</sup>_
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
_Safari – search for 'example' on DuckDuckGo <sup>(iOS)</sup>_
~~~yaml
x-web-search://duckduckgo/?example
~~~
_Safari – search for 'example' on Google <sup>(iOS)</sup>_
~~~yaml
x-web-search://google/?example
~~~
_Safari – search for 'example' on Bing <sup>(iOS)</sup>_
~~~yaml
x-web-search://bing/?example
~~~
_Safari – search for 'example' on Yahoo <sup>(iOS)</sup>_
~~~yaml
x-web-search://yahoo/?example
~~~
_Safari – search for 'example' on Ecosia <sup>(iOS)</sup>_
~~~yaml
x-web-search://ecosia/?example
~~~
_Safari – search for 'example' on Wikipedia <sup>(iOS)</sup>_
~~~yaml
x-web-search://wikipedia/?example
~~~
_Settings <sup>(iOS)</sup>_
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
_Shortcuts – run shortcut 'example' with the clipboard as input <sup>(iOS)</sup>_
~~~yaml
shortcuts://run-shortcut?name=example&input=clipboard
~~~
_Shortcuts – open shortcut 'example' <sup>(case-insensitive)</sup>_
~~~yaml
shortcuts://open-shortcut?name=example
~~~
_Shortcuts – create new shortcut_
~~~yaml
shortcuts://create-shortcut
~~~
_Shortcuts – create new automation <sup>(iOS)</sup>_
~~~yaml
shortcuts://create-automation
~~~
_Shortcuts > Automations <sup>(iOS)</sup>_
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
_System Settings <sup>(macOS)</sup>_
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
_Voice Memos <sup>(iOS)</sup>_
~~~yaml
voicememos://
~~~
_Wallet <sup>(iOS)</sup>_
~~~yaml
wallet://
~~~
_Watch <sup>(iOS)</sup>_
~~~yaml
bridge://
~~~
_Watch > Face Gallery_
~~~yaml
facegallery://
~~~
_Weather_
~~~yaml
weather://
~~~
_Web App <sup>(iOS)</sup>_
~~~yaml
webapp://
~~~
> _Opens the earliest installed web app if there is any, otherwise a blank screen is shown_
