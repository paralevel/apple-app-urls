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
_Apple Configurator <sup><sup>__macOS__</sup></sup>_
~~~yaml
configurator://
~~~
_Apps <sup><sup>__macOS__</sup></sup>_
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
_Calendar <sup><sup>__iOS__</sup></sup>_
~~~yaml
calshow://
~~~
_Calendar <sup><sup>__macOS__</sup></sup>_
~~~yaml
ical://
~~~
_Calendar – add subscription calendar_
~~~yaml
webcal://
~~~
_Camera <sup><sup>__iOS__</sup></sup>_
~~~yaml
camera://
~~~
_Camera <sup><sup>__iOS__</sup></sup> – take photo with back camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=back
~~~
_Camera <sup><sup>__iOS__</sup></sup> – take photo with front camera_
~~~yaml
camera://configuration?capturemode=photo&capturedevice=front
~~~
_Camera <sup><sup>__iOS__</sup></sup> – shoot video with back camera_
~~~yaml
camera://configuration?capturemode=video&capturedevice=back
~~~
_Camera <sup><sup>__iOS__</sup></sup> – shoot video with front camera_
~~~yaml
camera://configuration?capturemode=video&capturedevice=front
~~~
_Clock_
~~~yaml
clock-worldclock://
~~~
_Contacts <sup><sup>__iOS__</sup></sup>_
~~~yaml
contact://
~~~
_Contacts <sup><sup>__macOS__</sup></sup>_
~~~yaml
addressbook://
~~~
_Dictionary <sup><sup>__macOS__</sup></sup>_
~~~yaml
dict://
~~~
_Dictionary <sup><sup>__macOS__</sup></sup> – search for 'example'_
~~~yaml
dict://example
~~~
_FaceTime_
~~~yaml
facetime://
~~~
_Files <sup><sup>__iOS__</sup></sup>_
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
_Finder <sup><sup>__macOS__</sup></sup>_
~~~yaml
file:///Users/Shared
~~~
_Fitness <sup><sup>__iOS__</sup></sup>_
~~~yaml
fitnessapp://
~~~
_Font Book <sup><sup>__macOS__</sup></sup>_
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
_Health <sup><sup>__iOS__</sup></sup>_
~~~yaml
x-argonaut-app://
~~~
_iTunes Store <sup><sup>__iOS__</sup></sup>_
~~~yaml
itms://
~~~
_Journal_
~~~yaml
moments://
~~~
_Keynote <sup><sup>__macOS__</sup></sup>_
~~~yaml
com.apple.iwork.keynote-share://
~~~
_Magnifier <sup><sup>__iOS__</sup></sup>_
~~~yaml
apple-magnifier://
~~~
_Mail <sup><sup>__iOS__</sup></sup>_
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
_Notes <sup><sup>__iOS__</sup></sup> – create new note_
~~~yaml
mobilenotes://newNote
~~~
_Notes <sup><sup>__macOS__</sup></sup> – create new note_
~~~yaml
notes://newNote?displayMode=paper
~~~
_Numbers <sup><sup>__macOS__</sup></sup>_
~~~yaml
com.apple.iwork.numbers-share://
~~~
_Pages <sup><sup>__macOS__</sup></sup>_
~~~yaml
com.apple.iwork.pages-share://
~~~
_Passwords_
~~~yaml
apple-otpauth://
~~~
_Phone <sup><sup>__macOS__</sup></sup>_
~~~yaml
phoneapp://
~~~
_Phone <sup><sup>__iOS__</sup></sup> > Favorites (only works in Classic mode)_
~~~yaml
mobilephone-favorites://
~~~
_Phone <sup><sup>__iOS__</sup></sup> > Calls (Unified mode) or Recents (Classic mode)_
~~~yaml
mobilephone-recents://
~~~
_Phone <sup><sup>__iOS__</sup></sup> > Contacts_
~~~yaml
mobilephone-contacts://
~~~
_Phone <sup><sup>__iOS__</sup></sup> > Keypad_
~~~yaml
mobilephone-keypad://
~~~
_Photos_
~~~yaml
photos://
~~~
_Photos <sup><sup>__iOS__</sup></sup> > Library (tab)_
~~~yaml
photos://library
~~~
_Photos <sup><sup>__iOS__</sup></sup> > Collections (tab)_
~~~yaml
photos://collections
~~~
_Photos <sup><sup>__iOS__</sup></sup> – search for 'example'_
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
_Photos <sup><sup>__iOS__</sup></sup> > Featured Photos_
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
_Safari <sup><sup>__iOS__</sup></sup> – search for 'example' on DuckDuckGo_
~~~yaml
x-web-search://duckduckgo/?example
~~~
_Safari <sup><sup>__iOS__</sup></sup> – search for 'example' on Google_
~~~yaml
x-web-search://google/?example
~~~
_Safari <sup><sup>__iOS__</sup></sup> – search for 'example' on Bing_
~~~yaml
x-web-search://bing/?example
~~~
_Safari <sup><sup>__iOS__</sup></sup> – search for 'example' on Yahoo_
~~~yaml
x-web-search://yahoo/?example
~~~
_Safari <sup><sup>__iOS__</sup></sup> – search for 'example' on Ecosia_
~~~yaml
x-web-search://ecosia/?example
~~~
_Safari <sup><sup>__iOS__</sup></sup> – search for 'example' on Wikipedia_
~~~yaml
x-web-search://wikipedia/?example
~~~
_Settings <sup><sup>__iOS__</sup></sup>_
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
_Shortcuts <sup><sup>__iOS__</sup></sup> – run shortcut 'example' with the clipboard as input_
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
_Shortcuts <sup><sup>__iOS__</sup></sup> – create new automation_
~~~yaml
shortcuts://create-automation
~~~
_Shortcuts <sup><sup>__iOS__</sup></sup> > Automations_
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
_System Settings <sup><sup>__macOS__</sup></sup>_
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
_Voice Memos <sup><sup>__iOS__</sup></sup>_
~~~yaml
voicememos://
~~~
_Wallet <sup><sup>__iOS__</sup></sup>_
~~~yaml
wallet://
~~~
_Watch <sup><sup>__iOS__</sup></sup>_
~~~yaml
bridge://
~~~
_Watch > Face Gallery <sup><sup>__iOS__</sup></sup>_
~~~yaml
facegallery://
~~~
_Weather_
~~~yaml
weather://
~~~
_Web App <sup><sup>__iOS__</sup></sup> – opens the earliest installed web app if there is any, otherwise a blank screen is shown_
~~~yaml
webapp://
~~~
