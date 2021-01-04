# Task
Задача состояла в следующем: необходимо детектировать различные аномалии на снимках с БПЛА. Аномалии включали в себя разливы нефти, вскрытие грунта, складирование материала, а также несанкционированную свалку. Задача сформулирована компанией "Татнефть" на хакатоне Kazan Digital, ею же были предоставлены данные.

# Data
Данные представляют из себя фотографии размера 6000x4000. Включают в себя классы приведённых выше аномалий, а также: объекты нефтедобычи, рельеф, скважины без разливов. Данные, а также разметку можно найти по [ссылке](https://drive.google.com/drive/u/0/folders/1uCVHIz9cddaOKVQ8_SC_FcwgXTnIa4gC)
![Пример разлива нефти](https://github.com/gorodion/Anomaly-Detection-UAV/blob/master/example.jpg)
# Solution
Данная задача решалась с использованием различных подходов компьютерного зрения на основе CNN. Решение представлено в виде Jupyter ноутбуков в трёх частях: классификация, сегментация и детектирование. Приятного обзора!