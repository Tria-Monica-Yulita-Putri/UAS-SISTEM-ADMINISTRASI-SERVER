# **UAS SISTEM ADMINISTRASI SERVER KELOMPOK 9**

* Install LXC atau containers sesuai kebutuhan. Setting IP sehingga tidak ada yang sama

  ```markdown
  sudo lxc-create -n lxc_php7_1 -t download -- --dist ubuntu --release focal --arch amd64 --force-cache --no-validate --server images.linuxcontainers.org
  ```

  ![1](https://user-images.githubusercontent.com/92940432/151702439-986f37bf-1d50-440d-b62e-7b6ae0ba514a.png)

  

  * Code Igniter

    ```markdown
    deploy-app.yml
    ```

    

    ![2](https://user-images.githubusercontent.com/92940432/151702442-acdca06d-5016-4a82-b56a-aae49cf2280c.png)

    

    ```markdown
    File /app/handlers/main.yml
    ```

    

    ![3](https://user-images.githubusercontent.com/92940432/151702443-f89cbedf-34ec-4c17-8091-9621ceca8af9.png)

    

    ```markdown
    File /app/tasks/main.yml
    ```

    

    ![5](https://user-images.githubusercontent.com/92940432/151702445-390ba0dc-9ff3-44f6-b918-405aa24508e2.png)

    

    ```markdown
    File app/templates/app.conf
    ```

    

    ![6](https://user-images.githubusercontent.com/92940432/151702449-c515b4c5-db1b-46ce-96ac-3e4aec1e676f.png)

    

    ```markdown
    Run ansible deploy-app
    ```

    

    ![7](https://user-images.githubusercontent.com/92940432/151702452-b33f2873-1bc8-4a28-87f3-f3e91b8010fd.png)

    

  * Hasil CI

    ![8](https://user-images.githubusercontent.com/92940432/151702455-d0ecd8ea-f5a5-4a8c-8f0a-7bd3b602662d.png)

    

* Laravel 

  ```
  File nginx.yml
  ```

  

  ![9](https://user-images.githubusercontent.com/92940432/151702457-fd4465c5-416a-4312-9b02-2353068fe718.png)

  

  ```markdown
  File installcomposer
  ```

  

  ![10](https://user-images.githubusercontent.com/92940432/151702458-a72fee23-4742-46f1-8de4-224905aca135.png)

  

  ```markdown
  File config.yml
  ```

  

  ![11](https://user-images.githubusercontent.com/92940432/151702459-d8a321a8-98fd-49b9-aeae-9c85a663b4a3.png)

  

  ```markdown
  File lxc_php7.dev
  ```

  

  ![12](https://user-images.githubusercontent.com/92940432/151702461-d3a31ab2-c3c3-45a9-ab9b-21b0e27f7936.png)

  

  * Hasil Laravel 

    ![13](https://user-images.githubusercontent.com/92940432/151702463-8755099a-7f3e-493a-b382-f44ac0da8ad4.png)

  

* Wordpress

  ```markdown
  File installwordpress
  ```

  

  ![14](https://user-images.githubusercontent.com/92940432/151702464-9c20ad78-8618-4610-b06f-ab07ee0817c4.png)

  

  ```markdown
  File wp.conf
  ```

  

  ![15](https://user-images.githubusercontent.com/92940432/151702465-df6687db-cba8-4da0-8d51-64db448efc94.png)

  

  ```markdown
  File wordpress.conf
  ```

  

  ![16](https://user-images.githubusercontent.com/92940432/151702466-ab78ebc5-8b1a-4d32-8cad-956de485060b.png)

  

  * Hasil Wordpress

    ![17](https://user-images.githubusercontent.com/92940432/151702467-15818414-844a-4806-bc59-45d8227bddaa.png)

    

* Mariadb

  ```markdown
  File /pma/tasks
  ```

  

  ![18](https://user-images.githubusercontent.com/92940432/151702469-19c9ea5d-c986-4cb0-8d14-e2c17bb4dcb6.png)

  

  ```markdown
  File /pma/handlers
  ```

  

  ![19](https://user-images.githubusercontent.com/92940432/151702473-d3203b97-9a7f-492b-9dd0-99c5c6b172a9.png)

  

  ```markdown
  Hasil pma.local
  ```

  

  ![20](https://user-images.githubusercontent.com/92940432/151702474-241c2bc0-3415-4927-9c91-c134121483f1.png)

  

  * Hasil Mariadb

    ![21](https://user-images.githubusercontent.com/92940432/151702476-36096af6-9197-4d1c-a82d-3099d8a58f96.png)

    

  
