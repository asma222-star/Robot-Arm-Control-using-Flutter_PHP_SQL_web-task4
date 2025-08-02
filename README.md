# Robot-Arm-Control-using-Flutter_PHP_SQL_web-task4
Flutter_PHP_SQL_web robot arm control with android 
🦾 Robot Arm Control Panel – Task 1
This project is a Flutter + PHP application for controlling and saving poses of a robotic arm with 4 motors. It provides a mobile app with sliders to set motor angles and buttons to save, run, and reset poses.

📌 Features
✅ Control 4 motors with sliders
✅ Save poses to MySQL database
✅ Run saved poses (updates status)
✅ Reset all motors to default (90°)
✅ View all saved poses with real-time updates

the complete read me file in the project folder ___Readme :)

overview about task steps 
Task 1 – Robot Arm Control Panel

1.	Create Flutter App
o	Install Flutter SDK & Android Studio.
o	Run flutter create run_pose_app.
o	Add dependencies (http, sqflite, path_provider) in pubspec.yaml.
o	Implement UI with sliders and buttons (main.dart).
2.	Set Up Database
o	Start XAMPP (Apache & MySQL).
o	Create database run_pose_db in phpMyAdmin.
o	Create table poses with fields:
id, motor1, motor2, motor3, motor4, status.
3.	Backend PHP Files
o	save_pose.php: Saves new motor positions.
o	get_run_pose.php: Fetches saved poses.
o	update_status.php: Updates pose status.
4.	Connect Flutter to PHP API
o	Use http requests in main.dart.
o	Update base URL: http://10.0.2.2/run_pose/.
o	Test API using curl before integrating.
5.	Test Features
o	Run Flutter app on Emulator.
o	Add poses → Verify in database.
o	Run pose → Status changes.
o	Reset → Motors return to default (90°).
6.	Deployment
o	Place PHP files in xampp/htdocs/run_pose.
o	Keep Apache & MySQL running while testing
