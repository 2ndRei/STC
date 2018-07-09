# STC
Летняя школа машинного обучения 

В <b>solution.ipynb</b> находиться код воспроизводящий полученные результаты.<br>
Необходимо запустить все ячейки (Cell->Run All).<br>
Перед этим задав в 3-ей ячейке путь к папке с базой данных (относительно директории для которой запущен Jupyter notebook).<br>
DATASET_PATH = '.\data_v_7_stc'<br>

В <b>research.ipynb</b> представлено исследование по задаче (довольно сумбурно, возможно наличие ошибок не позволяющих выполнить весь код целиком), плюс нахождение всех гипперпараметров.<br>

Файл <b>result_close.txt</b> - результаты по закрытой задаче.<br>
Файл <b>result_open.txt</b> - результаты по открытой задаче.<br>
Детектор наличия факта события представлен функцией <b>signal_detector</b>.<br>

Код разрабатывался на платформе Windows 7/10 при помощи Anaconda 3 (https://conda.io/docs/user-guide/install/windows.html) в Jupyter notebook.<br>
Использовались следующие пакеты (для <b>solution.ipynb</b>):<br>
import os<br>
from os import path<br>
import numpy as np<br>
import pandas as pd<br>
from scipy.io import wavfile<br>
from sklearn.svm import SVC<br>
from sklearn.ensemble import RandomForestClassifier<br>
from sklearn.multiclass import OneVsRestClassifier<br>
from sklearn.preprocessing import StandardScaler<br>
from sklearn.metrics import confusion_matrix, accuracy_score
