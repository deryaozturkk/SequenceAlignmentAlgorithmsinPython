# SequenceAlignmentAlgorithmsinPython
Bu proje, global ve lokal hizalama algoritmalarını gerçekleştiren bir programı içermektedir.

## Özet

Bu projede, Python programlama dilinde global ve lokal hizalama algoritmaları kodlanmıştır. Kütüphane kullanılmadan, dinamik programlama yöntemiyle iki dizi arasındaki en iyi hizalamayı bulmaktadır. Global hizalama, eşleşme, uyuşmazlık ve boşluk skorlarını kullanarak iki dizi arasında en iyi hizalamayı bulurken, lokal hizalama en iyi hizalamayı bulmak için skor matrisi ve geri izleme matrisi kullanmaktadır.

## Kullanım

Program, Python 3.x sürümleriyle uyumlu olarak çalışır.

- `global_alignment(seq1, seq2, match_score, mismatch_penalty, gap_penalty)`: İki diziyi global olarak hizalar ve hizalama sonuçlarını, hizalama puanını ve dinamik programlama matrisini döndürür.
- `local_alignment(s1, s2, match, mismatch, gap)`: İki diziyi lokal olarak hizalar ve hizalama sonuçlarını ve hizalama puanını döndürür.
