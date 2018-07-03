# Hacktiv8-Pseudocode-Challenge
Hacktiv8 Phase 0 Week 2: The World of JavaScript > Senin - Pengenalan Programming, Algoritma, dan Pseudocode

Pseudocode Challenge
Soal ini terdiri dari 4 nomor!

1. Newton Second Law
	Bunyi hukum II Newton adalah:

	Percepatan sebuah benda akan sebanding dengan gaya yang diberikan pada benda dan berbanding terbalik dengan massa benda. Arah percepatan benda sama dengan arah gaya total yang diberikan pada benda.

	Secara matematis hukum II Newton dirumuskan sebagai berikut: ΣF = m x a

	ΣF = resultan gaya (Newton)

	m = massa benda (kg)

	a = percepatan benda (m/s2)

	Berdasarkan keterangan di atas, buatlah sebuah algoritma / pseudocode untuk menghitung resultan gaya pada sebuah mobil yang memiliki massa benda 600 kg dan ketika didorong oleh tiga orang percepatannya adalah 2 m/s2!

Jawaban Newton Second Law:

	a. Algoritma Newton Second Law

			Step 1 : Identify weight of the car (masa benda dalam satuan kg)
			
			Step 2 : Identify acceleration of the car 
			
			Step 3 : nultiply the weight of the car with acceleration of the car to get the net force of the car.

	

	b. Pseudocode Newton Second Law

			1. READ weight of the car
			2. READ acceleration of the car
			3. COMPUTE net force of the car movement as weight of the car multiply by acceleration of the car



2. Tahun Kabisat
	Apa yang kamu ketahui tentang tanggal 29 Februari? Kamu pasti tahu jika suatu tahun memiliki tanggal 29 Februari berarti tahun tersebut merupakan tahun kabisat.

	Dalam kalender Gregorian, tahun kabisat memiliki beberapa kriteria yaitu antara lain:

	Jika tahun habis di bagi 4 dan tidak habis di bagi 100, dan
	Jika tahun habis di bagi 4, habis di bagi 100 dan habis di bagi 400
	Buatlah algoritma & pseudocode untuk menentukan apakah suatu tahun merupakan tahun kabisat atau bukan!

Jawaban Tahun kabisat:

	a. Algoritma Tahun kabisat 
		1. Pick the gregorian year you would to identify as leap year (tahun kabisat)
		2. Clarify the leap year by calculate it in the following step :
			a. divide the year by 4, if there is remainder of the division then it is not leap year, if there is no remainder then
			b. divide the year by 100, if there is remainder of the division then it is leap year, if there is no remainder then
			c. divide the year by 400, if there is remainder of the division then it is not leap year, if there is no remainder then it is a leap year


	b. Pseudocode Tahun kabisat 
		1. OBTAIN the gregorian year
		2. COMPUTE gregorian year by divide it with 4
			a. IF 	gregorian year / 4 with remainder THEN
					PRINT "NOT LEAP YEAR"
				ELSE IF gregorian year / 4 without remainder THEN
					COMPUTE gregorian year / 100
						IF gregorian year / 100 with remainder THEN
							PRINT "LEAP YEAR"
							ELSE IF gregorian / 100  without remainder THEN
							 COMPUTE gregorian year / 400
							 IF gregorian year / 400 with remainder THEN
							 PRINT "NOT LEAP YEAR"
							 ELSE PRINT "LEAP YEAR"
						

3. Laundry Day
	Foxie akan mencuci pakaiannya menggunakan mesin cuci. Pakaian yang akan dicuci oleh Foxie sebanyak 20 dan akan dimasukkan ke mesin cuci. Mesin cuci akan dinyalakan jika semua pakaian Foxie sudah masuk ke mesin cuci.

	Bantulah Foxie untuk menghitung jumlah pakaian yang akan dimasukkan ke mesin cuci menggunakan algoritma & pseudocode perulangan!

	1. Algoritma Laundry Day
			a. Prepare the clothes
			b. Prepare the washing machine detergent
			c. Insert the clothes one by one into the washing machine
			d. Insert adequate level of water into washing machine
			e. Start the washing machine to wash the clothes
	
	2. Pseudocode Laundry Day
			a. OBTAIN the clothes
			b. GET washing machine detergent
			c. FOR clothes = 1 to 20
					INSERT clothes into washing machine
				END FOR
			d. GET water into washing machine
			e. SET washing machine to START


4. Periksa Kuku
	Seorang guru akan memeriksa kuku siswa-siswinya yang sebanyak 40 orang dengan cara berkeliling kelas. Jika guru menemukan siswa/siswi yang memiliki kuku yang panjang maka guru akan menghukum siswa/siswi tersebut, jika tidak guru akan memuji siswa/siswi tersebut.

	Buatlah algoritma & pseudocode untuk permasalahan diatas.
	
	1. Algoritma Periksa Kuku
		a. Teacher instruct the student to put the student finger on the desk
		b. Teacher observe the nail of the student one by one per desk
			if the student nail is long then the teacher will punish the student 
			if the student nail is not long then the teacher will give compliment to the student
			
	2. Pseudocode
		a. GET the student to put the finger on the desk
		b. INIT the inspection of the student nail
		c. FOR student = 1 to 40
				DETERMINE the length of the student nail
				IF student nail long THEN
					INIT punishment to the student
				ELSE
					INIT compliment to the student
				END IF
		d. END Inspection of the student nail
