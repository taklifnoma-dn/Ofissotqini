# Ofis sotqini

Hamkasblar rasmlari bilan brauzerda birga o'ynaladigan 3D ofis detektiv o'yini. Ofisga sotqin kirib olgan: u xodimlarni birin-ketin "ishdan bo'shatadi". Qolganlar topshiriqlarni bajarishi yoki planyorkada sotqinni fosh qilishi kerak.

**O'ynash:** https://taklifnoma-dn.github.io/Ofissotqini/

## Xarita

O'yin bizning ofisimiz va uning atrofida bo'lib o'tadi: 2-etaj TASNIF (o'yin divan yonida boshlanadi), 1-etaj Animax, Oshxona, Balkon, Qizlar tualeti, milliy uslubdagi Nigora kafe, Ko'cha (BYD mashinalari bilan), Sigaret pitak, Hola magazin va Qo'shnining uyi.

Xaritada uchta tirik personaj bor: Hola magazinda **Hola opa** mahalla yangiliklarini aytadi, Nigora kafeda **Oshpaz bobo** osh taklif qiladi, **Qo'shni** esa shovqindan shikoyat qiladi.

## Qanday boshlanadi

1. Bir kishi saytni ochib **"Yangi xona ochish"** ni bosadi. 5 belgili xona kodi chiqadi.
2. U **"Rasm qo'shish"** orqali hamkasblar rasmlarini yuklaydi (bir nechtasini birdaniga). Rasmlar faqat shu kompyuterning brauzerida saqlanadi.
3. **"Havolani nusxalash"** ni bosib, havolani hamkasblarga yuboradi. Ular havolani ochib o'z rasmini tanlaydi.
4. Kamida 3 kishi yig'ilgach, kimdir **"O'yinni boshlash"** ni bosadi. O'yin boshlangach, u tugamaguncha qaytadan boshlab bo'lmaydi.

Xona ochgan odam o'yin tugaguncha sahifani yopmasligi kerak. Agar u sahifani tasodifan yangilab yuborsa, xona o'sha kod bilan o'zi qayta ochiladi va hamma avtomatik qayta ulanadi. To'g'ridan-to'g'ri ulanish ishlamasa, o'yin o'zi ommaviy serverlar orqali ulanadi.

## Qoidalar

- **Xodimlar** topshiriqlarni bajaradi: kabellarni ulash, seyf kodini takrorlash, oshni damlash, mashina oynasidan barglarni tozalash, hisobotni yuborish, kadrlarni 1-10 tartiblash va boshqalar. Hamma ishlar bitsa, xodimlar yutadi.
- **Sotqin** yaqinidagi hamkasbni ishdan bo'shatadi, lyuklar orqali xonadan xonaga yashirin o'tadi va sabotaj qiladi:
  - **Svetni o'chirish:** xodimlar deyarli hech narsani ko'rmaydi. Qizil strelka 1-etajdagi elektr shchitiga olib boradi.
  - **Serverni qizdirish:** 45 soniya ichida ikki kishi bir vaqtda Animax va TASNIF'dagi serverlarni ushlab turmasa, sotqin yutadi.
- Sotqinlar soni xodimlarga tenglashsa, sotqin yutadi.
- **Planyorka:** jasadni topgan odam xabar beradi yoki TASNIF'dagi jurnal stol ustidagi qizil tugmani bosadi. Avval muhokama vaqti, keyin ovoz berish. Natijada kim kimga ovoz bergani ko'rinadi.
- Yorug'lik devordan o'tmaydi: devor ortida nima borligini ko'rmaysiz.
- Bo'shatilganlar arvohga aylanadi: topshiriqlarni bajarishda davom etadi, lekin tiriklarga hech narsa demaydi.

## Boshqaruv

| Harakat | Klaviatura | Telefon |
|---|---|---|
| Yurish | WASD yoki strelkalar | Chapdagi joystik |
| Ishlatish | E | "Ishlatish" tugmasi |
| Xabar berish | R | "Xabar berish" |
| Bo'shatish (sotqin) | Q | "Bo'shatish" |
| Sabotaj (sotqin) | F | "Sabotaj" |
| Lyuk (sotqin) | V | "Lyuk" |
| Xarita | M | "Xarita" |

Musiqa birinchi bosishdan keyin boshlanadi, "Musiqa" tugmasi bilan o'chiriladi. Kompyuter sekin bo'lsa, o'yin grafikani o'zi soddalashtiradi (**Menyu → Grafika**).

Bitta `index.html` fayl, server kerak emas. 3D grafika uchun [Three.js](https://threejs.org), o'yinchilar ulanishi uchun [PeerJS](https://peerjs.com) va zaxira sifatida MQTT ishlatiladi.
