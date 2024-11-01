## Hi... I'm RAKIFSUL!

![Static Badge](https://img.shields.io/badge/rakifsul-lusfikar-red)

I'm a freelance desktop and web developer.

I write open source apps when there is no job.

For examples... See below.

<details>

<summary>Browser Slower</summary>

I wrote a simple JavaScript program to make my browser a little bit slower.

```
// Browser Slower v1.0.0, written by RAKIFSUL

const a = "a"; // const a = "a";

while(true) { // while(true) {
	try { // try {
		console.log(a); // console.log(a); 
	} catch (err) { // } catch (err) {
		console.log(err); // console.log(err);
	} finally { // } finally {
		console.log(a); // console.log(a);
	} // }
} // }
```
</details>

<details>

<summary>ScrCpy Command Builder</summary>

Writing an interactive app for connecting Android to PC might be a good idea:

```
@echo off

echo ScrCpy Command Builder v1.0.0, written by RAKIFSUL

echo[

echo Langkah 0: Prasyarat
echo Pastikan Anda sudah menginstall scrcpy dari sumber resminya dan menambahkannya ke PATH.

echo[

echo Langkah 1: Pairing
echo Sekarang anda akan memasangkan pc anda dengan android.
echo Pastikan anda telah meng-enable usb debugging dan wireless debugging.
echo Semua itu ada di developer options jika anda telah mengaktifkannya.

echo[

echo Dari "Developer Options, masuklah ke bagian "Wireless Debugging".
echo Silakan tap "Pair device with pairing code"
echo Berapakah IP address yang tampil di "IP address & port" ?

set /p "ip=Masukkan IP address: "
set /p "port=Masukkan Port: "

echo[

echo Terima kasih, sekarang, saya akan jalankan perintah ini: "adb pair %ip%:%port%".
echo Nanti anda akan diminta memasukkan pairing code yang ditampilkan.

adb pair %ip%:%port%

echo[

echo Langkah 2: Connecting
echo Jika pairing berhasil, maka lanjutkan.
echo Sekarang lihat bagian "IP address & port" yang ada di bawah "Device name".
echo Perhatikan bahwa port yang saya minta bukan yang untuk pairing tadi.

set /p "ip1=Masukkan IP address: "
set /p "port1=Masukkan Port: "

echo Terima kasih, sekarang, saya akan jalankan perintah ini: "adb connect %ip1%:%port1%".

adb connect %ip1%:%port1%

echo[

echo Selamat, jika koneksi berhasil, saya akan menjalankan scrcpy dengan parameter default saya.

scrcpy --video-bit-rate=8M --max-size=1090 --max-fps=60 -e
```
</details>

But wait, there's more.

Just visit the pinned repositories below.
