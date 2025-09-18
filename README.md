# Traffic Flow Predictor Project

A complete end-to-end **traffic congestion prediction system** built for Mumbai (Matunga ↔ Wadala corridor).  
The project covers **37 streets** and achieves an accuracy of **97%** for congestion level prediction around Vidyalankar Institute of Technology, Wadala.  

<!-- ![Street Map](https://github.com/gaga1313/Traffic-Flow-Prediction/blob/main/street%20map.jpeg?raw=true) -->
<p align="center">
    <img alt="map" src="https://github.com/user-attachments/assets/18a36f32-db20-43f2-9f77-4c35c79ab7ec" width="85%" />

</p>

---

## Application Screenshots

<p align="center">
  <img src="https://user-images.githubusercontent.com/91366535/173252290-e1861184-39aa-4fbe-99ae-48af2e297c6c.jpg" width="30%" />
  <img src="https://user-images.githubusercontent.com/91366535/173252278-a82a9532-0e6d-4d4d-a224-889a02067d74.jpg" width="30%" />
  <img src="https://user-images.githubusercontent.com/91366535/173252299-6c89035b-c705-4fbf-90ab-6388b71d2103.jpg" width="30%" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/91366535/173252304-8623256d-3264-4372-82b0-c0e498c95ce8.jpg" width="30%" />
  <img src="https://user-images.githubusercontent.com/91366535/173252309-306e9dda-d3de-4333-9aa8-cddc42aa3982.jpg" width="30%" />
  <img src="https://user-images.githubusercontent.com/91366535/173252315-be3def76-9119-4253-bfdd-3adde8e94a56.jpg" width="30%" />
<!--   <img src="https://user-images.githubusercontent.com/91366535/173252328-ccf5f86b-a99f-4b63-9044-16de048a808d.jpg" width="30%" /> -->
</p>

<!--
<p align="center">
  <img src="https://user-images.githubusercontent.com/91366535/173252315-be3def76-9119-4253-bfdd-3adde8e94a56.jpg" width="30%" />
</p>
-->

---

## Features

- Predicts congestion levels for **37 mapped streets** in real-time  
- Trained ML model with **97% accuracy**  
- Data collected via the **Google Maps Traffic API**  
- Flask-based REST API, deployed on **Heroku**  
- Flutter mobile application as the user interface  
- Includes time and date selectors for flexible predictions  
- Clean UI with pre-loader, search, and flip card result views  

---

## Technology Stack

- **Machine Learning Model**: Python, scikit-learn (trained on Google Maps API data)  
- **Backend API**: Flask, deployed on Heroku  
- **Frontend App**: Flutter (Dart)  
- **Data Source**: Google Maps Traffic API  

---

## Project Components

The complete Traffic Flow Predictor consists of:

1. **ML Model** (prediction engine)  
   [Traffic-Flow-Prediction](https://github.com/gaga1313/Traffic-Flow-Prediction.git)

2. **Backend API** (Flask REST API on Heroku)  
   [Traffic-Flow-Predictor-API](https://github.com/VedantBandre/Traffic-Flow-Predictor-API.git)  
   Hosted at: https://traffic-flow-predictor.herokuapp.com/

3. **Mobile Application** (Flutter front-end)  
   [Traffic-Flow-Predictor-App](https://github.com/VedantBandre/Traffic-Flow-Predictor-App.git)

---

## Streets Covered

The model covers the following **37 streets/intersections** between Matunga and Wadala:

1. Adenwala Rd  
2. Adenwala Rd and Nathalal Parekh Marg  
3. Antop Hill Rd and Shaikh Misree Marg  
4. Balaram Babu Khedekar Marg  
5. Bharni Naka Rd / Sir Pochkhan Wala Rd / Vidyalankar College Rd  
6. Comrade Harbanslal Marg / Flank Rd  
7. Comrade Harbanslal Marg / Flank Rd and Dr Baba Saheb Ambedkar Rd  
8. Dadar TT Flyover / Eastern Express Hwy  
9. David S Barretto Rd  
10. David S Barretto Rd and Barkat Ali Dargah Rd  
11. Dr Baba Saheb Ambedkar Rd  
12. Eastern Express Hwy and Dr Baba Saheb Ambedkar Rd  
13. GD Ambekar Marg / Katrak Rd  
14. GD Ambekar Marg / Katrak Rd and Firdausi Rd  
15. Govindji Keni Rd  
16. Govindji Keni Rd and GD Ambekar Marg / Katrak Rd  
17. Govindji Keni Rd, Mahatma Jyotiba Phule Rd / Naigaon Rd and BJ Devrukhkar Rd  
18. H R Mahajani Rd  
19. Jerbai Wadia Rd  
20. Kings Cir / Matunga Cir and Puranmal Singhani Rd  
21. Lady Jamshedji Rd / NC Kelkar Rd  
22. Lady Jehangir Rd  
23. Mahatma Jyotiba Phule Rd / Naigaon Rd and MMGS Marg / Naigaon Cross Rd  
24. Mancherji Joshi Rd  
25. NC Kelkar Rd and Lady Jamshedji Rd  
26. Nathalal Parekh Marg and Rafi Ahmed Kidwai Rd  
27. Puranmal Singhani Rd and Nathalal Parekh Marg  
28. Rafi Ahmed Kidwai Rd  
29. Rd Number 16 and Barkat Ali Dargah Rd  
30. SM Uphill Rd  
31. Shaikh Misree Marg  
32. Shaikh Misree Marg and JK Bhasin Marg  
33. Shaikh Misree Marg and SM Uphill Rd  
34. Taikalwadi Marg and JK Sawant Marg  
35. Tilak Rd  
36. Tilak Rd and Firdausi Rd  
37. Tilak Rd / Tilak Bridge / Tilak Flyover  

---

## Deployment

- **Backend API** is live on Heroku:  
  https://traffic-flow-predictor.herokuapp.com/

- **Mobile Application** can be built and run from the Flutter app repository:  
  https://github.com/VedantBandre/Traffic-Flow-Predictor-App.git  

---

## Data Source

- **Google Maps Traffic API**  
  Documentation: https://mapsplatform.google.com/

---

## License

[MIT License](https://choosealicense.com/licenses/mit/)  
