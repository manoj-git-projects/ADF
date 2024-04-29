# Azure Data Factory - Delta load end-to-end
This pipline copies data source to destination
First is alwats full load
Then only the chnaged data , delta load will happen

**ADF- Structure**

![image](https://github.com/manojGetHub/ADF/assets/52737713/ae16b1c2-5ac2-4a80-bd03-c0fe5fa24b2f)

**Master Pipeline**

![image](https://github.com/manojGetHub/ADF/assets/52737713/fa0ec537-2d8d-4f8e-bb1c-03ee9eaf9b07)

**Child Pipeline Delta load**

![image](https://github.com/manojGetHub/ADF/assets/52737713/d5aa100a-3b32-42b7-bd74-dcdceadc9b09)

**Pipelun run activity**
![image](https://github.com/manojGetHub/ADF/assets/52737713/4c341a8a-25d4-4fb2-8669-bb719e66abae)
