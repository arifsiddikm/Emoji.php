# Emoji.php

Library file Emoji.php.

# Contoh cara penggunaan :

# Cara Encode Emoji saat insert data ke database:
$Deskripsi1 = "Emoticon 👋";
$Deskripsi2 = Emoji::Encode($Deskripsi1);

# Cara Decode Emoji saat select data dari database:
$Deskripsi1 = FetchQuery;
$Deskripsi2 = Emoji::Encode($Deskripsi1['Deskripsi']);
