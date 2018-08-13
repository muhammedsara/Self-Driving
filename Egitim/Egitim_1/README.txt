

- Sanal makina icin VMware tavsiye ederim, kendi sitesinden indirebilirsiniz. Ubuntu için 16.04 versiyonunu indirip yükleyin.

- Ubuntu kulumunu bitirdikten sonra;

 * Ubuntu için "Anaconda" nın araştırılıp kurulması gerekmektedir. ( Python 2.7 sürümü)
 * Anaconda env oluşturulması
    - conda create -n tensorflow2.7 python=2.7    -->"Env oluşturmak için bu komutu  kullacanağız."
   
 * Kurulacak Kütüphaneler
    - source activate tensorflow2.7    -->"Env oluşturduktan sonra bu komutla env yi aktifleştirmemiz gerekiyor. Biz her zaman bu env ile çalıştıracağımız için bu adım sürekli kullanılacak."
    - conda install -c anaconda jupyter 
    - conda install -c menpo opencv3 
    - conda install -c conda-forge matplotlib
    
 * Kurulum işlemleri tamamlandıktan sonra env'ı aktifleştirip "jupyter notebook" yazıp jupyteri açıyoruz.

 * Buraya kadar işlemleri tamamladıysak size verdiğimiz ZED kamera ile çekilmiş resmi (376x1344 boyutunda)

    sağ sol olarak ayırmanız
    sol resmi gri tona çevirmeniz
    gri resmin sol üst köşesine adınızı yazmanız
    resmin en son halini kaydetmeniz istenmektedir

    img_path = '/00001.jpg' resmi bu şekilde direk yolunu vererek açın. (open file dialog kullanmayın)
    img_save_path = '/00001_gray.jpg' bu şekide direk kayıt edin. (open file dialog kullanmayın)


- Bu işlemlerden sonra çalışma klasörünün adını öğrenci numaranız yaparak zip haline getirin.
  Zipi fourplusone.kou@gmail.com adresine mail atın.

- Python-Lectures-master adlı klasördeki .ipynb uzantılı jupyter dosyaları bulunmaktadır. Bu komutları tek tek çalıştırıp ne iş yaptıklarını öğrenin.

- Bu işlemleri erken tamamlayan arkadaşlar, ROS ve TensorFlow konularında araştırma yapsınlar. Ros u ubuntuya kurmaya çalışırsanız bir sonraki haftaya hazırlık yapmış olursunuz.
