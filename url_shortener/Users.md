Loyihamizda foydalanuvchilarni faqat asosiy ma'lumotlari bo'ladi: foydalanuvchi ismi, parol, elektron pochta.

Foydalanuvchilar ro'yhatdan o'tishi va o'z profilini o'chirishi mumkin.
Shuningdek, biz loyihamizda birinchi **testlarni** yaratamiz.
Testlar har qanday yaxshi dasturiy ta'minotning juda muhim qismi bo'lib, ular sizning kodingiz to'g'riligiga ishonch hosil qiladi.


**Tasks**

Quyidagi endpointlarnig yarating.

1. `GET /users/register/` - ro'yhatdan o'tish sahifasini qaytarish
2. `POTS /users/create/` - foydalanuvchini ro'yhatdan o'tkazish
3. `GET /users/<int:pk>/delete/` - foydalanuvchini o'chirib tashlash sahifasi
4. `POST /users/int:pk/delete/` - foydalanuvchini o'chirib tashlash
5. `GET /login/` - log-in sahifasini qaytarish
6. `POST /login/` - foydalanuvchi autentifikatsiyasi. Bu yerda foydalanuvchi saytga kirishi kerak.
7. `POST /logout/` - saytdan chiqish
8. Hamma endpointlar uchun testlar yozing


**Links**

- [MVC](https://ru.wikipedia.org/wiki/Model-View-Controller)
- [Django Urls](https://docs.djangoproject.com/en/4.0/topics/http/urls/)
- [Django Forms](https://docs.djangoproject.com/en/4.0/topics/forms/modelforms/)
- [Django Class Based Views](https://docs.djangoproject.com/en/4.0/ref/class-based-views/)
- [Pytest](https://docs.pytest.org/en/7.1.x/)
- [Django Tests](https://docs.djangoproject.com/en/4.1/topics/testing/)