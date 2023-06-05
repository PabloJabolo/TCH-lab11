# Laboratorium_11

Paweł Jabłoniec

Sprawozdanie - laboratorium 11

---

### 1. Uruchomienie aplikacji

#### 1. Uruchomienie docker-compose

`docker compose up -d --build`

![Budowanie aplikacji](img/budowanie.jpg)

---

#### 2. Odblokowanie portu 6666 w przeglądarce

![Odblokowanie portu](img/chrome.jpg)

---

#### 3. Uruchomienie usług w przeglądarce na portach 6666 oraz 6001:

`http://localhost:6666/`

![Uruchomienie usługi](img/nginx_6666.jpg)

![Uruchomienie usługi](img/nginx_polaczenie.jpg)

---

`http://localhost:6001/`

![Baza phpmyadmin](img/phpmyadmin_logowanie.jpg)

![Baza phpmyadmin](img/baza.jpg)

---

#### 4. Zatrzymanie oraz usunięcie kontenerów:

`docker compose down`

