# Mask-r-cnn
Maskeleme Yöntemi 

##Adım-1

  Python 3.6.12 versionuna sahip olmanız yada anaconda environment yöntemiyle kullanmanız gerekmektedir
  https://www.anaconda.com
  
##Adım-2

  Github'dan Mask-r-Cnn dosyalarını indirmeniz gerekmektedir. 
  https://github.com/matterport/Mask_RCNN

##Adım-3
  requirements.txt dosyasının içindekiler ;
    numpy,
    scipy,
    cython,
    h5py,
    Pillow,
    scikit-image,
    tensorflow==1.14.0, or (tensorflow==1.15.0 )
    keras==2.0.8, or (keras==2.2.5)
    jupyter 
    
    
    GPU için : tensorflow-gpu:1.15.0, keras:2.2.5, CPU için: tensorflow:1.14.0, keras:2.0.8, h5py:2.10.0
    
  gibi olmalıdır
  
##Adım-4
   Komut istemi içerisinde setup.py dosyası çalıştırılmalı 
    
##Adım-5
   Data setler https://www.makesense.ai/ sitesi gibi sitelerle editlendikten sonra VGG dosyası olarak indirilmelidir.Bu talimatlara göre VGG olarak kullanılırken,       coco olarak işlem yapıyorsanız coco'yu kullanmanız gerekmektedir 
##Adım-6
   Data setin içerisinde train ve val VGG dosyalarını ve resimleri iki farklı dosyaya atılmalıdır .!önemli: 2 dosyadaki resimler farklı olmalıdır.
##Adım-7
  Repository'nin içersindeki kaynak2.py çalıştırılmalıdır. Not: KaynakConfig fonksiyonun içerisinde parameterelere dikkat edilmelidir.
  
##Adım-6
  İşlem bittikten sonra test_kaynak_model2 dosyası jupyter notebook içersinde çalıştırılarak test dosyasının içerisindeki resimler eğitilen yapay zekayla maskelendirilir.
  
  
  Kaynaklar:
  https://www.youtube.com/watch?v=t1MrzuAUdoE&ab_channel=CodeWithAarohi
  https://www.youtube.com/watch?v=9ZNtavU1asE&ab_channel=BuseYarenTekin
  https://github.com/buseyaren/installation-guide-of-maskrcnn
  
  

  
  
