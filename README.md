# Flipkart___GRID

   ## EXPIRY DATE DETECTION 

Introduction : Expiry date detection can be very helpful in many real-world scenarios. Either to aid the visually impaired or to just make it easier to read expiry dates which could be printed in various formats and fonts, implementing an automated date detector could be beneficial. This work utilized concepts of opencv and tesseract in order to detect the expiry date printed on it and find the days remaining.
This study proposes a generalized framework for detecting and understanding product expiration dates. The proposed framework consists of three networks: Object Detection Network, which detects labels from a live webcam feed; (Optical Character Recognition (OCR) Network, which extracts the text corresponding to the expiry date from the detected labels; and Date Processing Network, which computes the remaining days until the expiry date and displays the results in real-time.

![Screenshot 2024-12-11 202649](https://github.com/user-attachments/assets/74cf2d3c-fc0b-45c2-8c61-7c5b2622da6c)



Fig The overall architecture of the proposed framework for expiration date detection and understanding.

The proposed framework can handle challenging expiration date cases and distinguish 13 different date formats. It can detect and understand the expiration dates even when the input image contains multiple dates.Moreover, the proposed framework can detect date, days remaining from the current date.

![Screenshot 2024-12-11 191947](https://github.com/user-attachments/assets/ebed1d0e-d085-4ed8-9c3c-d2c8b2d854ea)


   ## ITEM COUNTING WITH YOLO & LIVE WEBCAMERA FEED

This project is a real-time item counting system designed to identify and count items using live webcam feeds. By leveraging cutting-edge technologies such as YOLOv8s, Pandas, and Ultralytics, the system ensures accurate and efficient object detection and counting.

Features
- Real-Time Object Detection: Detects items live using YOLOv8s.
- Item Counting with Maximum Tracking: Tracks and counts multiple items simultaneously while identifying the maximum count in a session.
- Seamless Data Processing: Utilizes Pandas for efficient data handling and maintaining logs of item counts.
- Live Visualization: Displays item counts directly on the webcam feed with visual overlays.
- Data Persistence: Saves item counts and maximum counts to CSV files for further analysis

*Example Output*
Live Feed with Annotations


CSV Output
item_counts.csv:
-----------------------------
| Frame Number | Item Count |
| 1            |   49       |
-----------------------------

Installation
- Clone the repository
- Install dependencies
    - pip install -r requirements.txt
- Ensure a webcam is connected to your system.

