# freetuga-dist

Канал распространения обновлений плагина **FreeTuga** (`ru.freetuga.one`).

- `dist/latest.json` — манифест каналов `dev` / `beta` / `stable` (версия, versionCode, sha256, url).
  Плагин читает его по raw-ссылке:
  `https://raw.githubusercontent.com/altegotech/freetuga-dist/main/dist/latest.json`
- Сами APK (`freetugaone-x.x.x.apk`) публикуются в **Releases** этого репозитория; поле `url`
  в манифесте указывает на конкретный asset релиза.

Исходный код плагина — в приватном репозитории `altegotech/freetuga`.
