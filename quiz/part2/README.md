# Quiz Pemrograman Sebelum Masuk Looping | Part 2
## Soal 1
```js
//1. Let's Form a Sentence

// Problem
// Pada tugas ini kamu diminta untuk melakukan penambahan string menggunakan simbol +.
//  Disediakan variable word. Tambahkan nilai word satu per satu dengan nilai variable lain
//  untuk membentuk sebuah kalimat. Jangan lupa menambahkan spasi di setiap kata, dan
//   tampilkan di console hasil penggabungannya! Kamu tidak perlu membuat variable baru!

let word = 'JavaScript';
let second = 'is';
let third = 'awesome';
let fourth = 'and';
let fifth = 'I';
let sixth = 'love';
let seventh = 'it!';

//code here
const gabung1 = `${word} ${second} ${third} ${fourth} ${fifth} ${sixth} ${seventh}`;
console.log(gabung1);

const gabung2 = word + ' ' + second + ' ' + third + ' ' + fourth + ' ' + fifth + ' ' + sixth + ' ' + seventh;
console.log(gabung2);
```
## Soal 2. Index Accessing - 1 by 1
```js
// Problem
// Pada tugas ini kamu diminta untuk "memecah" sebuah kalimat dan menampilkan setiap kata didalamnya.
//  Untuk soal nomor ini, gunakan akses satu per satu karakter dari string untuk mengambil setiap huruf dalam kata.
//   Terasa manual? Tidak apa-apa, kita coba ini dulu untuk saat ini.

// Hints
// Saat kamu mendapatkan tiap huruf, untuk membentuk setiap kata kamu tinggal menggunakan simbol + untuk membentuk kata
//  tersebut!

let word = 'wow JavaScript is so cool';

const firstWord = word[0] + word[1] + word[2];
const secondWord = word[4] + word[5] + word[6] + word[7] + word[8] + word[9] + word[10] + word[11] + word[12] + word[13];
const thirdWord = word[15] + word[16];
const forthWord = word[18] + word[19];
const fifthWord = word[21] + word[22] + word[23] + word[24];

console.log('First Word: ' + firstWord);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + forthWord);
console.log('Fifth Word: ' + fifthWord);
```
## Soal 3. Breaking Sentence (Again) using Substring
```js
// Problem
// Mirip seperti soal nomor 2, namun kali ini gunakan substring untuk mengambil potongan dari tiap kata!

let word3 = 'wow JavaScript is so cool';
let exampleFirstWord3 = word3.substring(0, 3);



console.log('First Word: ' + exampleFirstWord3);

const firstWord = word3.substring(0,3);
const secondWord = word3.substring(4, 14);
const thirdWord = word3.substring(15, 17);
const fourthWord = word3.substring(18, 20);
const fifthWord = word3.substring(21, 25);

console.log('First Word: ' + firstWord);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + fourthWord);
console.log('Fifth Word: ' + fifthWord);
```

## Soal 4. Breaking Sentence (yet Again) and Count Each Length
```js
// Problem
// Mirip seperti soal nomor 3, tapi tampilkan juga panjang kata masing-masingnya!

let word4 = 'wow JavaScript is so cool';

const firstWord = word4.substring(0,3);
const secondWord = word4.substring(4, 14);
const thirdWord = word4.substring(15, 17);
const fourthWord = word4.substring(18, 20);
const fifthWord = word4.substring(21, 25);

const firstWordLength = firstWord.length;
const secondWordLength = secondWord.length;
const thirdWordLength = thirdWord.length;
const fourthWordLength = fourthWord.length;
const fifthWordLength = fifthWord.length;

console.log('First Word: ' + firstWord + ',with Length: ' + firstWordLength);
console.log('Second Word: ' + secondWord + ',with Length: ' + secondWordLength);
console.log('Third Word: ' + thirdWord + ',with Length: ' + thirdWordLength);
console.log('Fourth Word: ' + fourthWord + ',with Length: ' + fourthWordLength);
console.log('Fifth Word: ' + fifthWord + ',with Length: ' + fifthWordLength);
```

tulis code sesuai dengan keterangan soalnya dan pola example yang ada

Selamat Mengerjakan 👨🏻‍🌾