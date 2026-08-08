<div align="center">
  <h1>📐 Euclidean Distance Calculator</h1>
  <p><i>Coordinate Geometry & Distance Algorithm in Python<br>Python ile Koordinat Geometrisi ve Mesafe Algoritması</i></p>
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
</div>

<br>

## 🇬🇧 English

A focused Python script written to calculate the Euclidean distance between multiple coordinates in a 2D space. It demonstrates mathematical computing and nested loop structures.

### 🧠 Algorithmic Approach
- **Mathematical Formula**: Implements the standard Euclidean distance formula `√((x2 - x1)² + (y2 - y1)²)` utilizing Python's built-in `math.sqrt()` function.
- **Permutation Checking**: Uses a nested `for` loop (`for j in range(i + 1, len(points))`) to calculate the distance between *every unique pair* of points provided in a list of tuples without duplicating the checks.
- **Optimization**: Appends all distances to an array and uses the built-in `min()` function to rapidly find the closest pair of coordinates.

---

## 🇹🇷 Türkçe

2 boyutlu uzayda (2D space) verilen birden fazla koordinat noktası arasındaki Öklid (Euclidean) mesafesini hesaplamak için yazılmış Python betiği. Matematiksel hesaplama ve iç içe döngü yapılarını göstermek için ideal bir projedir.

### 🧠 Algoritmik Yaklaşım
- **Matematiksel Formül**: Standart Öklid mesafe formülü olan `√((x2 - x1)² + (y2 - y1)²)` işlemini, Python'un yerleşik `math.sqrt()` fonksiyonunu kullanarak koda döker.
- **Kombinasyon Kontrolü**: İç içe geçmiş bir `for` döngüsü (`for j in range(i + 1, len(points))`) kullanarak, verilen koordinat listesindeki *her benzersiz nokta çifti* arasındaki mesafeyi, işlemleri tekrarlamadan hesaplar.
- **Optimizasyon**: Tüm mesafeleri bir listeye ekler ve birbirine en yakın iki noktayı bulmak için `min()` fonksiyonunu kullanarak sonucu en hızlı şekilde yazdırır.
