# Cofflyze - Final Capstone Project 2024
Cofflyze is an Android-based application that aims to help coffee farmers diagnose diseases in coffee plants through leaf analysis. This application is designed to overcome the problem of early detection of coffee leaf diseases, which are often difficult for farmers to recognize visually and have a significant impact on crop yields. Based on research questions related to the effectiveness of leaf scanning in identifying coffee plant diseases, Cofflyze uses image processing and machine learning technology to identify four leaf conditions: miner,phoma , rust, and no disease.

## Featured 
Here is an explanation of the features of the Cofflyze application:
1. **Login and Register**  
   The **Login and Register** feature allows users to securely create an account and log into the Cofflyze application. Users can register with their email and password, or use Firebase Authentication to streamline the login process. After registering, users can log in to access their personalized dashboard and features. The login system ensures that only authorized users can access their data and other functionalities of the app.
2. **Articles**  
   The **Articles** feature provides users with access to informative content related to coffee plant diseases, prevention methods, and agricultural tips. Articles are regularly updated, ensuring users have access to the latest research and expert advice. This feature helps users stay informed and improve their knowledge of coffee plant care.
3. **Coffee Leaf Disease Detection**  
   The **Coffee Leaf Disease Detection** feature allows users to take a picture of their coffee plant leaves and upload it to the application for analysis. Using machine learning models deployed in the backend, Cofflyze processes the image and detects potential diseases affecting the coffee plant. The system provides users with results, including the disease type, symptoms, and recommendations for treatment.
4. **History**  
   The **History** feature allows users to view their past disease detection results. It stores all previously uploaded images and the corresponding diagnosis, helping users track the health of their coffee plants over time. This feature is useful for monitoring progress and ensuring proper care for the plants.
5. **User Profile**  
   The **User Profile** feature allows users to manage their personal information and settings. Users can update their profile details, such as name, email, and password, and view their detection history and other relevant data. This feature provides a personalized experience, allowing users to tailor their interaction with the app according to their preferences.
6. **Logout**  
   The **Logout** feature provides users with a secure way to log out of their account when they are finished using the app. This ensures that no one else can access the user's information or leave them logged into the app without their consent, enhancing the overall security and privacy of the application.
These features collectively ensure that Cofflyze provides a user-friendly, secure, and informative platform for coffee plant disease detection and management.

## Our Team

|          Nama         | Bangkit-ID |       Path       |
|:---------------------:|:----------:|:----------------:|
|  Ryan Erlangga Ardiansyah  |  M260B4KY3980  | Machine Learning |
|  Sutan Arsyah Nugraha  |  M129B4KY4236  | Machine Learning |
|   Alieffiea Widya Prawita    |  M748B4KX0376  |   Machine Learning |
|  Dwi Maharani Purwati  |  C748B4KX1194  |  Cloud Computing |
|    Rahmanda Putri Radisa     |  C748B4KX3625  |      Cloud Computing     |
|    Muhammad Irsyad      |  A120b4KY2916  |      Mobile Development    |
|    Yosea Mervandy Sugiarto      |  A120B4KY4544  |      Mobile Development    |

## Machine Learning  
* Dataset
* (https://drive.google.com/file/d/1SaKFvIytPwKPgJ8a0J77InPFcla2kXvC/view)
  
## Mobile Development
* Tools
* Android Studio Lady Bug | 2024.2.1 

## Cloud Computing
* Cloud Architecture
1. Cofflyze API <br>
* [Google Cloud Platform](https://medium.com/@dwmhranii08/c242-ps231-cofflyze-api-documentation-5d01ec7059dd)
2. Cofflyze Architecture <br>>
* https://github.com/Cofflyze-Capstone-Project/C242-PS231-Cloud-Computing/blob/main/arsitektur.png 

* Featured Technologies
* [Google Cloud Platform](https://cloud.google.com/) GCP provides the scalable infrastructure needed for the Cofflyze project, enabling us to seamlessly grow from prototype to production without worrying about capacity, reliability, or performance. With GCP, we can easily capture, manage, process, and visualize data through its powerful data analytics products and services, ensuring high availability and cost optimization.
* [Hapi](https://hapi.dev/) Hapi.js is a robust and flexible framework for building applications and services. It is used to handle HTTP requests, route management, and request validation with ease. Hapi.js also supports plugin-based architecture, allowing easy extension of the application. This framework simplifies building secure and scalable RESTful APIs, which is key to Cofflyze's real-time capabilities.
* [Flask](https://flask.palletsprojects.com/) Flask is a lightweight and flexible micro web framework for Python that enables easy development of RESTful APIs. It is used in Cofflyze for deploying machine learning models and integrating them with the backend. Flask’s minimalistic design and simplicity make it ideal for fast prototyping and serving machine learning models with minimal overhead.
