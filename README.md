# FastPing

---

Утилита командной строки, для быстрой проверки подключения к адресу на уровне IP.

<img src="image/fastping-scr.png" width="500px">

На данном скриншоте отображены все исходные файлы программы, а также пример выполнения запроса.

<a name="Oglavlenie"></a>

**Оглавление**

1. [Информация](#Info)
2. [Компиляция](#Compilation)
3. [Примеры использования](#Examples)
4. [Обо мне](#About)

---

## <a name="Info">Информация</a>

Стандартная утилита командной строки имеет некоторую задержку отправки подобных комманд проверки доступности того или иного узла. Данная утилита не имеет такой неприятной задержки. 

Однако, и она имеет свои ограничения. Например, большинство параметров в ней заданы по умолчанию и не могут быть изменены с целью ускорения отправки таких запросов и получения ответов соответственно.

<img src="image/cpp-builder-icon.svg" width="140">

Программа написана на языке C++. Для этого использовалась IDE - C++ Builder.

---

[К оглавлению](#Oglavlenie)

## <a name="Compilation">Компиляция</a>

Для компиляции программы понадобится **Borland C++ Builder 6 Pro**. Причём достаточно будет даже **Portable** версии утилиты.

Найдите такую в *Yandex* или *Google* самостоятельно и скачайте. К сожалению, лицензия данной программы не позволяет прикреплять ссылки на скачивание нелицензионных указанной данной **IDE**.

Как только установите или распакуете данную *IDE* откройте файл проекта: **«src/fastping.bpr»**.

**Обратите внимание!** Не пытайтесь в настройках проекта (Project -> Options) на вкладке **Version Info** поставить *Minor*, *Release* или *Build* версию, а также на вкладке **Cimpiler** снять галочки с *Warnings* и *Debugging* или автоматически выставить параметры при помощи кнопок *Full Debug* и *Release*. 

У вас скорее всего возникнет ошибка октрытия объектного файла проекта **«COX32.obj»** и исправить её, к сожалению, никак не удасться!

Сразу компилируйте проект в режиме как есть. Этого будет достаточно!

---

[К оглавлению](#Oglavlenie)

## <a name="Examples">Примеры использования</a>

Запустите командную строку и перейдите в папку с программой.
наберите имя программы и адрес, достумность которого желаете проверить. Никаких дополнительных параметров и аргументов вводить не нужно.

```
	C:\Temp\FastPing> fastping ya.ru
	
	C:\Temp\FastPing> fastping 8.8.8.8
	
```

---

[К оглавлению](#Oglavlenie)

## <a name="About">Обо мне</a>

The author of this development **Shadow**: [maximalisimus](https://github.com/maximalisimus).

Author's name: **maximalisimus**: [E-Mail](mailto:maximalis171091@yandex.ru).

Date of creation: **23.08.2022**

