# Goods-Expiry-Date-Tracker
Goods_Expiry_Date_Tracker
Features:

    Scan QR Code
    Get Scanned data, save it in database and display it in a recyclerView
    when item's date expires, show notification

Tools :

    Kotlin
    MVVM
    Room db
    viewModel , LiveData
    Coroutines
    Navigation component
    Hilt
    ViewBinding
    RecyclerView

Note:
Here I'm using Qr Code_generator to generate fake objects that will be scanned later .. each object must have id, item_name, item_type, item_date in a json format then item is scanned by Zxing library
Screens:
![image](https://user-images.githubusercontent.com/28671182/150836201-2cc28b5c-c4a0-48e0-a10e-e756caeb49db.png)
![image](https://user-images.githubusercontent.com/28671182/150836261-0d123e51-fc5f-4dc2-a32a-2ae7074c0d55.png)
