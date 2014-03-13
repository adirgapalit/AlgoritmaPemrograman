Welcome to the AlgoritmaPemrograman wiki!

(1)
PROGRAM penetuan_bilangan

DEKLARASI :
	n,  : integer;

ALGORITMA :
	write (n)
	while n > 0, do
		if (n mod 4= 0) then
		n adalah kelipatan 4
	endwhile
	write (n)

(2)
PROGRAM harga_belanja

DEKLARASI :
	harga, total : integer;
	diskon : real;


ALGORITMA :
	write (harga)
	while harga > 100000, do	
		total <- harga-diskon
	endwhile
	write (total)
(3)
PROGRAM urut_3_bilangan

DEKLARASI :
	a,b,c : integer;
	bilangan_bulat :string;

ALGORITMA :
	read (a, b, c)
	while a,b,c adalah 'bilangan_bulat' do
		if a>b>c then 
		write ('urutan adalah c,b,a')

		else if b>c>a then
		write ('urutan adalah a,c,b')

		else if c>b>a then
		write ('urutan adalah a,b,c')
		
		else if a>c>b then
		write ('urutan adalah b,c,a')
		
		else if b>a>c then
		write ('urutan adalah c,b,a')

		else if c>a>b then
		write ('urutan adalah b,a,c')
		
		endif
		endif
		endif
		endif
		endif
		endif
		
	endwhile

(4)
PROGRAM membaca panjang

DEKLARASI
	a,b,c :integer

ALGORITMA
	read (a,b,c)
	while (a<= b<= c) do
	if (a=b=c) then
	write ('segitiga sama sisi')

	else if (a < b and b=c) then
	write ('segitiga lancip')

	else if (a > b and a > c) then
	write ('segitiga tumpul')

	endif
	endif
	endif

	endwhile

(5)
PROGRAM karakter_digit

DEKLARASI
	angka : char

ALGORITMA
	read (angka)

	case angka
	'1' : 1
	'2' : 2
	'3' : 3
	'4' : 4
	'5' : 5
	'6' : 6
	'7' : 7
	'8' : 8
	'9' : 9
	otherwise : -99
	endcase
	
(6)
PROGRAM pembulatan_rendah

DEKLARASI
	harga : integer
	pec_terkecil : integer {pecahan terkecil dari harga}
	harga_bulat
	
ALGORITMA
	read (harga)
	while harga > 0 do

	if (0 > pec_terkecil < 25 'or' 26 > pec_terkecil < 50 ) then
	(harga dibulatkan ke pecahan terendah)
	end if
	
	endwhile
	
	write (harga_bulat)

(7)
PROGRAM konversi

DEKLARASI
	x : integer

ALGORITMA
	read (x)
	while x > 0 do
	case x
	1 : 'I'
	2 : 'II'
	3 : 'III'
	4 : 'IV'
	5 : 'V'
	6 : 'VI'
	7 : 'VII'
	8 : 'VIII'
	9 : 'IX'
	10 : 'X'
	endcase
	endwhile	
	


(8)
PROGRAM clipping

DEKLARASI
	hasil_operasi, nilai_potong : integer

ALGORITMA
	read (hasil_operasi)
	
	if (hasil_operasi > 255)  then
	nilai_potong = 255

	else if (pixel < 0) then
	nilai potong = 0

	endif	

(9)
PROGRAM berat_ideal

DEKLARASI
	berat, tinggi : real
	berat_ideal : integer
	
ALGORITMA
	read (berat, tinggi)
	if  2 <- berat_ideal-berat 'or' -2 <-berat_ideal-berat then
	write ("ideal")
	
	else write ("tidak ideal")

	endif

	
	
	

	
		



	
	