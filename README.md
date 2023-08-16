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

   Unit Test bu dasturni eng kichik komponentlarini ajratib olgan holda ularni to’g’ri 
   ishlashini tekshirish. Bu komponentchalar odatda juda kichik va mustaqil bo’ladi. 
   Ular birgalikda katta dasturni tashkil qiladi. Ushbu kichik komponent va qismlarni 
   ajratib olib test qilish orqali ulardagi hatoliklar juda erta aniqlanadi va bu    
   o’z navbatida katta vaqt va pul tejalishiga olib keladi.





#3 Django ORM da select_related va prefetch_related ning maqsadi nima va ular qanday farq qiladi? 
