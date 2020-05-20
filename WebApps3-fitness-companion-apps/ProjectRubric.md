### Projects Submission

#### Project Submission Checklist

> **Untuk bisa lulus di projek ini, kamu harus memenuhi minimal 10 dari 14 kriteria**

- Saya yakin semua item rubrik yang ada telah sesuai persyaratan dan proyek saya akan lolos untuk di-review \(Jika tidak, saya akan berdiskusi dengan mentor sebelum men-submit.\)
- Project dibuat dengan benar tanpa error.
- Semua kebutuhan fungsional terpenuhi dan projek saya mampu berjalan sesuai dengan persyaratan yang ada.

Jika semua hal di atas terpenuhi, projek kamu sudah bisa di-submit.

### Project Rubric

| Application Setup                                                                   |                                                                                                                                                                                                   |
| :---------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CRITERIA                                                                            | SPECIFICATIONS                                                                                                                                                                                    |
| Apakah aplikasi ini mudah diatur?                                                   | Aplikasi ini dibuat dengan CSS dan JS terpisah di setiap folder. Index.html adalah entry point menuju website. Lebih baik lagi jika website ini berbebntuk SPA                                    |
| Apakah aplikasi memiliki README dengan panduan instalasi dan penggunaan yang jelas? | README yang ter-update sudah termasuk pada aplikasi ini, di mana README ini menjelaskan proyek, serta memberikan instruksi untuk me-maintain dan memodifikasi proyek.                             |
| Apakah aplikasi menggunakan vue-router?                                             | Vue-router digunakan untuk menampilkan detail dari card yang ada di Heroes Workout.                                                                                                               |
| Apakah aplikasi menerapkan konsep SPA (Single Page Aplication) pada vue?            | SPA menggunakan component base dalam pembangunan user interfacenya, di mana semua component akan ditampilkan ke dalam single file yaitu index.html, sesuai kebutuhan.                             |
| Apakah aplikasi menggunakan nodemon di express.js?                                  | Nodemon menjadikan server otomatis direload setiap kali ada perubahan yang terjadi di sisi server.                                                                                                |
| Apakah aplikasi menggunakan middleware CORS (Cross-origin resource sharing)?        | CORS middleware digunakan untuk mengatasi perbedaan domain yang terjadi. Di mana jika tidak menggunakan CORS Middleware, ke dua aplikasi tidak bisa saling bertukar informasi.                    |
| Apakah aplikasi menggunakan axios untuk mem-fetching data dari server?              | Axios digunakan untuk menggantikan peran fetch API. Salah satu keuntungan menggunakan axios, website tidak perlu repot-repot lagi mengatur headers HTTP client untuk melakukan request ke server. |

| Personal Workout Page                                                                        |                                                                                                                                                                           |
| :------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CRITERIA                                                                                     | SPECIFICATIONS                                                                                                                                                            |
| Apakah halaman Personal Workout menampilkan checkbox dengan semua data Personal Workout nya? | Halaman Personal Workout menampilkan list semua data Personal Workout, di mana list tersebut berbentuk checkbox yang isinya semua data Personal Workout, dan bisa diklik. |

| Heroes Workout Page                                      |                                                                                                                           |
| :------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------ |
| CRITERIA                                                 | SPECIFICATIONS                                                                                                            |
| Apakah halaman Heroes menunjukkan daftar Heroes Workout? | The Heroes Page menunjukkan daftar semua workout. Setiap workout menunjukkan konten yang benar, title, dan button detail. |
| Apakah Heroes Page memiliki search bar?                  | Ya, Heroes Work harus mempunyai search bar.                                                                               |

| Code Functionality                                |                                                                                                                                                                                                                                  |
| :------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CRITERIA                                          | SPECIFICATIONS                                                                                                                                                                                                                   |
| Apakah search berfungsi?                          | Fungsi search pada search bar bekerja saat user mengetik karakter apapun pada search bar. Di saat yang sama, workout yang muncul akan ter-filter sesuai dengan input tadi.                                                       |
| Apakah button detail pada Heroes Workout bekerja? | Button tersebut akan bekerja ketika ada interaksi yang menampilkan modal ataupun page baru, di mana modal dan page tersebut berisikan detail dari Heroes Workout.                                                                |
| Apakah halaman navigasi bekerja?                  | User dapat bernavigasi dari main page ke Personal ataupun Heroes Workout tanpa halangan. Begitu juga sebaliknya.                                                                                                                 |
| Apakah kode yang ada berjalan tanpa error?        | Ya, kode yang ada dapat berjalan tanpa error. Tidak ada peringatan yang menunjukkan tanda error, karena daftar yang ada pada dokumentasi sudah termasuk best practice. Semua kode bersifat fungsional dan terformat dengan baik. |
