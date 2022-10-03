# **Presentasi-minggu-2**

## **Javascript (Scope and Function)** 


 ### **Scope**
Hal pertama yang harus kita pahami mengenai scope pada javascript yaitu definisi nya terlebih dahulu, scope merupakan pembatas yang digunakan untuk membatasi pengaksesan suatu variabel. Scope pada javascript memiliki 2 jenis yaitu local scope dan global scope

 - Local scope
 Local scope merupakan sebuah jenis scope yang dimana variabel diletakan **diluar** sebuah function
 - Global scope
 - Local scope merupakan sebuah jenis scope yang dimana variabel diletakan **didalam** sebuah function

 ### Function
 Function sendiri merupakan sub-program yang dapat di panggil pada bagian lain dari sebuah program atau bisa dibilang sebuat prosedur yang dibuat untuk melakukan sebuah tugas tertentu pada sebuah bahasa pemograman. 
 ### Kenapa kita harus menggunakan function? 
 Penggunaan function merupakan sesuatu hal yang krusial pada sebuah bahasa pemograman karena berhubungan dengan *reusabillity* atau kita tidak perlu membuat perintah secara berulang dengan adanya function ini. 
### Jenis-jenis function
 - Built-in function 
Fungsi yang sudah disediakan oleh javascript contoh : toUppercase(), Split(), slice(), sin().....
 - User defined function
Fungsi yang dibuat oleh coder itu sendiri contoh : function (`parameter`){`berisi sebuah / kumpulan statement`; `return`}. 
Terdapat dua cara membuat sebuah user defined function yaitu :
	
	- Function declaration 
	function yang disimpan diluar sebuah variabel
	`function penguranganBilangan (num1, num2){
	var total;
	total = num1 - num2;
	return total; 
	}`
	- Function expression
	function yang disimpan dalam sebuah variabel
`var penguranganBilangan = function(num1, num2) { var total;
	total = num1 - num2;
	return total;
	}`

Pendeklarasian function dapat dilakukan dengan 2 cara yaitu dengan cara biasa dan arrow function
**Normal function**
![enter image description here](https://i.postimg.cc/wTvr0Dwf/function.png)
**Arrow function**
![enter image description here](https://i.postimg.cc/6qRfm5GQ/arrow-functuin.png)

	

 ## **Javascript (Data Type Built in Prototype and Method)** 
- ### Data Type
	Data type merupakan sebuah hal yang krusial pada sebuah bahasa pemograman karena berfungsi untuk mengoperasikan sebuah variabel.
- ### String
	String `("") dan ('')` merupakan salah satu jenis data yang terdapat pada javascript dimana jenis data ini berfungsi untuk merepresentasikan sebuah data bersifat tekstual. Method string pada javascript memiliki beberapa jenis contoh nya toUppercase, toLowerCase, Slice
	![enter image description here](https://i.postimg.cc/Pq5S9Xp5/string.png)
- ### Number
	Number merupakan salah satu jenis data yang dimana jenis data ini merepresentasikan data yang bersifat numerikal. pada Number terdapat methods yang bisa dilakukan seperti toFixed.. dan lainnya 
![enter image description here](https://i.postimg.cc/YCyjHRDB/method-number.png)Gamabr diatas merupakan beberapa contoh penggunaan number methods yang dimana `toFixed` berfungsi untuk mengambil berapa koma yang ingin kita ambil pada angka.
- ### Math
Math merupakan sebuah object methods merupakan sesuatu yang digunakan untuk menjalankan operasi matematika seperti `max()` `sin()` `sqrt()` dan beberapa operator lainnya.
- ### Primitive & Non Primitive
Primitive dan Non primitive merupakan tipe data pada javascript. Tipe data pada javascript dapat diklasifikasikan sebagai berikut: 
-   **Primitive**: (String, Boolean, Number, BigInt, Null, Undefined, Symbol )
-   **Non-Primitive**: Object (array, functions) 

Sebenarnya perbedaan dari kedua data tersebut terletak pada sifat nya yang dimana data **primitive** bersifat ***immutable*** atau bisa dibilang data tersebut tidak bisa dimodifikasi setelah kita deklarasikan, sementara data **non-primitive** bersifat ***mutable*** atau bisa dibilang data tersebut bisa kita modifikasi walaupun telah kita deklarasikan.
![enter image description here](https://i.postimg.cc/KY6h2q6V/prim-non-prim.png)
## **Javascript (DOM Manipulation)** 
DOM merupakan sebuah interface yang digunakan untuk memanipulasi keseluruhan dokumen HTML yang dimana memiliki properties dan methods untuk memanipulasi HTML tersebut. Terdapat cara untuk mengakses dokumen HTML pada javascript yaitu :

 - document.getElementById ()
 -  document.GetElementsByClassName ()
 - document.GetElementsByName ()
 -  document.GetElementsByTagName ()
 
 Menambah (Adding) 

 - document.createElement(element)  
 - document.appendChild(element)

 menghapus (removing) 

 - document.removeChild(element)

Kemudian tedapat beberapa properties yang digunakan yaitu :

 - innerHTML
 - innerText

**INTERAKSI USER (User Event)**

Sebuah website yang dinamis harus bisa menangkap interaksi user terhadap website tersebut karena user experience bersifat 2 arah, dalam JS DOM ini terdapat sebuah methods yang digunakan untuk membantu sebuah website agar bisa menangkap habbit user tersebut yaitu menggunakan `addeventlistener`


