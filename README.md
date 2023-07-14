# LADOCK_vina_1Ligand
Script untuk automatisasi proses docking banyak ligand menggunakan autodock-vina terhadap satu reseptor.

1. Buat direktori kerja
2. Tempatkan file-file input yang terdiri dari konfigurasi (config.txt), receptor.pdbqt dan ligand-ligand dalam format pdbqt.
3. Tempatkan file LADOCK_vina2lig.py pada direktori kerja.
4. Tempatkan file excecutable dari autodock-vina dan autodock-vina_split pada direktori kerja.
5. Buka file LADOCK_vina1lig.py menggunakan text editor.
6. Edit file config.txt sesuai dengan pengaturan simulasi yang Anda inginkan. Simpan.
7. Pada file LADOCK_vina2lig.py, tentukan file receptor. 
8. Simpan script.
9. Ubah script menjadi excecutable dengan perintah: chmod a+x LADOCK_vina2lig.py.
10. Eksekusi dengan perintah: python ./LADOCK_vina2lig.py atau python3 ./LADOCK_vina2lig.py
11. Model terbaik dengan energi terbaik dari setiap ligand atau kombinasi ligand dirangkum pada direktori "model1".
12. Energi terbaik dari hasil docking setiap ligand dirangkum pada file energy_summary.csv pada direktori "model1"
