# ⚔️ Three Musketeers

Repository latihan **Git Merge** — tempat kami berlatih workflow branching, commit, dan resolve merge conflict secara kolaboratif.

## 👥 Anggota Tim

| Nama | NPM |
|---|---|
| Fadhlan Limanda | 2532066 |
| Lionel Jordan Chou | 2532058 |
| Vincent Cristiano Wistara | 2532036 |

## 🎯 Tujuan Latihan

Repo ini dibuat untuk mempraktikkan:

- Membuat dan mengelola branch masing-masing anggota
- Melakukan commit dengan pesan yang jelas
- Melakukan merge antar branch
- Menyelesaikan merge conflict jika terjadi

## 🌱 Alur Kerja (Workflow)

1. Setiap anggota bekerja di branch versi masing-masing:

   | Branch | Anggota |
   |---|---|
   | `v1` | Fadhlan Limanda |
   | `v2` | Lionel Jordan Chou |
   | `v3` | Vincent Cristiano Wistara |

   ```
   git checkout -b nama-branch
   ```
2. Setelah selesai mengerjakan perubahan, commit dan push:
   ```
   git add .
   git commit -m "deskripsi perubahan"
   git push origin nama-branch
   ```
3. Buat Pull Request ke branch `main` untuk direview sebelum di-merge.
4. Selesaikan conflict (jika ada) secara manual, lalu merge.

## 🛠️ Cara Menjalankan

```
git clone https://github.com/Vizzly-nM09/Latihan-Git-Merge.git
cd Latihan-Git-Merge
```

---

Dibuat sebagai bagian dari latihan kolaborasi menggunakan Git & GitHub.
