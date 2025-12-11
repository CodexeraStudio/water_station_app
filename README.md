# water_station_app
This project is a dedicated mobile application designed for field technicians and staff of a water services company (e.g., ETA-Sammour) to manage and execute daily operational tasks, such as water meter readings, station maintenance, and ticket completion.

🎯 Key Features and Functionality:
1.Task Management & Workflow:
Task Listing (الرئيسية): Displays current tasks, showing details like battery life, Wi-Fi status, time, and task ID (e.g., #185, #279).
Task Details (Show details the task): A popup shows detailed station information, including contact numbers, problem description, required materials (e.g., Sodium Hypochlorite, Caustic Soda), and filter type (e.g., 20"- 5µm).
Task Completion: Users can confirm the completion of a task, resulting in a "Success!!!" notification ("تم انهاء التذكرة بنجاح").

2.Water Meter Reading Module (Enter counter in places):
Location and Subscriber Selection: Allows field agents to select the building (e.g., عمارة نيرو) and the specific subscriber.
Data Input: Dedicated interface to manually input the water meter reading ("ادخل قراءة العداد").

3.Subscriber and Location Management:
Location Filtering: Allows browsing places to select the subscriber for meter reading (e.g., مكتب أوركا ميديا, عيادة الدكتور شادي رمضان).
Task Type Specificity: Different task details popups (e.g., Show details vs. Show details the task) handle various operations, such as maintenance and filling/delivery.

4.Utility & Notifications:
Notifications: A dedicated "الإشعارات" screen shows incoming messages or task updates.
Settings: The side menu allows the user to enable/disable the use of mobile data ("استخدام بيانات الهاتف").

🛠️ Technologies Used (Example – Please customize these with your actual technologies):
Category,Technology (Example),Notes
Programming Language,Dart / Kotlin / Swift,Core language used for application logic.
Framework,Flutter / Android Native / React Native,Platform used for building the user interface.
Location Services,GPS/Location Tracking,Essential for field service and navigation.
Backend/Database,Custom API / Firebase Firestore,"Used for managing task assignments, inventory (materials/filters), and meter readings."


<img width="1504" height="2848" alt="Gemini_Generated_Image_tumg01tumg01tumg" src="https://github.com/user-attachments/assets/e4ed2fa9-5a7e-43ac-92f7-57444e56528f" />
