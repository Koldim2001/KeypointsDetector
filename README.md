# __Реализация системы извлечения изображений по текстовому описанию и поиск похожих фотографий в датасете__


## __УСТАНОВКА:__
Необходимо иметь установленный python 3 любой версии (лучше 11). \
Данные команды требуется запускать последовательно в терминале:
1. Склонируйте к себе этот репозиторий 
```
git clone https://github.com/Koldim2001/image_retrieval.git
```
2. Перейдите с помощью команды cd в созданную папку image_retrieval
```
cd SORT-DeepSORT-Tracker
```
3. Загрузите все необходимые библиотеки: 
```
pip install -r requirements.txt
```
PS: Лучше torch ставить сразу с поддержкой gpu __если она имеется__: 
```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```
4. Запустите ноутбук [retrival.ipynb](https://github.com/Koldim2001/image_retrieval/blob/main/retrival.ipynb), в котором примеры кода по извлечению изображений
5. Для запуска надо создать папку __images__ в корне репозитория и положить туда желаемый набор фоток для анализа
<br/>

---

## Webinar/Tutorial
Имеется подробный туториал по работе с данным репозиторием, в котором рассказаны основные теоретические и практические моменты по работе с image retrieval\
Доступен по клику на иконку:\
[![webinar video](retrival_logo.jpg)](https://youtu.be/kQoe0HWg9d0)


