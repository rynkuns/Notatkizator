
Program zapamiętuje ostatnie zarejestrowane współrzędne ekran do notowania.

Obecnie program jest przystosowany do zapisu języka angielskiego, polskiego i wzorów matematycznych.



## Ustawienia znajdziesz w pliku config.ini: ##

[okno]
ax, ay, bx, by = współrzędne narożników skanowanego okna (a=górny lewy róg, b=dolny prawy róg)
progowanie - średnia kwadratów różnicy pomiędzy obrazami; próg skanowania zrzutu; domyślnie=2.5

[tesseract]
langs - 3-literowe kody notowanych języków połączone znakiem '+'
path - lokalizacja tesseract.exe; domyślnie=C:\Program Files\Tesseract-OCR\tesseract.exe
kontrast - stopień podbicia kontrastu przechwyconego obrazu przed skanowaniem przez Tesseract (0=brak podbicia)

[preferencje]
motyw - wybór szaty graficznej; dostępne: Szymon, Ola
bip bop - dźwięki aplikacji (1=włączone, 0=wyłączone)
autozapis - czy program ma automatycznie zapisywać nowe informacje z ekranu, czy ma to się odbywać ręcznie (1=automatycznie, 0=ręcznie) 

