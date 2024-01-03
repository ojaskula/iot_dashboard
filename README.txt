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
/home/admin-root/Pictures/Screenshot from 2024-01-03 03-39-45.png

