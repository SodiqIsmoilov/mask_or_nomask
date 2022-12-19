# mask_or_nomask

Ushbu model maska insonning maska taqqan yoki taqmaganligini classifikatsiya qilib beradi. Model CNN MobileNetV2 arxitekturasi asosida qurilgan 154 layer dan iborat
Umumiy parametrlar soni: 8,531,105
Train qilinadiganlari: 6,273,121
Train qilimaydiganlari: 2,257,984

Input_shape = (224,224,3)

Datani ushbu ssilkada olish mumkin https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset

Ishlatilgan kutubxonalar:
Tensorflow - Model tuzishda ishlatiladi
opencv-python - Kompyuter ko'rishi(Computer Vision)
numpy - matritsalar bilan operatsiyalarni amalga oshirishda juda tez ishaydigan python kutubxonasi
os - fayllar bilan ishlash uchun
tqdm - progress bar
random - ma'lumotlarni tasodifiy aralashtirish uchun
