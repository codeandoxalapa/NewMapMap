# Instrucciones para el desarrollo de la aplicacion usando react-native

1. Follow the instructions https://facebook.github.io/react-native/docs/getting-started.html

# Problemas conocidos

En Ubuntu puede que se necesite instalar lib32stdc++6 lib32z1 para poder ejecutar la aplicación http://stackoverflow.com/questions/42594966/android-studio-2-3-errorjava-util-concurrent-executionexception-java-lang-runt

Puede que necesites actualizar a la version 23.0.3 de gradle http://stackoverflow.com/questions/39773326/gradle-on-android-studio-loading-with-error

Si marca error could not get BatchedBridge al lanzar la aplicacion prueba ejecutando adb reverse tcp:8081 tcp:8081

Si la maquina virtual en AVD no se ejecuta prueba estableciendo menos RAM, al menos 1GB recomendado y en Emulated Performance poner la opcion Graphics -> Software GLES
