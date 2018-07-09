# STC
Летняя школа машинного обучения 

В <b>solution.ipynb</b> находиться код воспроизводящий полученные результаты.
Необходимо запустить все ячейки (Cell->Run All).
Перед этим задав в 3-ей ячейке путь к папке с базой данных (относительно директории для которой запущен Jupyter notebook).
DATASET_PATH = '.\data_v_7_stc'

В <b>research.ipynb</b> представлено исследование по задаче (довольно сумбурно, возможно наличие ошибок не позволяющих выполнить весь код целиком), плюс нахождение всех гипперпараметров.

Файл <b>result_close.txt</b> - результаты по закрытой задаче.
Файл <b>result_open.txt</b> - результаты по открытой задаче.
Детектор наличия факта события представлен функцией <b>signal_detector</b>.

Код разрабатывался на платформе Windows 7/10 при помощи Anaconda 3 (https://conda.io/docs/user-guide/install/windows.html) в Jupyter notebook.
Использовались следующие пакеты (для <b>solution.ipynb</b>):
import os
from os import path
import numpy as np
import pandas as pd
from scipy.io import wavfile
from sklearn.svm import SVC
from sklearn.ensemble import RandomForestClassifier
from sklearn.multiclass import OneVsRestClassifier
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import confusion_matrix, accuracy_score
