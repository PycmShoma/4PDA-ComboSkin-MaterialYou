# Notes
- According to the rules of the 4PDA resource, the public release of client app modifications is prohibited, but no one forbids using it only for yourself
- To decompile applications, use any convenient apktool for you and your device architecture

`RUS`
- По правилам ресурса 4PDA публичный выпуск модификаций клиента запрещен, но никто не запрещает вам использовать его только для себя
- Для декомпиляции приложения используйте любой подходящий для вас и вашей архитектуры apktool

#
#

## To separate the favorites and mentions nav icons in drawer
- Add the ic_nav_men drawable resource as a bitmap or vector and edit /res/layout/mainactivity.xml in the **client app** itself

`RUS`

- Чтобы разделить иконки избранного и упоминаний в навигации создайте растровый либо векторный drawable ресурс ic_nav_men и отредактируйте /res/layout/mainactivity.xml в **приложении клиента форума**

`<TextView
    android:textSize="16sp"
    android:textColor="@color/main_text"
    android:gravity="center|left"
    android:layout_width="0dp"
    android:layout_height="match_parent"
    android:text="@string/nav_new_men"
    android:includeFontPadding="false"
    android:drawableLeft="@drawable/ic_nav_men"
    android:drawablePadding="8dp"
    android:layout_weight="1.0"
    android:lineSpacingExtra="0sp" />
`

#
#

## To add a monochrome app icon for A13
- Create or download a vector resource and put to /res/drawable on the **client app** and add the line to /res/mipmap-anydpi-v26/ic_launcher.xml and ic_launcher_round.xml with content:
penultimate line and add the line to /res/mipmap-anydpi-v26/ic_launcher.xml and ic_launcher_round.xml with content:
penultimate line

`RUS`
- Для добавления монохромной иконки для A13 создайте или скачайте векторную графику и посестите ее в /res/drawable **приложения клиента** и добавьте предпоследней строкой в /res/mipmap-anydpi-v26/ic_launcher.xml и ic_launcher_round.xml следующую строку:

`<monochrome android:drawable="@drawable/adaptive_monochrome_fourpda_launcher" />`

#
#

## To add a monochrome app shortcuts for A13
- Create or download a vector resources and put to /res/ on the **client app**

`RUS`
- Для добавления монохромных шорткатов создайте или скачайте векторную графику и поместите ее в /res **приложения клиента** 