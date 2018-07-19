# STC
Летняя школа машинного обучения 

В <b>Solution.ipynb</b> находится код воспроизводящий полученные результаты.<br>
Перед запуском решения необходимо задать в 4-ой ячейке путь к папке с базой данных (относительно директории для которой запущен Jupyter notebook).<br>
DATASET_PATH = '.\data_v_7_stc'<br>
Повторить результаты эксперимента можно выполнив все ячейки (Cell->Run All), что может занять более 5 часов.<br>
Следуя инструкции, приведенной в <b>Solution.ipynb</b> можно задать полученные заранее гипперпараметры для ансамбля классификаторов и порога отсечения класса "unknown" для открытой задачи.<br>

В <b>RnD.ipynb</b> представлено исследование по задаче (довольно сумбурно, возможно наличие ошибок не позволяющих выполнить весь код целиком), плюс нахождение всех гипперпараметров классификаторов.<br>

Файл <b>result_close.txt</b> - результаты по закрытой задаче.<br>
Файл <b>result_open.txt</b> - результаты по открытой задаче.<br>
Детектор наличия факта события представлен функцией <b>signal_detector</b>.<br>

Код разрабатывался на платформе Windows 7/10 при помощи Anaconda 3 (https://conda.io/docs/user-guide/install/windows.html) в Jupyter notebook.<br>
Использовались следующие пакеты (для <b>Solution.ipynb</b>):<br>
CPython 3.6.3
IPython 6.1.0

numpy 1.12.1
pandas 0.22.0
scipy 1.0.0
sklearn 0.19.1
os n

compiler   : MSC v.1900 64 bit (AMD64)
system     : Windows
release    : 10
machine    : AMD64
processor  : Intel64 Family 6 Model 58 Stepping 9, GenuineIntel
CPU cores  : 8
interpreter: 64bit
