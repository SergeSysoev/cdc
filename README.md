# cdc
Писалось как защита к лабе. Теперь есть желание немножко доработать, может, что выйдет.
Использование - запускаем из консоли с двумя агрументами:
Первый - что делать (-h, -c или -d), второй - имя файла (и/или путём к нему), где будет храниться сообщение.
Алгоритм кодирования - извлекаем восьмибитный код каждого символа сообщения, записываем каждый бит символа вместо первого бита исходных символов в файле.
То есть, один символ исходного сообщения будут кодировать 8 символов из файла.
