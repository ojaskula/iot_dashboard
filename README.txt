# IoT dashboard
A NodeRed project that receives MQTT messages (temperature and humidity), analyzes them and displays the statistics on the web dashboard.
App consists of tow docker services - NodeRed and postgreSQL, conncted into one network.

Requirements:
- docker
- docker compose

In case of ERROR permission denied use:
"sudo chmod -R 777 ." command. 

"http://127.0.0.1:1880/" for Node Red flow 
"http://127.0.0.1:1880/ui/" for node red UI 

# Screenshots
![Screenshot from 2024-01-03 03-39-45](https://github.com/ojaskula/iot_dashboard/assets/106124763/54c50dda-1a9a-47e8-859a-c6f7dc2f339a)

![Screenshot from 2024-01-03 03-46-26](https://github.com/ojaskula/iot_dashboard/assets/106124763/e9f0271f-5b6e-47b0-8ef6-e295fff0f545)
