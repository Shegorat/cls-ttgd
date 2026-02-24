# cls-ttgd

**cls-ttgd** — декриптор для *ttarch* архивов игр компании Telltale Games.

---

## 📦 Опции

| Параметр | Описание |
| -------- | -------- |
| `game=<game_id>` | Номер ключа для дешифровки |
| `ver=<version>` | Версия алгоритма (используется вместе с `key`) |
| `key=<key>` | Ключ в hex-виде для дешифровки |
| `strict` | Включает строгую проверку заголовков архивов, бросает ошибку вместо пропуска файлов |
| `t=<thread_count>` | Количество рабочих потоков |
| `r` | Рекомпрессия блоков (пока поддерживается только `deflate`) |

**Примечания:**
- Опции можно указывать без знака `=` (например: `game42`).
- Можно положить рядом `zlib.dll` / `zlib64.dll` для рекомпрессии — библиотека будет автоматически подхвачена.

---

## ⚙️ Настройки через `cls.ini`

| Параметр | Описание |
| -------- | -------- |
| `ThreadCount=<thread_count>` | Количество рабочих потоков (переопределяет опцию `t`) |

**Пример:**

```ini
[ttgd]
ThreadCount=50%
```

## 🗝️ Список ключей:
| Код ключа | Название игры |
| ------ | ------ |
| 0  | Wallace & Gromit: Episode 1: Fright of the Bumblebees |
| 1  | Wallace & Gromit: Episode 2: The Last Resort |
| 2  | Wallace & Gromit: Episode 3: Muzzled |
| 3  | Telltale Texas Hold'em |
| 4  | Bone: Out From Boneville |
| 5  | Bone: The Great Cow Race |
| 6  | Sam & Max: Episode 101 - Culture Shock |
| 7  | Sam & Max: Episode 102 - Situation: Comedy |
| 8  | Sam & Max: Episode 103 - The Mole, The Mob, and the Meatball |
| 9  | Sam & Max: Episode 104 - Abe Lincoln Must Die! |
| 10 | Sam & Max: Episode 105 - Reality 2.0 |
| 11 | Sam & Max: Episode 106 - Bright Side of the Moon |
| 12 | Sam & Max: Episode 201 - Ice Station Santa |
| 13 | Sam & Max: Episode 202 - Moai Better Blues |
| 14 | Sam & Max: Episode 203 - Night of the Raving Dead |
| 15 | Sam & Max: Episode 204 - Chariots of the Dogs |
| 16 | Sam & Max: Episode 205 - What's New, Beelzebub |
| 17 | Strong Bad: Episode 1 - Homestar Ruiner |
| 18 | Strong Bad: Episode 2 - Strong Badia the Free |
| 19 | Strong Bad: Episode 3 - Baddest of the Bands |
| 20 | Strong Bad: Episode 4 - Daneresque 3 |
| 21 | Strong Bad: Episode 5 - 8-Bit Is Enough |
| 22 | CSI 3 - Dimensions of Murder / Bone demo |
| 23 | CSI 4 - Hard Evidence (demo) |
| 24 | Tales of Monkey Island 101: Launch of the Screaming Narwhal |
| 25 | Wallace & Gromit: Episode 4: The Bogey Man |
| 26 | Tales of Monkey Island 102: The Siege of Spinner Cay |
| 27 | Tales of Monkey Island 103: Lair of the Leviathan |
| 28 | CSI 5 - Deadly Intent |
| 29 | Tales of Monkey Island 104: The Trial and Execution of Guybrush Threepwood |
| 30 | CSI 4 - Hard Evidence |
| 31 | Tales of Monkey Island 105: Rise of the Pirate God |
| 32 | CSI 5 - Deadly Intent (demo) |
| 33 | Sam & Max: Episode 301 - The Penal Zone |
| 34 | Sam & Max: Episode 302 - The Tomb of Sammun-Mak |
| 35 | Sam & Max: Episode 303 - They Stole Max's Brain! |
| 36 | Puzzle Agent - The Mystery of Scoggins |
| 37 | Sam & Max: Episode 304 - Beyond the Alley of the Dolls |
| 38 | Sam & Max: Episode 305 - The City That Dares Not Sleep |
| 39 | Poker Night at the Inventory |
| 40 | CSI 6 - Fatal Conspiracy |
| 41 | Back To The Future: Episode 1 - It's About Time |
| 42 | Back To The Future: Episode 2 - Get Tannen! |
| 43 | Back To The Future: Episode 3 - Citizen Brown |
| 44 | Hector: Episode 1 - We Negotiate with Terrorists |
| 45 | Back To The Future: Episode 4 - Double Visions |
| 46 | Back To The Future: Episode 5 - OUTATIME |
| 47 | Puzzle Agent 2 |
| 48 | Jurassik Park: The Game |
| 49 | Hector: Episode 2 - Senseless Act of Justice |
| 50 | Hector: Episode 3 - Beyond Reasonable Doom |
| 51 | Law and Order: Legacies |
| 52 | Walking Dead: A New Day |
| 53 | Poker Night 2 |
| 54 | The Wolf Among Us |
| 55 | The Walking Dead: Season 2 |
| 56 | Tales from the Borderlands (all episodes) |
| 57 | Game of Thrones (all episodes) |
| 58 | Minecraft: Story Mode |
| 59 | The Walking Dead: Michonne |
| 60 | Batman: The Telltale Series |
| 61 | The Walking Dead: A New Frontier |
| 62 | Marvel's Guardians of the Galaxy |
| 63 | Minecraft: Story Mode - Season Two |
| 64 | Batman: The Enemy Within |
| 65 | Bone: Out From Boneville 2.0 |
| 66 | Bone: The Great Cow Race 2.0 |
| 67 | The Walking Dead: The Telltale Definitive Series  |
| 68 | The Walking Dead: The Final Season |
| 69 | Sam & Max Save The World Remastered |
