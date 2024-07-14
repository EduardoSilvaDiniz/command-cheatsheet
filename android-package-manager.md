## comandos shell

| nome do aplicativo | nome do pacote                              |
|--------------------|---------------------------------------------|
| Play Store         | com.android.vending                         |
| Google Chrome      | com.android.chrome                          |
| Google Search      | com.google.android.googlequicksearchbox     |
| Clima              | com.miui.weather2                           |
| Bússola            | com.miui.compass                            |
| Galeria            | com.miui.gallery                            |
| Radio.fm           | com.miui.fm                                 |
| ???                | com.miui.secury                             |
| ???                | com.android.mms                             |
| ???                | com.miui.securitycore                       |
| ???                | com.miui.securitycenter                     |
| Galeria            | com.android.calendar                        |
| Galeria            | com.xiaomi.calendar                         |

## para procurar o nome do app procure no site da playstore, a url contem o nome do app
adb shell pm disable-user --user 0 NomeDoPackage
adb shell pm enable NomeDoPackage

## exemplo: https://play.google.com/store/apps/details?id=com.microsoft.emmx 
## (com.microsoft.emmx) nome do app

## entrar no shell do celular (depuração precisa esta ativada)
adb devices # seu dispositivo deve aparece e com "attached" device
adb shell   # entrar no shell
