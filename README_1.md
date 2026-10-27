# Ofis sotqini

Hamkasblar rasmlari bilan brauzerda birga o'ynaladigan 3D ofis detektiv o'yini. Ofisga sotqin kirib olgan: u xodimlarni birin-ketin "ishdan bo'shatadi". Qolganlar topshiriqlarni bajarishi yoki planyorkada sotqinni fosh qilishi kerak.

**O'ynash:** https://taklifnoma-dn.github.io/Ofissotqini/

## Xarita

O'yin bizning ofisimiz va uning atrofida bo'lib o'tadi: 2-etaj TASNIF (o'yin divan yonida boshlanadi), 1-etaj Animax, Oshxona, Balkon, Qizlar tualeti, Nigora kafe, Ko'cha (Akmalning mashinasi bilan), Sigaret pitak, Hola magazin va Qo'shnining uyi.

## Qanday boshlanadi

1. Bir kishi saytni ochib **"Yangi xona ochish"** ni bosadi. 5 belgili xona kodi chiqadi.
2. U **"Rasm qo'shish"** orqali hamkasblar rasmlarini yuklaydi (bir nechtasini birdaniga). Rasmlar faqat shu kompyuterning brauzerida saqlanadi, internetga yuklanmaydi.
3. **"Havolani nusxalash"** ni bosib, havolani hamkasblarga yuboradi. Ular havolani ochib o'z rasmini tanlaydi.
4. Kamida 3 kishi yig'ilgach, kimdir **"O'yinni boshlash"** ni bosadi.

Xona ochgan odam o'yin tugaguncha sahifani yopmasligi kerak: ulanish uning brauzeri orqali o'tadi. Agar u sahifani tasodifan yangilab yuborsa, xona o'sha kod bilan o'zi qayta ochiladi va hamma avtomatik qayta ulanadi. Hamma bitta Wi-Fi'da bo'lsa, eng yaxshi ishlaydi.

Kompyuter sekin bo'lsa, o'yin grafikani o'zi soddalashtiradi. Buni **Menyu → Grafika** orqali qo'lda ham o'zgartirish mumkin.

## Qoidalar

- **Xodimlar** ofis bo'ylab yurib topshiriqlarni bajaradi: kofe qaynatish, oshni aralashtirish, Akmalning mashinasi raqamini topish, multfilm kadrlarini tartiblash, trenajorda shug'ullanish va boshqalar. Hamma ishlar bitsa, xodimlar yutadi.
- **Sotqin** yaqinidagi hamkasbni ishdan bo'shatadi va svetni o'chira oladi. Sotqinlar soni xodimlarga tenglashsa, sotqin yutadi.
- **Planyorka:** bo'shatilgan hamkasbni topgan odam xabar beradi yoki TASNIF'dagi jurnal stol ustidagi qizil tugmani bosadi. Hamma ovoz chiqarib bahslashadi va ovoz berib bittasini haydaydi.
- Bo'shatilganlar arvohga aylanadi: topshiriqlarni bajarishda davom etadi, lekin tiriklarga hech narsa demaydi.

## Boshqaruv

| Harakat | Klaviatura | Telefon |
|---|---|---|
| Yurish | WASD yoki strelkalar | Chapdagi joystik |
| Ishlatish | E | "Ishlatish" tugmasi |
| Xabar berish | R | "Xabar berish" |
| Bo'shatish (sotqin) | Q | "Bo'shatish" |
| Svetni o'chirish (sotqin) | F | "Svetni o'chirish" |
| Xarita | M | "Xarita" |

Musiqa birinchi bosishdan keyin boshlanadi, "Musiqa" tugmasi bilan o'chiriladi.

## GitHub Pages'ga joylash

1. GitHub'da yangi public repo oching (masalan, `ofis-sotqini`).
2. `index.html` va `README.md` ni yuklang (**Add file → Upload files**).
3. **Settings → Pages** bo'limida *Branch: main*, papka */ (root)* ni tanlab **Save** bosing.
4. Bir-ikki daqiqadan keyin o'yin `https://<akkaunt>.github.io/ofis-sotqini/` manzilida ochiladi.

Bitta `index.html` fayl, server kerak emas. 3D grafika uchun [Three.js](https://threejs.org), o'yinchilar ulanishi uchun [PeerJS](https://peerjs.com) ishlatiladi.
