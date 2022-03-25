# Tubes2_13520075
Tugas Besar 2 IF2211 Strategi Algoritma Semester II Tahun 2021/2022 
Pemanfaatan Algoritma BFS dan DFS dalam implementasi folder crawling

## Algoritma BFS dan DFS
### BFS ( Breadth-First Search )
Breadth-first search merupakan algoritma untuk mencari sebuah simpul dalam sebuah pohon yang mengandung nilai tertentu. BFS melakukan pengecekan pada semua kemungkinan simpul di kedalaman selanjutnya, baru setelah itu melakukan pengecekan untuk kedalaman selanjutnya.

Dalam hal ini, BFS melakukan iterasi untuk mencari file yang sesuai pada semua file yang ada di folder root. Jika belum ketemu, akan melakukan iterasi yang sama pada semua folder di dalam root dan begitu seterusnya.

terdapat dua opsi BFS, yakni pencarian seluruh simpul ataupun pencarian simpul pertama.

### DFS ( Depth-First Search ) 
Depth-first search merupakan algoritma untuk mencari sebuah simpul yang sesuai dalam sebuah pohon yansg mengandung nilai tertentu. DFS melakukan pengecekan pada salah satu cabang. Apabila belum ditemukan simpul sesuai, maka dilakukan rekursi pencarian DFS pada cabang tersebut. Apabila sudah tidak terdapat cabang lagi dan simpul sesuai belum ditemukan, maka dilakukan back-tracking dan melakukan DFS pada cabang yang lain.

Dalam hal ini, DFS melakukan pencarian rekursif dimulai dari root folder yang diberikan user, melakukan iterasi pada semua file yang terdapat pada root folder tersebut. Jika belum ditemukan, maka akan dilakukan pencarian DFS lagi pada salah satu folder dalam root folder tersebut, dan begitu seterusnya.

terdapat dua opsi DFS, yakni pencarian seluruh simpul ataupun pencarian simpul pertama.

## Environment Requirements
* C# [Download] (https://www.microsoft.com/en-us/download/details.aspx?id=7029)
* .NET Framework [Download] (https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.3-windows-x64-installer)
* Visual Studio [Download] (https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&cid=2030&passive=false)


## Setup


## Authors Information
| Nama | NIM | Email | 
| ---- | --- | ----- | 
| Samuel Christopher | 13520075 | 13520075@std.stei.itb.ac.id |
| Patrick Amadeus Irawan | 13520109 | 13520109@std.stei.itb.ac.id |
| Azmi Alfatih Shalahuddin | 13520158 | 13520158@std.stei.itb.ac.id |

## Referensi 
Munir, Rinaldi, Breadth First Search (BFS) dan Depth First Search (DFS) (Bagian 1) (Versi baru 2021) https://informatika.stei.itb.ac.id/~rinaldi.munir/Stmik/2020-2021/BFS-DFS-2021-Bag1.pdf.

Munir, Rinaldi, Breadth First Search (BFS) dan Depth First Search (DFS) (Bagian 2) (Versi baru 2021) https://informatika.stei.itb.ac.id/~rinaldi.munir/Stmik/2020-2021/BFS-DFS-2021-Bag2.pdf.
