# Celebrity / «Знаменитій»

Live site: https://celebrity.webart.work

## About
Celebrity — камерне помешкання (`lodge_or_guest_house`) у Кам’янці-Подільському, вул. Гунська, 32. Сторінка продає «easy city stay» за формулою STAY · REST · EXPLORE: проживання, тераса, безкоштовні Wi-Fi і приватна парковка, кондиціонування, можна з тваринами. Сценарій конверсії — ARRIVE → PARK → STAY → EXPLORE; кампанійний рядок «Припаркуйте авто. Залиште речі. Кам’янець чекає.»

У list.json об’єкт названо «готельно-ресторанний комплекс», але сучасні джерела ресторан не підтверджують — тому на сторінці немає ні ресторану, ні сніданку, ні бару (ні в навігації, ні в галереї, ні в SEO).

## Amenities (verified)
- Безкоштовний Wi-Fi, безкоштовна приватна парковка, тераса, кондиціонування
- Приватна ванна кімната лише в частині варіантів — так і написано; у schema не винесено
- Pet friendly (умови не підтверджені)

## Contact
- Phone: +380 67 159 49 57 — єдиний підтверджений канал
- Email, website, Instagram: не підтверджені, не публікуються
- Booking.com: https://www.booking.com/hotel/ua/celebrity.uk.html
- Address: вул. Гунська, 32, Кам’янець-Подільський
- Google Maps: CID-посилання `https://maps.google.com/?cid=8552997515122737342`

## Reviews
Google 4.5/5 (207) і Booking.com 9.0/10 (137) — знімок на 29.09.2026. Показано окремими картками в hero та в секції відгуків, без спільного «середнього» і без aggregateRating у structured data. Цитат немає.

## Forms
Connected to HotelOS (`hotelId` kp-celebrity): `stay-request` (phone required; name, guests, dates, message — pet/parking details go in the message). No room-type select (categories unverified). Also bookable by phone and on Booking.com; instant booking is not promised.

## Structured data
`LodgingBusiness` (не `Hotel`), name Celebrity, alternateName «Знаменитій». Без numberOfRooms, starRating, email, check-in/out, aggregateRating.

## Photos
Тимчасові стокові фото з Pexels (ліцензія Pexels, атрибуція не обов’язкова), 1440×960 JPG у `images/`. Фото номерів, тераси, входу й подвір’я — ілюстративні (так і підписано); `city.jpg` — справжня вулиця Кам’янця-Подільського, без тверджень про відстань. Відхилено: 8292491 (вивіска «BAXTER»), 31728412 (кухонний куточок — кухня не підтверджена — і постер з людиною).

| Файл | Pexels ID | Автор |
|---|---|---|
| `hero.jpg` | 6934229 | Max Vakhtbovych |
| `room.jpg` | 37460682 | UMUT |
| `terrace.jpg` | 36418599 | Sóc Năng Động |
| `entrance.jpg` | 887822 | Tirachard Kumtanom |
| `final.jpg` | 5667225 | Serena Koi |
| `pets.jpg` | 2102839 | Lisa Fotios |
| `city.jpg` | 30525394 | Olesia Libra |

## Notes
Не підтверджені й не публікуються: поточна кількість номерів (старі джерела — 7, не використовувати), місткість, категорії, ціни, ліжка, розміри; приватна ванна в кожному варіанті; ресторан, кафе, бар, сніданок, кухня; балкон; сауна, SPA, басейн; сімейні номери; зірковість; вид із тераси; відстань до Старого міста чи фортеці; час заїзду й виїзду; години рецепції. Якщо ресторан підтвердиться — розширити до STAY · DINE · REST.
