# Ujian kelompok 0


## Anggota
Terdapat lima orang anggota pada kelompok 0 ini dengan fraksi kontribusinya pada pengerjaan tiap soal dapat dilihat dalam tabel berikut.

| NIM      | Nama                  | Peran pada soal (dan fraksi kontribusinya)   |
|----------|-----------------------|----------------------------------------------|
|          |                       |                                              |
| 10217003 | Ima Rahmadanti        | 1 (0.00) 2 (0.25) 3 (0.00) 4 (0.00) 5 (0.00) |
| 10217013 | Alika Rahma G.        | 1 (0.00) 2 (0.00) 3 (0.00) 4 (0.00) 5 (0.00) |
| 10217018 | Johnson Fernando      | 1 (0.00) 2 (0.00) 3 (0.00) 4 (0.00) 5 (0.00) |
| 10217057 | Ighfar Hasbi A.       | 1 (0.00) 2 (0.00) 3 (0.00) 4 (0.00) 5 (0.00) |
| 10217065 | Pangeran Niti K.      | 1 (0.25) 2 (0.00) 3 (0.00) 4 (0.00) 5 (0.00) |
|          |                       |                                              |
|          | Total                 | 1 (1.00) 2 (1.00) 3 (1.00) 4 (1.00) 5 (1.00) |



# Jawaban

## Soal 1 | Sistem bandul dengan sistem koordinat kartesian

### a
Jawaban berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Didapatkan persamaan dalam setiap arah gerak bandul sebagai berikut,
	untuk gerak sumbu $x$:

	\begin{equation}
	\label{eqn:law-newton-1-x}
	\sum F_x = m \ddot{x}
	\end{equation}

	Pertama-tama, dapat ditemukan hubungan

	\begin{equation}
	\label{eqn:law-newton-2-x}
	T \cos \theta - F_{viskox} = m \ddot{x}
	\end{equation}

	Jika dianalisa gaya searah dengan vektor dari r, maka

	\begin{equation}
	\label{eqn:tension}
	T = m g \sin \theta + \frac{m (\dot{x}^2 + \dot{y}^2)^2}{l}
	\end{equation}	

	Substitusikan persamaan $F_{viskox} = 3 \eta \pi D \ddot{x}$ dan \eqref{eqn:tension} ke dalam persamaan \eqref{eqn:law-newton-2-x}, maka

	\begin{equation}
	\label{eqn:law-newton-3-x}
	- m g \sin \theta \cos \theta + \left(\frac{m v^2}{l} \right) \cos \theta - 3 \eta \pi \D \dot{x} = m \ddot{x}
	\end{equation}

	Substitusikan $\cos \theta = \frac{x}{l}$ dan $\sin \theta = \frac{x}{l}$ ke dalam persamaan \eqref{eqn:law-newton-3-x} sehingga akan didapat

	\begin{equation}
	\label{eqn:nlode-x}
	\ddot{x} + \left( \frac{3 \pi \eta D}{m} \right) \dot{x} - \left(\frac{1}{l^2} \right) (\dot{x}^2 + \dot{y}^2) x + \left( \frac{g}{l^2}\right) xy = 0
	\end{equation}

	Selanjutnya, akan diturunkan persamaan gerak untuk sumbu y, dimana

	\begin{equation}
	\label{eqn:law-newton-1-y}
	\sum F_y = m \ddot{y}
	\end{equation}

	Dapat dilihat gaya yang bekerja di sumbu y adalah

	\begin{equation}
	\label{eqn:law-newton-2-y}
	T \sin \theta - mg - F_{viskoy} = m \ddot{x}
	\end{equation}

	Substitusikan persamaan $F_{viskoy} = 3 \eta \pi D \ddot{y}$, \eqref{eqn:tension}, dan $\sin \theta = \frac{x}{l}$, sehingga 	akan didapat

	\begin{equation}
	\label{eqn:nlode-y}
	\ddot{y} + \left( \frac{3 \pi \eta D}{m} \right) \dot{y} + \left(\frac{1}{l^2} \right) (\dot{x}^2 + \dot{y}^2) y - \left( \frac{g}{l^2}\right) y^2 = -g.
	\end{equation}

### b

### c


## Soal 2 | Bandul dengan sistem koordinat polar

### a

### b

### c

### d
Kode program berikut

```C++
/*
	NamaProgram.cpp
	
	Menghitung sesuatu
*/

int main(int argc, char *argv[]) {
}
```

dapat dijalankan secara daring menggunakan [http://cpp.sh/](http://cpp.sh/) atau aplikasi lainnya.

## Soal 3 | Jaringan saraf tiruan dengan aplikasi TensorFlow

### a

### b

### c

### d


## Soal 4 | Algoritma genetik sederhana dengan JS

### a
Fungsi yang dimaksud adalah

```JavaScript
// Get interpretation of position and group from chromosome
function getValues() {
	var p = arguments[0];
	
	var xs = p.slice(0, 3);
	var ys = p.slice(3, 6);
	var gs = p.slice(6);
	
	var x = -1;
	var y = -1;
	var g = -1;
	
	/*
	x = xs;
	y = ys;
	g = gs;
	*/
	
	return [x, y, g];
}
```

dengan .. (penjelasannya).

### b

### c

### d


## Soal 5 | Research based learning

### a Tujuan

### b Rumusan masalah

### c Metode

### d Hasil dan diskusi

### e Referensi
1. Penulis, "Judul", Website, ..
2. Penulis, "Judul", Journal, vol. no., pp. Bulan Tahun, DOI ..
