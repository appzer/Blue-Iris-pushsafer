![Pushsafer](https://www.pushsafer.com/de/assets/logos/logo.png)
# Blue-Iris-pushsafer
## How to send push-notifications out of Blue Iris by pushsafer.com

Webcam and video security software. Record, playback and watch your surveillance cameras live at home or on the go with our mobile apps.

[Pushsafer.com](https://www.pushsafer.com) make it easy and safe to send &amp; receive push-notifications to your
- Android devices
- iOS devices (iPhone, iPad, iPod Touch, Watch)
- Windows 10 Phone & Desktop
- Browser (Chrome & Firefox)

## Usage
1. Open Camera settings
2. go to the alerts tab ![Pushsafer](https://www.pushsafer.com/en/assets/examples/blueiris.jpg)
3. enable "Request from a webservice" and click on "Configure"
4. choose https://
5. enter the Pushsafer API URL with parameters you need (without https or http)
6. you can use the Link/URL generator in your dashboard
7. choose parameters you want and click on Create Link
8. Copy the generated URL in Blue Iris (without https or http)

## Example URLs

	www.pushsafer.com/api?k=XXXXXXXXXXXXXXXXXXXX&d=418&i=82&s=25&v=3&t=iSpy%20Alert&m=Movement%20detected%20in%20living%20room
  
	www.pushsafer.com/api?k=XXXXXXXXXXXXXXXXXXXX&d=418&i=82&s=25&v=3&t=iSpy%20Alert&m=Movement%20detected%20in%20living%20room%0A{ID}%3A%20{NAME}

## Screenshots of Blue Iris Push-Notifications

Screenshot Client App

![Pushsafer](https://www.pushsafer.com/de/assets/examples/blueiris-2.jpg)

Screenshot iOS > iPhone

![Pushsafer](https://www.pushsafer.com/de/assets/examples/blueiris-3.jpg)

Screenshot Android

![Pushsafer](https://www.pushsafer.com/de/assets/examples/blueiris-4.jpg)

Screenshot Windows 10 Phone

![Pushsafer](https://www.pushsafer.com/de/assets/examples/blueiris-5.jpg)

