🩺 Kasallik Tashxisi Dasturi
📘 Loyihaning maqsadi

Ushbu dastur foydalanuvchi kiritgan kasallik belgisi asosida unga mos dori nomini tavsiya qiladi va dorining rasmini ekranda ko‘rsatadi.
Dastur Google Colab muhiti uchun moslashtirilgan va cv2 (OpenCV) kutubxonasi yordamida ishlaydi.

⚙️ Ishlash prinsipi

Foydalanuvchi kasallik belgisini kiritadi (masalan: grip, bosh ogriq, yotal).

Dastur kiritilgan belgiga mos dori nomini aniqlaydi.

Tavsiya etilgan dori nomi konsolda chiqariladi.

Agar rasm mavjud bo‘lsa, u cv2_imshow() yordamida ekranda ko‘rsatiladi.

🧩 Talab qilinadigan kutubxonalar

Dastur quyidagi kutubxonalardan foydalanadi:

import cv2
import os
from google.colab.patches import cv2_imshow


Google Colab muhitida bu kutubxonalar avtomatik mavjud, ammo lokal kompyuterda ishlatmoqchi bo‘lsangiz, quyidagi buyruq orqali o‘rnating:

pip install opencv-python

📁 Fayl tuzilmasi
/content/
│
├── Screenshot 2025-10-16 095811.png   # Teraflyu
├── Screenshot 2025-10-16 095901.png   # Bolnol
├── Screenshot 2025-10-16 095842.png   # Kupen
├── Screenshot 2025-10-16 095935.png   # Loratal
├── Screenshot 2025-10-16 102354.png   # Parasetamol
├── Screenshot 2025-10-16 102731.png   # Kreon
├── Screenshot 2025-10-16 102909.png   # Ass
└── Screenshot 2025-10-16 103034.png   # Menovazin

🧠 Foydalanish bo‘yicha ko‘rsatma

Dastur kodini Google Colab muhitida ishga tushiring.

So‘rovda kasallik belgisini kiriting:

Kasallik belgisini kiriting: grip


Natija quyidagicha chiqadi:

Teraflyu iching


va dorining rasmi ekranda paydo bo‘ladi.

💊 Qo‘llab-quvvatlanadigan belgilar
Kasallik belgisi	Tavsiya dori nomi
grip	Teraflyu
bosh ogriq	Bolnol
tish ogrigi	Kupen
allergiya	Loratal
istima	Parasetamol
qorin ogrigi	Kreon
yotal	Ass
oyoq ogrigi	Menovazin
💡 Muallif haqida

Dastur OpenCV asosida tuzilgan ta’limiy loyiha bo‘lib, foydalanuvchiga sog‘liq bilan bog‘liq umumiy maslahatlarni interaktiv tarzda ko‘rsatadi.
⚠️ Eslatma: Bu dastur tibbiy maslahat o‘rnini bosa olmaydi. Haqiqiy tashxis uchun shifokorga murojaat qiling.# dori.tavsiyasi.cv2
