# Ofis sotqini

Hamkasblar rasmlari bilan brauzerda birga o'ynaladigan ofis detektiv o'yini. Ofisga sotqin kirib olgan: u xodimlarni birin-ketin "ishdan bo'shatadi". Qolganlar topshiriqlarni bajarishi yoki planyorkada sotqinni fosh qilishi kerak.

## Qanday boshlanadi

1. Bir kishi saytni ochib **"Yangi xona ochish"** ni bosadi. 5 belgili xona kodi chiqadi.
2. U **"Rasm qo'shish"** orqali hamkasblar rasmlarini yuklaydi (bir nechtasini birdaniga). Rasmlar faqat shu kompyuterning brauzerida saqlanadi, internetga yuklanmaydi.
3. **"Havolani nusxalash"** ni bosib, havolani hamkasblarga yuboradi. Ular havolani ochib o'z rasmini tanlaydi.
4. Kamida 3 kishi yig'ilgach, kimdir **"O'yinni boshlash"** ni bosadi.

Xona ochgan odam o'yin tugaguncha sahifani yopmasligi kerak: ulanish uning brauzeri orqali o'tadi. Hamma bitta Wi-Fi'da bo'lsa, eng yaxshi ishlaydi.

## Qoidalar

- **Xodimlar** ofis bo'ylab yurib topshiriqlarni bajaradi: kofe qaynatish, printerga qog'oz solish, imzo chekish, Wi-Fi'ni qayta yoqish va boshqalar. Hamma ishlar bitsa, xodimlar yutadi.
- **Sotqin** yaqinidagi hamkasbni ishdan bo'shatadi va svetni o'chira oladi. Sotqinlar soni xodimlarga tenglashsa, sotqin yutadi.
- **Planyorka:** bo'shatilgan hamkasbni topgan odam xabar beradi yoki planyorka xonasidagi qo'ng'iroqni bosadi. Hamma ovoz chiqarib bahslashadi va ovoz berib bittasini haydaydi.
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

Bitta `index.html` fayl, server kerak emas. O'yinchilar ulanishi uchun [PeerJS](https://peerjs.com) ishlatiladi.
