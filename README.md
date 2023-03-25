# LoRa_Network
A continuación, se mostrarán las distintas pruebas relizadas para determinar la corriente consumida por el Gateway y el nodo en un intervalo de tiempo.
## **Variación de parámetros de la modulación LoRa**
###  **Gateway** 
#### **_Gráficas de corriente y potencia_**
- **SF = 7, BW = 125E3, CR = 5**
![s7b125c5](https://user-images.githubusercontent.com/127070980/224197447-553fe6bd-6995-48c8-85f3-b04272ceeca9.jpg)
- **SF = 8, BW = 125E3, CR = 5**
![s8b125c5](https://user-images.githubusercontent.com/127070980/224197449-6de4e043-6b0f-4f9a-b7f4-dda460efceb6.jpg)
- **SF = 9, BW = 125E3, CR = 5**
![s9b125c5](https://user-images.githubusercontent.com/127070980/224197450-aac08e58-75e1-4072-a768-256f3f312b61.jpg)
- **SF = 9, BW = 500E3, CR = 5**
![s9b500c5](https://user-images.githubusercontent.com/127070980/224197454-17cc81df-c74b-4c73-8568-d6ed0cafbed4.jpg)
- **SF = 9, BW = 500E3, CR = 8**
![s9b500c8](https://user-images.githubusercontent.com/127070980/224197460-cad88f19-66ce-4029-99b3-3f7402c4443f.jpg)
- **SF = 10, BW = 125E3, CR = 5**
![s10b125c5](https://user-images.githubusercontent.com/127070980/224197462-04977bef-c6df-4826-9f52-8c6d065fbb94.jpg)
- **SF = 10, BW = 500E3, CR = 5**
![s10b500c5](https://user-images.githubusercontent.com/127070980/224197463-5192fcd4-7e61-4002-a49e-97b8af71d356.jpg)
- **SF = 10, BW = 500E3, CR = 8**
![s10b500c8](https://user-images.githubusercontent.com/127070980/224197466-9712b6af-9a45-4265-ad32-5a90f593a035.jpg)
- **SF = 11, BW = 500E3, CR = 5**
![s11b500c5](https://user-images.githubusercontent.com/127070980/224197468-b177e20f-aee0-44fa-8253-eef2a379887b.jpg)
- **SF = 11, BW = 500E3, CR = 8**
![s11b500c8](https://user-images.githubusercontent.com/127070980/224197469-28d6599a-5601-4560-af6c-655d64192635.jpg)
- **SF = 12, BW = 500E3, CR = 5**
![s12b500c5](https://user-images.githubusercontent.com/127070980/224197475-a4d3f008-c50f-4104-bd7c-eb94ab443e29.jpg)

#### **_Gateway server_**
> En este apartado se presenta el comparmiento del esp32 al conectarse a un servidor y dirigir la red LoRa

* ![server0](https://user-images.githubusercontent.com/127070980/224197476-897aff05-72fa-4ea7-a271-7e5050a75976.jpg)

+ ![server2](https://user-images.githubusercontent.com/127070980/224197478-542c76da-ef1d-47e9-a452-224f2360274c.jpg)

###  **Nodo** 
#### **_Gráficas de corriente y potencia_**

- **SF = 7, BW = 125E3, CR = 5**
![s7c5b125](https://user-images.githubusercontent.com/127070980/224208196-2b91f99c-b448-4228-bd7c-1c6a6b3c3afb.jpg)

- **SF = 7, BW = 250E3, CR = 5**
![s7c5b250](https://user-images.githubusercontent.com/127070980/224208199-d7d0ec3a-97be-424e-aec6-d4ce4f817978.jpg)

- **SF = 7, BW = 500E3, CR = 5**
![s7c5b500](https://user-images.githubusercontent.com/127070980/224208200-6b433062-6138-4228-ac2d-22eed220fbe8.jpg)

- **SF = 7, BW = 125E3, CR = 8**
![s7c8b125](https://user-images.githubusercontent.com/127070980/224208203-c8d9614c-7a62-4632-8e7d-917594463877.jpg)

- **SF = 7, BW = 250E3, CR = 8**
![s7c8b250](https://user-images.githubusercontent.com/127070980/224208204-4c687045-129c-4253-86f1-ea15be2e3897.jpg)

- **SF = 7, BW = 500E3, CR = 8**
![s7c8b500](https://user-images.githubusercontent.com/127070980/224208207-62faffea-e1ae-4e53-8791-6df09bdbe7a6.jpg)

- **SF = 9, BW = 125E3, CR = 5**
![s9c5b125](https://user-images.githubusercontent.com/127070980/224208210-766c0203-b2ee-477b-8c5d-ce4ff5a6c827.jpg)

- **SF = 9, BW = 250E3, CR = 5**
![s9c5b250](https://user-images.githubusercontent.com/127070980/224208212-40bed8a1-d8f1-4f2c-aabb-cf1de88c5903.jpg)

- **SF = 9, BW = 125E3, CR = 8**
![s9c8b125](https://user-images.githubusercontent.com/127070980/224208215-f15b7ebb-df6c-42fd-b7e9-3e5a4199374b.jpg)

- **SF = 9, BW = 500E3, CR = 8**
![s9c8b500](https://user-images.githubusercontent.com/127070980/224208219-61d97d2c-e143-447b-9cbf-e9a7b1e9414e.jpg)

- **SF = 11, BW = 250E3, CR = 5**
![s11c5b250](https://user-images.githubusercontent.com/127070980/224208220-94fb9030-5b77-4704-89ce-90ad206166d2.jpg)

- **SF = 11, BW = 500E3, CR = 5**
![s11c5b500](https://user-images.githubusercontent.com/127070980/224208221-a76098be-1ee3-4313-b63c-28f2754f3de8.jpg)

- **SF = 11, BW = 250E3, CR = 8**
![s11c8b250](https://user-images.githubusercontent.com/127070980/224208222-1299b773-d5fb-4196-bad0-f53d9703852e.jpg)

- **SF = 11, BW = 500E3, CR = 8**
![s11c8b500](https://user-images.githubusercontent.com/127070980/224208224-c3d5db87-26e7-4839-a643-2fc723121730.jpg)

- **SF = 12, BW = 500E3, CR = 5**
![s12c5b500](https://user-images.githubusercontent.com/127070980/224208227-08d03544-8775-4ece-8953-4565f8c7c5c2.jpg)
