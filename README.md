# Patikadev-Merge

1. Merge Sort Aşamaları:

Verilen dizi: [16, 21, 11, 8, 12, 22]

Adımlar:
1. Bölme:
   - [16, 21, 11, 8, 12, 22]
   - [16, 21, 11] ve [8, 12, 22]
   - [16], [21], [11] ve [8], [12], [22]

2. Birleştirme:
   - Sol dizi: [16, 21, 11] -> [16, 21] -> [11, 16, 21]
   - Sağ dizi: [8, 12, 22] -> [8, 12] -> [8, 12, 22]
   - Son birleşim: [11, 16, 21] ve [8, 12, 22] -> [8, 11, 12, 16, 21, 22]

Sonuç: [8, 11, 12, 16, 21, 22]

---

2. Big-O Gösterimi:

Merge Sort'un zaman karmaşıklığı:
- Best Case: O(n log n)
- Average Case: O(n log n)
- Worst Case: O(n log n)
