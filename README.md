# UAS PENGENALAN INFORMATIKA
## Menjelaskan dan Menginternalisasi Computational Thinking ⭐⭐⭐⭐⭐⭐⭐
Dikutip dari dicoding.com, *Computational Thinking* atau Pemikiran Komputasional cara berpikir untuk menyelesaikan suatu masalah. Caranya adalah dengan menguraikan setiap masalah menjadi beberapa bagian atau tahapan yang efektif dan efisien. Ia juga dapat diartikan menjadi sebuah metode untuk menyelesaikan suatu masalah yang dirancang untuk bisa diselesaikan oleh manusia atau sistem atau keduanya.

## Menjelaskan Jenis-Jenis Mesin Komputasi ⭐⭐⭐
Dikutip dari anotherorion.com, jenis-jenis komputasi modern meliputi:
- Mobile Computing
  
Mobile computing adalah teknologi komputasi modern yang memungkinkan pengguna untuk dapat bergerak tanpa harus duduk di depan layar komputer. Mobile computing didesain untuk dapat melakukan transmisi dan komunikasi data, suara, gambar maupun video dengan menggunakan jaringan nirkabel. Seperti gelombang radio, sinyal Wifi, RFID, bluetooth, dan lain sebagainya.
- Grid Computing

Grid computing adalah teknologi komputasi yang terdistribusi/terpisah namun melakukan koordinasi pada sebuah mekanisme guna mendukung sebuah tugas. Unsur utama dalam grid computing adalah bagaimana setiap komputer dapat berbagi sumberdaya untuk meningkatkan quality of service.
- Cloud Computing

Cloud computing merupakan komputasi modern yang memungkinkan akses sebuah software/aplikasi melalui internet, cloud computing dikembangkan untuk mendukung reliabilitas sebuah layanan. Penggunaan email, social media, instant messaging, google docs, merupakan contoh penerapan cloud computing. Dimana data disimpan dalam server cloud dan pengguna dapat terhubung ke layanan tersebut.

## Mengktifkan dan Mencoba Google Colab [v] ⭐⭐⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/b2e96914-2d1d-4c0b-96bc-1d60f3067226)

## Mencoba Console Sistem Operasi
### Windows CMD [v] ⭐⭐⭐⭐

### Linux Terminal Menggunakan Google Colab [v] ⭐⭐⭐⭐

## Membuat Algoritma Dalam Bentuk Flow Chart [v] ⭐⭐⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/ce81fc67-4313-466d-bb11-3501308ed6be)

## Mencoba Scratch Bahasa Indonesia [v] ⭐⭐⭐⭐⭐⭐⭐

## Mencoba Algoritma Bubble Sort Menggunakan Java [v] ⭐⭐⭐
```shell
import java.util.Scanner;

public class CodesCracker{
   public static void main(String[] args)
   {
      Scanner s = new Scanner(System.in);
      System.out.print("Enter the Size: ");
      int n = s.nextInt();
      int[] arr = new int[n];
      System.out.print("Enter " +n+" Elements in Random Order: ");
      for(int i=0; i<n; i++)
         arr[i] = s.nextInt();
      System.out.println("\n\nSorting the array...");
      for(int i=0; i<(n-1); i++)
      {
         for(int j=0; j<(n-i-1); j++)
         {
            if(arr[j]>arr[j+1])
            {
               int temp = arr[j];
               arr[j] = arr[j+1];
               arr[j+1] = temp;
            }
         }
      }
      System.out.println("The array is sorted successfully!");
      System.out.println("\nThe new sorted array is:");
      for(int i=0; i<n; i++)
         System.out.print(arr[i]+ " ");
   }
}
```
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/2de4b9ee-0908-4d60-bb3d-32442224059a)

## Mencoba dan Mendemonstrasikan Penggunakan IDE ⭐⭐

## Mendaftar, Mengeksplorasi, dan Mendemonstrasikan Penggunaan HackerRank [v] ⭐⭐⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/d3a1d4bc-0b2f-475e-9135-55d973a47f54)

## Mendemonstrasikan Pembuatan Aplikasi / Game Pada Platform : Mobile / Desktop / Web Browser ⭐⭐⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/344b01c6-2c48-42dc-b85c-091dde91baaa)

## Mencoba Instalasi Database (PostgreSQL / MySQL / dsb.) [v] ⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/20169a9c-3056-4247-839c-5f8747a2db97)

## Mendemonstrasikan dan Menjelaskan Penggunaan Web Browser untuk Mengakses Halaman Website HTML [v] ⭐⭐⭐⭐
- Dokumen HyperText Markup Language (HTML) ada untuk memudahkan pertukaran informasi berbasis Hypertext.
- Web Browser seperti Firefox, Chrome, Opera, ada untuk membuka dan mempresentasikan dokumen HTML
- Dokumen HTML ini bisa bersumber dari web server yang kita ingin datanya (Tokopedia, Wikipedia, Detik.com, dsb.) atau bisa juga dukumen HTML yang kita buat sendiri

## Mendemonstrasikan dan Menjelaskan Komponen Dari Contoh Uniform Resource Locator (URL) [v] ⭐⭐

## Mencoba Pelacakan Informasi Server dari Alamat Domain [v] ⭐

## Mencoba Pembuatan Halaman Web Menggunakan HTML, CSS, dan JavaScript [v] ⭐⭐⭐
```shell
<!DOCTYPE html>
<html>
<head>
<style>
body {
	background-color: lightgreen;
}

h1 {
	color: white;
    text-align: center;
}

h2 {
	text-align: center;
}

p {
	font-family: sans-serif;
    font-size: 24px;
}
</style>
</head>
<body>

<h1>UNIVERSITAS ISLAM NEGERI SUNAN GUNUNG DJATI BANDUNG</h1>
<h2>Jurusan Teknik Informatika</h2>
<p>Nama	: Denis Firmansyah</p>
<p>NIM	: 1227050034</p>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

<p id="demo"></p>

</body>
</html>
```
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/bf5a73c2-14eb-4805-98aa-0ea22f62aa97)

## Mencoba Penerapan Teknik Search Engine Optimization (SEO) Pada HTML [v] ⭐⭐⭐

## Mencoba Pembuatan File JSON [v] ⭐⭐⭐

## Mencoba Penggunaan Web Hosting Dengan Untuk Halaman HTML [v] ⭐⭐⭐

## Mencoba Penggunaan Web Hosting Dengan Untuk Web Service [v] ⭐⭐⭐

## Mencoba HTTP Request dan Web API dengan Hoppscotch / Postman [v] ⭐⭐

## Mendemonstrasikan Penggunaan Developer Tools Pada Web Browser (Firefox / Chrome) [v] ⭐⭐⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/92ebef61-6329-49c6-b998-18158c2c06dc)

## Mengeksplorasi dan Menjelaskan Layanan Cloud Service yang Diminati (GCP / AWS / Azure) [v] ⭐⭐

## Mencoba Penggunaan Content Management System (Wordpress) [v] ⭐⭐⭐

## Mendemonstrasikan Akses Konten Multimedia (Image, Audio, Video) ⭐⭐⭐

## Mencoba Edit Konten Multimedia (Image, Audio, Video) [v] ⭐⭐

## Mencoba Pembuatan Game dan Simulasi Menggunakan Logo [v] ⭐⭐

## Mencoba Pemrosesan Konten Multimedia (Image, Audio) Menggunakan Google Colab [v] ⭐⭐⭐

## Mencoba Web Tool AI Discriminative (Image Classification) [v] ⭐⭐⭐⭐

## Mencoba Web Tool AI Generative (Text to Image, Text to Text) [v] ⭐⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/1a53a5ee-2ae1-4db6-8816-1d0d1750a2b4)


## Mencoba Model Machine Learning Menggunakan Google Colab, TTS, Speechrecognition, dan HuggingFace [v] ⭐⭐⭐

## Mencoba Data Visualization Dengan Tools [v] ⭐⭐

## Mencoba Data Visualization Dengan Code [v] ⭐⭐

## Mendaftar dan Mencoba Eksplorasi HuggingFace [v] ⭐⭐⭐

## Mendaftar dan Mencoba Eksplorasi Kaggle [v] ⭐⭐⭐⭐

## Mencoba Protokol Komunikasi IoT (MQTT) [v] ⭐

## Mencoba Memproses File CSV Menggunakan Google Colab [v] ⭐⭐

## Mencoba Memproses File Big Data ORC Menggunakan Google Colab [v] ⭐⭐

## Menjelaskan Jurnal, Conference, Artikel, Grade Jurnal [v] ⭐⭐⭐⭐⭐

## Eksplorasi Artikel Jurnal / Conference di Repository Terekognisi Internasional (IEEE / Arxiv / Science Direct / ACM /DBLP) [v] ⭐⭐⭐⭐

## Menonton Video Presentasi Tugas Akhir Informatika ⭐⭐⭐⭐⭐

## Mengeksplorasi Seluruh Profesi Terkait Informatika dan Profesi yang Diminati ⭐⭐⭐⭐
10 Pilihan pekerjaan dengan lulusan Teknik Informatika
- Software Developer
- Analis Sistem
- Programmer
- Information Security
- Data Analys
- Konsultan IT
- Mobile App Developer
- Game Developer
- Web Developer
- Database Administrator

Data tersebut dikutip dari primakara.ac.id

## Eksplorasi Tools Untuk Belajar Bahasa Inggris (Duolingo) ⭐⭐⭐

## Eksplorasi Tools Untuk Belajar Berbicara Bahasa Inggris (HelloTalk) ⭐⭐⭐ 

## Eksplorasi Lowongan Pekerjaan IT ⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/523299ee-fd2a-4a1e-88d2-4e756cfdaf6a)

## Eksplorasi Lowongan Freelancer IT (Upwork / Toptal / Freelancer.com) ⭐⭐⭐

## Eksplorasi dan Pilih Topik yang Diminati di Roadmap.sh ⭐⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/b7bc1d63-a2cd-4eda-94c3-9f90ca2bfbba)

## Eksplorasi Top Github Project yang Diminati ⭐⭐
![image](https://github.com/DenisFirmansyah/UAS-PI/assets/121292416/7f4f7587-70c9-40be-b85e-904fdbf2b9b3)

## Membangun Profil Linkedin dan Mengikuti Akun-Akun Inspirasif Bertema Informatika ⭐⭐⭐

## Membangun Profil Github Page ⭐⭐⭐⭐⭐

## Mengikuti Workshop / Event / Course Terkait IT ⭐⭐⭐⭐

## Membaca dan Mengambil Inspirasi Dari Buku Bertema Informatika ⭐⭐⭐⭐⭐

