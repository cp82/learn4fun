# ![logo](http://i.imgur.com/1TnaivW.png)
# Learn 4 Fun public translation project

## Introduction

This repository contains the translation for my app [Learn 4 Fun](https://play.google.com/store/apps/details?id=com.cpu82.learn4fun).

Learn 4 Fun works like a screen lock. Before accessing the apps or games on the phone or tablet, your kids have to solve some math exercises first and are rewarded with play time.

Once time is up, access will be locked and the exercise screen appears again.


Learn 4 Fun is not a kids mode! Access to apps and internet is not restricted.


## How to contribute

You can help making this app better by contributing to your local translation.

Your work will be credited in the app's about page:
![alt text](http://imgur.com/9VIn4o6.png)

### Prerequisites

You need a github account to make contributions to a project on github.


### Editing directly on github

1. Got to the res/values-xx folder for your language and open the strings.xml file.

2. Enter editor mode by clicking the pencil icon

3. Edit the text within the xml start and end tags

Example:
```xml
<string name="title_translation">English translation</string>
```
In German, this string becomes
```xml
<string name="title_translation">Deutsche Übersetzung</string>
```
If you want to get credits in the app's about page, enter your name or nickname to the following string, separated by the newline character ('\n')
```xml
<string name="translators">cpu82\nYour name</string>
```

4. If you are done with your changes, you can create a so called pull-request by clicking "Propose file change".

5. After I have reviewed and merged your changes, I will create a new app version including your translation.

### Editing a local copy on your computer
 
If you want don't want to use the web editor, you can also create a fork and checkout your local copy.
Please read this [guide](https://guides.github.com/activities/forking/) for more information.

### Play Store Entry

Please also translate the Play Store entry to your language.
You find the template in the folder "PlayStoreEntry" under "yourlanguage.txt".

## Languages and country codes

### Done
* English, US - en-US
* German - de
* Italian - it
* Japanese - ja

### Needs translation
* Afrikaans - af
* Arabic - ar
* Belarusian - be
* Burmese - my
* Catalan - ca
* Chinese simplified - zh-CN
* Chinese traditional - zh-TW
* Croatian - hr
* Czech - cs
* Danish - da
* Dutch - nl
* Estonian - et
* Filipino - fil-PH
* Finnish - fi
* French - fr
* Greek - el
* Hebrew - he
* Hindi - hi
* Hungarian - hu
* Indonesian - in
* Korean - ko
* Latvian - lv
* Lithuanian - lt
* Malay - ms
* Norwegian - nb
* Persian - fa
* Polish - pl
* Portuguese, Brazilian - pt-BR
* Portuguese - pt-PT 
* Romanian - ro
* Russian - ru
* Serbian (Cyrillic) - sr
* Slovak - sk
* Slovenian - sl
* Spanish - es-ES
* Swedish - sv-SE
* Tagalog - tl-PH
* Thai - th
* Turkish - tr
* Ukrainian - uk
* Vietnamese - vi



If your language is missing or you need help with github, please send a message to cpu82@gmx.net
