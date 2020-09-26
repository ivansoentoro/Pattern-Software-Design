# Pattern-Software-Design

## TokoBeDia
Project ini dibuat untuk Assignment mata kuliah Pattern Software Design 
Website untuk e-commerce dengan fitur sebagai berikut:
* Guest
  * Register
  * Login (Data - data user disimpan menggunakan session)
  * View Product
* Member
   * View Product
   * Profile
   * Change Password
* Administrator
   * View User
   * View Product
   * Insert Product
   * Update Product
   * View Product Type
   * Insert Product Type
   * Update Product Type
   * Profile
   * Update Profile
   * Change Password

Link [Download Project](https://drive.google.com/file/d/1XZB1thZJcexwLuw_ycZbD4r2O3rANK1c/view?usp=sharing)
Untuk menjalankan project buka file 2201762976_Assignment pada Visual Studio 2015

## HabitTracker
Project ini dibuat untuk Ujian Akhir Semester mata kuliah Pattern Software Design project ini tidak memiliki interface, program ini menggunakan API dengan route sebagai berikut:
 Project ini dibuat untuk melakukan track sebuah habit yang dimiliki usernya
 *[HttpGet("api/v1/users/{userID}/habits")]
 *[HttpGet("api/v1/users/{userID}/habits/{id}")]
 *[HttpPost("api/v1/users/{userID}/habits")] -> membutuhkan data nama habit dan string hari libur
 *[HttpPut("api/v1/users/{userID}/habits/{id}")] -> membutuhkan data nama habit baru karena mengupdate nama habit
 *[HttpDelete("api/v1/users/{userID}/habits/{id}")]
 *[HttpPost("api/v1/users/{userID}/habits/{id}/logs")]
