# LinkedIn: Go desktop для AI runtime — это очень трезвый выбор

Когда продукт local-first по своей природе, архитектурный центр тяжести у него уже не во фронтенде.

Он в runtime:

- subprocesses
- provider adapters
- artifact model
- local preview processes
- files, policies, diagnostics

Именно поэтому в ARC desktop слой на Go для нас выглядел не “экзотикой”, а самым честным решением.

Не потому что “Go модно”.
А потому что AI desktop для local runtime — это не просто веб-морда поверх API.

Это surface над системной машиной.

Мне кажется, в этом вообще важная мысль для AI product builders:

если ядро у тебя локальное и процессное, UI должен расти рядом с этим ядром, а не притворяться, что его не существует.
