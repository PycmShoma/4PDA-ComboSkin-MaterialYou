## MaterialYou (Monet) ComboSkin for [4PDA](https://4pda.to/forum/index.php?showtopic=673755) forum app
#
<img src="https://img.shields.io/badge/minSdk-31-blue?longCache=true&style=flat">

<img src="https://img.shields.io/badge/Build%20Project-blue?longCache=true&logo=github&labelColor=blue&style=flat">

`ENG`
You can build this project on desktop with Android Studio or on Android device with AIDE - Android IDE - Java, C++

`RUS`
Вы можете собрать данный проект на декстопе в Android Studio либо на устройстве с Android OS с помощью AIDE - Android IDE - Java, C++ 

#
#

<img src="https://img.shields.io/badge/Troubleshooting-blue?longCache=true&logo=github&labelColor=blue&style=flat">

`ENG`
If you building a project in AIDE - Android IDE - Java, C++
Remove implemention `testImplementation 'junit:junit:4.12'` in build.gradle

`RUS`
Если при сборке проекта в AIDE - Android IDE - Java, C++
Удалите зависмость `testImplementation 'junit:junit:4.12'` в build.gradle

#
#

`ENG`
If when building a project in AIDE - Android IDE - Java, C++ you get an error on the color code:
`@android:color/system_neutral1_50`
`@android:color/system_neutral1_900`
`@android:color/system_accent1_500`

replace this code with a color in hex format. After building the project, you can decompile the application into apktool and return the values ​​in place

`<color name="brend">@android:color/system_neutral1_50</color>`

`<color name="zn_brend">@android:color/system_neutral1_900</color>`

`<color name="selected_bg">@android:color/system_accent1_500</color>`

`<color name="zn_selected_bg">@android:color/system_accent1_500</color>`

`RUS`
Если при сборке проекта в AIDE - Android IDE - Java, C++ вы получили ошибку по коду цвета:
`@android:color/system_neutral1_50`
`@android:color/system_neutral1_900`
`@android:color/system_accent1_500`

замените этот код на цвет в hex формате. После сборки проекта вы можете декомпилировать приложение в apktool и вернуть значения на место:
`<color name="brend">@android:color/system_neutral1_50</color>`

`<color name="zn_brend">@android:color/system_neutral1_900</color>`

`<color name="selected_bg">@android:color/system_accent1_500</color>`

`<color name="zn_selected_bg">@android:color/system_accent1_500</color>`

#
#

<a href="https://github.com/PycmShoma/4PDA-DarkMaterialYou-Skin/blob/master/assets/screenshots.md"><img src="https://img.shields.io/badge/Screenshots-blue?longCache=true&logo=github&labelColor=blue&style=flat"> </a>

