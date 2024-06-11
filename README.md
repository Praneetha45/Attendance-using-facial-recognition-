# Attendance Using Facial Recognition

This project is implemented in Python and aims to create an Excel sheet of all the students present in the class. The attendance is marked using the system's webcam, which compares the detected face from the webcam with the pictures of students present in the photos database.

## How is this project useful?

This project helps in calculating student attendance. The attendance is marked in an Excel file using the OpenCV library. The CSV file is created with the title as the present date when the attendance is calculated. Another program is used to send an email to the recipient with the created CSV file attached to it.

## Requirements

Before executing this program, you need to install the following libraries in your system using pip:

- face_recognition
- opencv-python (cv2)
- yagmail

You can install these libraries using the following commands:

```bash
pip install face_recognition
pip install opencv-python
pip install yagmail
```
## Working 
This project contains two parts:

Part 1: Marking the Attendance
When you run the program, the webcam detects the student's face and compares it to the photos of the students present in the database. If the face is matched, the student's name is displayed, and the name is entered into the Excel sheet. The Excel sheet is created with the CSV file name as the date when the attendance is taken.

Part 2: Sending the Attendance Sheet via Email
The second part of the program is to send the created attendance sheet to the given recipient's email. To send the email, we use the yagmail library. Both parts of the project should be run separately.

## Usage
Clone this repository to your local machine.
Install the required libraries using pip.
