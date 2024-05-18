> The swiss army knife os sound processing


```bash
ffmpeg -i old.wav -ac 1 -ar 16000 new.wav
```

 
```bash
sox old.mp3 -r 16k -c 1 new.wav
```

 
```bash
sox old.mp3 -r 16k -c 1 new.ogg
```

 
```bash
sox old.mp3 -r 16k -c 1 -b 8 new.wav
```

 
```bash
sox old.mp3 -r 16k newLeftchannel.wav remix 1  
sox old.mp3 -r 16k newRightchannel.wav remix 2
```

 
```bash
sox --i new.wav  
sox --info new.wav
```

## Sources

* [SoX - Sound eXchange](https://h3manth.com/2009/01/08/sox-sound-exchange-2)
* [Audio resample 8K to 16K, convert mp3 to wav format](https://programmersought.com/article/31006998533/)
* [LEVERAGING THE AUDIO SIGNAL PROCESSING POWER OF SOX IN PYTHON](https://wp.nyu.edu/ismir2016/wp-content/uploads/sites/2294/2016/08/bittner-pysox.pdf)
* [SoX: Конвертация файлов для Asterisk](https://sysadminmosaic.ru/sox/asterisk)
* [Отправка голосовых сообщений и аудио в Telegram](https://help.bothelp.io/article/8227)
* [Цифровой аудиоформат](https://ru.wikipedia.org/wiki/%D0%A6%D0%B8%D1%84%D1%80%D0%BE%D0%B2%D0%BE%D0%B9_%D0%B0%D1%83%D0%B4%D0%B8%D0%BE%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82)
* [Какой аудиоформат выбрать? MP3 WMA FLAC WAV CDA](https://www.drive2.ru/b/2161458/)
* [MP3, AAC, WAV, FLAC: рассказываем обо всех форматах аудиофайлов](https://www.audiomania.ru/content/mp3-aac-wav-flac-rasskazivaem-obo-vseh-formatah-audiofaylov/)
* [Популярные форматы аудиофайлов © Movavi.ru](https://www.movavi.ru/learning-portal/audio-file-formats.html)
* [Популярные форматы аудиофайлов и их особенности](https://www.pult.ru/articles/interesting/audioformaty/)
* [Форматы аудиофайлов: Полное руководство](https://emastered.com/ru/blog/audio-file-formats)
* [Руководство по аудиоформатам: как выбрать лучшие аудиоформаты](https://filmora.wondershare.com.ru/audio/best-audio-formats.html)
