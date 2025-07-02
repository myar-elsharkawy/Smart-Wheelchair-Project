# Smart Wheelchair 👨‍🦼

The smart wheelchair designed for people with special needs features advanced capabilities such as measuring heart rate and temperature. It sends all data directly to a dedicated app, allowing the user to easily monitor their health status. The app also sends instant notifications to the user in case of any changes in their health condition. The wheelchair is equipped with smart sensors and safety features to avoid obstacles and can also detect harmful gases in the surrounding environment to alert the user of potential danger. Additionally, it includes an umbrella to protect the user from sunlight and rain, making it suitable for both indoor and outdoor mobility in various weather conditions.

![Smart Wheelchair](Smart%20Wheelchair/SmartWheelchairPhoto.png)

🎥 [Watch Smart Wheelchair Demo](Videos/Smart%20Wheelchair%201.mp4)



## 🔧 Features

- Movement control using mobile app (via Bluetooth)
- Obstacle avoidance using ultrasonic sensors
- Health monitoring 
- Environmental sensing 
- Automatic umbrella opening using servo motor


## 🧠 How It Works

The system is based on an **Arduino Mega 2560**, which connects to multiple sensors and modules:
- **Ultrasonic Sensors** for detecting obstacles
- **Pulse Sensor** to monitor heart rate
- **DHT11** for temperature and humidity
- **MQ135** for gas detection
- **Servo Motor** for umbrella control
- **HC-05 Bluetooth Module** for app communication
- **DC Motors and Motor Driver** for movement

## 📱 Mobile App (by MIT App Inventor)

The app connects via Bluetooth and allows the user to:
- Control wheelchair movement
- Monitor health data
- Open and close the umbrella
- Sending location and health status to caregivers
  
  **Initial Version**
  
![Smart Wheelchair UI](Application/UI/Initial%20Version.png)
