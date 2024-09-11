The 3x3 Game is a mobile application written in Flutter, bootstrapped with Spring Boot for the backend, and integrated with PostgreSQL for the database. In this application, users will have options to create an account, log in, and play some somewhat trivial games. Also, upon login, it fetches and displays real-time weather data regarding the current location of a user using the WeatherAPI. This is a 3x3 button grid game wherein a user would try to guess the "correct" button, preselected randomly, using three attempts.

1. Run Docker

```docker run --name my-postgres -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d postgres:15```
2. Run backend
 - go to ```src/main/java/org/puxuan/checkinapp/CheckinAppApplication.java```
 - <img width="1386" alt="Screenshot 2024-09-10 at 11 45 35 PM" src="https://github.com/user-attachments/assets/49d851b9-2eef-4d41-9f55-ca73c7826e4f">
3. Run Frontend
 - go to ```frontend1/my_game/lib/main.dart```
 - ```flutter run```

https://github.com/user-attachments/assets/1cb46c2e-cdcf-4bc8-b0a3-84ff0709e96b

