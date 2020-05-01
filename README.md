# Ujian kelompok 8


## Anggota
Terdapat lima orang anggota pada kelompok 8 ini dengan fraksi kontribusinya pada pengerjaan tiap soal dapat dilihat dalam tabel berikut.

| NIM      | Nama                  | Peran pada soal (dan fraksi kontribusinya)   |
|----------|-----------------------|----------------------------------------------|
|          |                       |                                              |
| 10217003 | Ima Rahmadanti        | 1 (0.00) 2 (0.25) 3 (0.00) 4 (0.00) 5 (0.00) |
| 10217013 | Alika Rahma G.        | 1 (0.00) 2 (0.00) 3 (0.00) 4 (0.00) 5 (0.00) |
| 10217018 | Johnson Fernando      | 1 (0.50) 2 (0.00) 3 (0.00) 4 (0.00) 5 (0.00) |
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

	Substitusikan persamaan $F_{viskox} = 3 \eta \pi D \ddot{x}$ dan
	\eqref{eqn:tension} ke dalam persamaan \eqref{eqn:law-newton-2-x}, maka

	\begin{equation}
	\label{eqn:law-newton-3-x}
	- m g \sin \theta \cos \theta + \left(\frac{m v^2}{l} \right) \cos \theta 
	- 3 \eta \pi \D \dot{x} = m \ddot{x}
	\end{equation}

	Substitusikan $\cos \theta = \frac{x}{l}$ dan $\sin \theta = \frac{y}{l}$
	ke dalam persamaan \eqref{eqn:law-newton-3-x} sehingga akan didapat

	\begin{equation}
	\label{eqn:nlode-x}
	\ddot{x} + \left( \frac{3 \pi \eta D}{m} \right) \dot{x} - \left(\frac{1}
	{l^2}\right) (\dot{x}^2 + \dot{y}^2) x + \left( \frac{g}{l^2}\right) xy = 0
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

	Substitusikan persamaan $F_{viskoy} = 3 \eta \pi D \ddot{y}$, \eqref{eqn:tension},
	dan $\sin \theta = \frac{y}{l}$, sehingga akan didapat

	\begin{equation}
	\label{eqn:nlode-y}
	\ddot{y} + \left( \frac{3 \pi \eta D}{m} \right) \dot{y} + \left(\frac{1}{l^2}
	\right) (\dot{x}^2 + \dot{y}^2) y - \left( \frac{g}{l^2}\right) y^2 = -g.
	\end{equation}

### b

Jawaban pada soal berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Persamaan diferensial non-linier memiliki beberapa suku yang menyebabkan persamaan
	diferensial yang didapatkan tidak linier. Pada suku turunan pertama ($\dot{x}$ dan
	$\dot{y}$), didapati koefisien berupa besaran gaya gesek udara yang artinya nilai percepatan
	bandul sangat dipengaruhi oleh besarnya gesekan udara. Pada suku selanjutnya, yaitu suku
	dengan koefisien $\left(\frac{1}{l^2} \right) (\dot{x}^2 + \dot{y}^2)$, maka suku ini
	berhubungan dengan panjang tali serta nilai kecepatan pada sumbu x dan sumbu y. Adapun pada
	suku terakhir, persamaan diferensial non-linear pada $x$ berupa $\left( \frac{g}{l^2}\right)
	xy$ dan pada $y$ berupa $- \left( \frac{g}{l^2}\right) y^2 + g$ sebenarnya merupakan nilai
	konstanta yang dipengaruhi oleh perubahan sudut simpangan yang diberikan.

### c

Jawaban pada soal berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Untuk benda jatuh bebas, maka nilai $\sin \theta \approx 1$ sehingga $l \approx y$.
	Hal ini dikarenakan nilai $\theta$ dapat dianggap sebesar $\frac{\pi}{2}$.
	<br /><br />
	
	Karena benda bergerak tanpa mengalami gaya gesekan udara, maka nilai 
	$\eta = 0$. Hal ini dikarenakan viskositas berbanding lurus dengan
	gaya gesek.
	<br /><br />
	
	Dengan demikian, maka didapatkan persamaan differensial non-linear pada arah $x$
		
	\begin{equation}
	\label{eqn:nlode-x}
	\ddot{x} = \left(\frac{1}{y} \right) \left(\frac{(\dot{x}^2 + \dot{y}^2)}{y} +
	g \right) x
	\end{equation}

	dan $y$

	\begin{equation}
	\label{eqn:nlode-y}
	\ddot{y} = - \left(\frac{1}{y} \right) (\dot{x}^2 + \dot{y}^2)
	\end{equation}

### d

Jawaban pada soal berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Untuk bandul dengan simpangan kecil ($\theta \approx 0$), maka nilai $\sin \theta
	\approx \theta$.
	<br /><br />
	
	Karena benda bergerak tanpa mengalami gaya gesekan udara, maka nilai 
	$\eta = 0$. Hal ini dikarenakan viskositas berbanding lurus dengan
	gaya gesek.
	<br /><br />
	
	Dengan demikian, maka didapatkan persamaan differensial non-linear pada arah $x$
		
	\begin{equation}
	\label{eqn:nlode-x}
	\ddot{x} = \left(\frac{1}{l} \right) \left(\frac{(\dot{x}^2 + \dot{y}^2)}{l} +
	g \theta \right) x
	\end{equation}

	dan $y$

	\begin{equation}
	\label{eqn:nlode-y}
	\ddot{y} = \left(\frac{\theta}{l}\right) (\dot{x}^2 + \dot{y}^2) + (\theta^2 - 1) g
	\end{equation}
	
	

## Soal 2 | Bandul dengan sistem koordinat polar

### a

Jawaban pada soal berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Persamaan diferensial sistem bandul pada arah $\theta$ didapatkan sebagai berikut.

	\begin{equation}
	\label{eqn:law-newton-1-theta}
	\sum F = m a
	\\
	\sum F = W = -mg \sin \theta
	\\
	m a = - m g \sin \theta
	\end{equation}

	sehingga didapatkan sebagai berikut.

	\begin{equation}
	\label{eqn:law-newton-2-theta}
	a = - g \sin \theta
	\end{equation}

	Diketahui bahwa $s$ adalah jalur bandul yang didapatkan melalui hubungan $s=l \theta$,
	dengan $l$ adalah panjang tali, dan $\theta$ adalah sudut yang yang dibentuk oleh tali
	dan garis vertikal (sumbu y).
	<br /><br />
	
	Jalur bandul $s$, dapat menghasilkan persamaan sebagai berikut.

	\begin{equation}
	\label{eqn:law-newton-3-theta}
	s=l\theta
	\\
	v=\frac{ds}{dt}=l\frac{d\theta}{dt}
	\\
	a=\frac{d^2 s}{dt^2}=l\frac{d^2 \theta}{dt^2}
	\end{equation}

	Subsitusi percepatan $a$ pada persamaan \eqref{eqn:law-newton-3-theta} ke ersamaan
	\eqref{eqn:law-newton-2-theta} menghasilkan sebagai berikut.

	\begin{equation}
	\label{eqn:law-newton-4-theta}
	l\frac{d^2 \theta}{dt^2}=-g\sin\theta
	\\
	\frac{d^2 \theta}{dt^2}+\frac{g}{l}\sin\theta=0
	\end{equation}

	dan dihasilkan persamaan diferensial sistem bandul pada arah $\theta$.

	\begin{equation}
	\label{eqn:law-newton-5-theta}
	\ddot{\theta} + \left( \frac{g}{l} \right) \sin \theta = 0
	\end{equation}

	Sedangkan persamaan diferensial sistem bandul pada arah $r$ didapatkan sebagai berikut.

	\begin{equation}
	\label{eqn:law-newton-6-theta}
	\sum F_r = 0
	\\
	\frac{m v^2}{l}+lg\cos\theta-\frac{Tl}{m}=0
	\end{equation}

	Diketahui bahwa $v=\ddot{\theta}$, sehingga persamaan \eqref{eqn:law-newton-6-theta}
	dapat dituliskan sebagai berikut.

	\begin{equation}
	\label{eqn:nlode-theta}
	l^2 \dot{\theta}^2 + lg\cos\theta - \frac{Tl}{m}=0
	\\
	\dot{\theta}^2 + \frac{g}{l}\cos\theta - \frac{T}{lm}=0
	\end{equation}

	Dan dihasilkan persamaan diferensial sistem bandul pada arah $r$.

	\begin{equation}
	\label{eqn:nlode-r}
	\dot{\theta}^2 + \frac{g}{l}\cos\theta = \frac{T}{lm}
	\end{equation}

### b

Jawaban pada soal berikut akan lebih jelas dilihat dalam [editor](https://rawcdn.githack.com/dudung/jsxphys/4220729be109df8b94729ca4605562caa6d7596b/0.0.2/editor.html).

	Untuk nilai $\theta$ yang kecil, $\sin \theta \approx \theta$.
	Maka persamaan diferensial pada $\theta$ dapat dituliskan sebagai berikut.

	\begin{equation}
	\label{eqn:theta-1}
	\ddot{\theta} + \left( \frac{g}{l} \right) \theta = 0
	\\
	\ddot{\theta} = - \left( \frac{g}{l} \right) \theta
	\\
	\frac {d^2\theta} {dt^2} = - \left( \frac{g}{l} \right) \theta
	\end{equation}

	Persamaan \eqref{eqn:theta-1} memiliki solusi sebagai berikut.

	\begin{equation}
	\label{eqn:theta-2}
	\theta(t) = \theta_0 \cos \left( \sqrt \frac{g}{l} t + \delta \right) = 0
	\end{equation}

	dengan $\theta_0$ dan $\delta$ adalah suatu konstanta yang bergantung pada kondisi
	awal. $\theta_0$ adalah amplitudo, dan $\delta$ adalah konstanta fasa.
	<br /><br />
	
	Persamaan diferensial pada $\theta$ untuk nilai $\theta$ kecil, dapat pula dituliskan
	sebgai berikut.

	\begin{equation}
	\label{eqn:t-1}
	\ddot{\theta} + \left( \frac{g}{l} \right) \theta = 0
	\\
	\ddot{\theta} + \omega^2 \theta = 0
	\end{equation}

	dengan $\omega$ adalah $\sqrt \frac{g}{l}$, maka didapatkan sebagai berikut.

	\begin{equation}
	\label{eqn:t-2}
	T = \frac {2 \pi}{\omega} = 2 \pi \sqrt \frac{l}{g}
	\end{equation}

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
