### **1. Mean (Rata-rata)**

**Definisi**: Nilai rata-rata dari sekumpulan data.  
**Rumus**:

$$
overline(x)= (x_1 + ... + x_i)/n
$$

- $x_i$​: Nilai data ke-$i$.
    
- $n$: Jumlah data.
    

**Contoh**:  
Data: 4, 5, 6, 6, 8

$$
overline(x) &= (4 + 5 + 6 + 6 + 8)/5 \
            &= #{4 + 5 + 6 + 6 + 8}/5 \
            &= #{(4 + 5 + 6 + 6 + 8)/5}
$$

---

### **2. Median (Nilai Tengah)**

**Definisi**: Nilai yang membagi data terurut menjadi dua bagian sama besar.

**Langkah**:

1. Urutkan data dari terkecil ke terbesar.
    
2. Jika $n$ **ganjil**:

	$$
	M e = x_((n+1)/2)
	$$
    
3. Jika $n$ **genap**: Median = rata-rata dua nilai tengah.

	$$
	M e = (x_(n/2) + x_(n/2 + 1))/2
	$$

**Contoh**:

- Data ganjil: 3, 5, 7

	$$
	M e &= x_((3+1)/2) arrow "karena ganjil" \
	    &= x_2 \
	    &= 5
	$$
	<br>
    
- Data genap: 2, 4, 6, 8

	$$
	M e &= (x_(4/2) + x_(4/2+1))/2 arrow "karena genap" \
		&= (4 + 6)/2 \
		&= 10/2 \
		&= 5
	$$
    

---

### **3. Modus**

**Definisi**: Nilai yang paling sering muncul dalam data.  
**Contoh**:

- Data: 2, 3, 3, 5, 6 → Modus = **3**.
    
- Data: 1, 2, 2, 3, 3 → Modus = **2 dan 3** (bimodal).
    
- Data: 1, 2, 3 → Tidak ada modus.
    

---

### **4. Jangkauan (Range)**

**Definisi**: Selisih antara nilai maksimum dan minimum.  
**Rumus**:

$$
r = max x - min x
$$

**Contoh**:  
Data: 10, 15, 20, 25, 30

$$
r &= 30 - 10 \
  &= 20
$$

---

### **5. Kuartil (Q1, Q2, Q3)**

**Definisi**: Nilai yang membagi data terurut menjadi 4 bagian sama besar.

- **Q1 (Kuartil bawah)**: Median separuh data pertama.
    
- **Q2 (Median)**: Nilai tengah seluruh data.
    
- **Q3 (Kuartil atas)**: Median separuh data kedua.
    

**Langkah Menentukan Kuartil**:

1. Urutkan data.
    
2. Tentukan posisi kuartil:
		$$
		Q_i = x_((i(n + 1))/4) "dimana" i = 1 "/" 2 "/" 3
		$$<br>
    - Jika posisi bukan bilangan bulat, lakukan interpolasi.
        

**Contoh**:  
Data: 5, 7, 8, 10, 12, 15, 17 ($n=7$)

$$
Q_1 &= x_((1(7 + 1))/4) = x_2 = 7 \
Q_2 &= x_((2(7 + 1))/4) = x_4 = 10 \
Q_3 &= x_((3(7 + 1))/4) = x_6 = 15
$$