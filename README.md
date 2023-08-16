# exam-projects

#1 Keshlash (caching) nima va nega bizga keshlash kerak?

   Keshlash  — bu ma'lumotlarni server tomonida saqlashdir.
   Keshlangan  ma'lumotlarni keyinchalik serverdan talab qilsak bizga ma'lumotni tezroq qaytaradi.

Keshlashning foydali tomonlari:
   1. Tezlik: Keshlangan ma'lumotlar lokal saqlanadi, shuning uchun ularga kirish vaqtni talab qilmaydi.
      Bu dasturlar va saytlar ishlashini tezlashtirishi mumkin.
   2. Server yukini pasaytirish: Agar har bir so'rovni boshqa joydan ma'lumotlarni
      olish uchun yuborish kerak bo'lsa, server ustida yuk oshishi mumkin.
      Keshlash esa bu yukni kamaytiradi, chunki ma'lumotlar avvalroq saqlangan bo'ladi
   3. Internet trafikni kamaytirish: Keshlangan ma'lumotlar lokal saqlanganligi uchun
      ularga internet orqali so'rov yuborish shart emas.
      Bu esa foydalanuvchilarga sayt yoki dastur bilan ishlashda tezlikni ta'minlaydi.


#2 Unit testlari nima va ular nima uchun muhim?

   Unit Test bu dasturni eng kichik komponentlarini ajratib olgan holda ularni to’g’ri ishlashini tekshirish. Bu komponentchalar odatda juda kichik va mustaqil bo’ladi. Ular birgalikda katta dasturni tashkil qiladi. Ushbu kichik komponent va qismlarni ajratib olib test qilish orqali ulardagi xatoliklar juda erta aniqlanadi va bu o’z navbatida katta vaqt va pul tejalishiga olib keladi. Unit testlar dasturlashda yozilgan kodni avtomatik ravishda tekshirish uchun ishlatiladigan test toifasi hisoblanadi. Bu testlar, biror bir dastur qismi (funktsiya, metod yoki klass)ni o'zgaruvchilarni va boshqa inputlarni berish orqali ishlatib, natijani tekshirish uchun yoziladi. 
Xatolarni aniqlash va to'g'ri ishlashni ta'minlash: Unit testlar, kodni to'g'ri ishlayotgani va kiritilgan inputlarga qarab to'g'ri natijalar qaytarayotgani haqida ko'rib chiqishga yordam beradi. Agar kod qaytarishi kerak bo'lgan natijalarda xato bo'lsa, test natijalarda xatoni aniqlab beradi.

Unit testlar nima uchun muhim:
Refaktoringni osonlashtirish: Kodni o'zgartirish yoki yangi funksiyalarni qo'shish vaqtida, mavjud unit testlar kodni to'g'ri ishlashini ta'minlash uchun yordam beradi. Yangi o'zgarishlar qilgandan so'ng testlarni qayta ishga tushirib, kodni to'g'ri ishlovchi ekanligini tekshirishingiz mumkin.

Timelarni qisqartirish: Qo'shimcha xatolar aniqlash va tuzatish jarayonida vaqtni va resurslarni sarflashni kamaytirish uchun unit testlar ishlatiladi. Xatoni aniqlab berish va tuzatish jarayonini tezlashtirish uchun manbaa sifatida foydalanish mumkin.

Kodningni dokumentlash: Unit testlar kodningizning qanday qilib ishlayotganini dokumentlashtiradi. Boshqa dasturchilar va jamoatga kodni tushunarli shaklda tavsiflash uchun unit testlardan foydalanishingiz mumkin.

Boshqa qo'llanuvchilar uchun uzoq davom etuvchi kodni qayta ishga tushirish: Agar boshqa dasturchilar yoki jamoatdagi boshqa a'zolar kodni o'zgartirish yoki qayta ishga tushirishni rejalashtirishsa, ular o'zgarishlarni kodni buzishsiz to'g'ri ishlashi uchun unit testlardan foydalanishi mumkin.

Yakuniy natijalar yoki interfeyslarni ta'minlash: Agar dasturda o'zgarishlar kiritilganida, unit testlar o'zgarishlarni to'g'ri ishlayotganligini ta'minlashga yordam beradi. Bu dastur yuqorida ko'rsatilgan funksiyonalarni yo'qotmaslikka yordam beradi.

Dastur qismi yoki modulni isolatsiyalash: Unit testlar, biror bir modulni o'zining foydalanilishi bo'lmagan boshqa modullardan isolatsiyalashga imkon beradi. Bu, qo'shimcha xatolarni aniqlash va tuzatish jarayonini osonlashtiradi.




#3 Django ORM da select_related va prefetch_related ning maqsadi nima va ular qanday farq qiladi? 
