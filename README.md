# MineSweeperProject

Bu proje, Java 21 kullanılarak geliştirilen klasik Mayın Tarlası oyununun text tabanlı bir versiyonudur.

## Oyunun Amacı

Oyunun amacı, mayınlarla dolu bir alanda tüm boş kareleri bulmak ve oyunu kazanmaktır. Oyuncular, satır ve sütun sayısını girdikten sonra kutuları açarak oyuna başlarlar. Her açılan kutunun etrafındaki mayın sayısı, kutuya yazdırılır. Oyuncular, diğer kutuları doğru tahmin ederek tüm mayınları etkisiz hale getirip oyunu tamamlayabilirler.

## Teknolojiler

- Java 21

## Oyun Kuralları

- Oyun, haritanın boyutunu ayarlamak için satır ve sütun sayılarını (int tipinde) girmenizle başlar.
- Harita boyutu belirlendikten sonra, bombalar (harita boyutunun çeyreği kadar) rastgele haritaya yerleştirilir.
- Oyunculardan her turda bir satır ve bir sütun koordinatı girmeleri istenir.
  - Açılmamış koordinatlar ' - ' ile gösterilir.
  - Eğer girdiğiniz koordinat bir mayına denk gelirse, oyunu kaybedersiniz.
  - Eğer girdiğiniz koordinata değen bir mayın varsa, o koordinata kaç adet mayın denk geliyorsa, o sayı kutuya yazılır.
  - Eğer girdiğiniz koordinatta mayın yoksa, o koordinata 0 yazılır.
  
