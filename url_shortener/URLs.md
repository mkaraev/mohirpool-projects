Ushbu bosqichda siz asosiy masalani - URL manzillarini qisqartirishni amalga oshirishingiz kerak.
URL qisqartiruvchisi URLdagi belgilar sonini kamaytiradi, bu esa o‘qish, eslab qolish va almashishni osonlashtiradi.

**Tasks**

1. `GET /urls/short/` - URL-ni qisqartirish sahifasi
2. `POTS /urls/short/` - URL-ni qisqartirish
3. `GET /urls/<str:short_url>/delete/` - `short_url`ni oʻchirish sahifasi
4. `POST /urls/<str:short_url>/delete/` - `short_url` ni ma'lumotlar bazasidan uchirib tashlash
5. `GET /urls/<str:short_url>/` - berilgan `short_url` orqali asl urlga yo'naltirish
6. Hamma endpointlar uchun testlar yozing

Faqat autentifikatsiya qilingan foydalanuvchilar qisqa URL manzillarini yaratishi mumkin.
Shuningdek, foydalanuvchilarga faqat qisqa URL manzillarini o'chirishga ruxsat beriladi.

**Eslatma:**

Bu yerda siz uzun url uzunligini qanday qisqartirish haqida o'ylashingiz kerak.
Ushbu funksiyani amalga oshirish uchun juda ko'p yondashuvlar mavjud, masalan, ba'zi bir murakkab xesh qiymatini hisoblash va faqat birinchi ber nechta belgilarni olish.
Lekin men juda oson yechimni amalga oshirishni taklif qilaman:
tasodifiy UUID4 (yoki UUID6) yaratishingiz va dastlabki 5 yoki 6 ta belgini olishingiz mumkin.


Links:

- [Python UUID](https://docs.python.org/3/library/uuid.html)
- [Django redirect](https://docs.djangoproject.com/en/4.0/topics/http/shortcuts/#redirect)
- [Django Models](https://docs.djangoproject.com/en/4.0/topics/db/models/)
- [Django Auth](https://docs.djangoproject.com/en/3.1/topics/auth/default/#the-loginrequired-mixin)
- [Many-to-One](https://docs.djangoproject.com/en/4.0/topics/db/examples/many_to_one/)
- [Django Models Relations](https://docs.djangoproject.com/en/4.0/ref/models/relations/)