### Переключение раскладки US/RU в XRDP XVNC 

**1.** Добавить файл _km-00001419.ini_ в папку `/etc/xrdp/`

**2.** В файле `/etc/xrdp/xrdp.ini` добавить строки:

```ini
[Globals]
xrdp.override_keyboard_type=0x04
xrdp.override_keyboard_subtype=0x01
xrdp.override_keylayout=0x00001419
```

---

Переключение раскладки происходит по нажатию клавиши **CapsLock**
