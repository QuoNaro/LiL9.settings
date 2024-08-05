# Настройка
## Установка AppOps и Shizuku
  ```sh
  adb install --user 0 -r ./apk/shizuku.apk
  adb install --user 0 -r ./apk/appops.apk
  ```

### Запуск Shizuku
   ```sh
   adb shell sh /storage/emulated/0/Android/data/moe.shizuku.privileged.api/start.sh
   ```


## Установка клавиатуры SwiftKey на передние экраны
  ```sh
  adb install --user 0 -r ./apk/swiftkey.apk
  adb install --user 21473 -r ./apk/swiftkey.apk
  ```
После этого нужно зайти в Swiftkey и настроить на главном экране. Потом начать настройку клавиатуры на втором экране. На этом этапе нужно перезагрузить машину. После включения автомобиля открываем Swiftkey на втором экране и завершаем настройку.

