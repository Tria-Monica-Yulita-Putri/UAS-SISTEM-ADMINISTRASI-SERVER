# **UAS SISTEM ADMINISTRASI SERVER KELOMPOK 9**

* Install LXC atau containers sesuai kebutuhan. Setting IP sehingga tidak ada yang sama

  ```markdown
  sudo lxc-create -n lxc_php7_1 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --no-validate --server images.linuxcontainers.org
  ```

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\1.png)

  

  * Code Igniter

    ```markdown
    deploy-app.yml
    ```

    

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\2.png)

    

    ```markdown
    File /app/handlers/main.yml
    ```

    

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\3.png)

    

    ```markdown
    File /app/tasks/main.yml
    ```

    

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\5.png)

    

    ```markdown
    File app/templates/app.conf
    ```

    

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\6.png)

    

    ```markdown
    Run ansible deploy-app
    ```

    

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\7.png)

    

  * Hasil CI

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\8.png)

    

* Laravel 

  ```
  File nginx.yml
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\9.png)

  

  ```markdown
  File installcomposer
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\10.png)

  

  ```markdown
  File config.yml
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\11.png)

  

  ```markdown
  File lxc_php7.dev
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\12.png)

  

  * Hasil Laravel 

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\13.png)

  

* Wordpress

  ```markdown
  File installwordpress
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\14.png)

  

  ```markdown
  File wp.conf
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\15.png)

  

  ```markdown
  File wordpress.conf
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\16.png)

  

  * Hasil Wordpress

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\17.png)

    

* Mariadb

  ```markdown
  File /pma/tasks
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\18.png)

  

  ```markdown
  File /pma/handlers
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\19.png)

  

  ```markdown
  Hasil pma.local
  ```

  

  ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\20.png)

  

  * Hasil Mariadb

    ![](C:\Users\TRIA YULITA\OneDrive\Dokumen\ITTS\SEMESTER 5\Sistem Administrasi Server\UAS SAS FOTO\21.png)

    

  
