# zspotify
## Create Virtual Python Environment
Damit du keine unnötigen installationen auf deinem Betriebssystem allgemeinen Betriebssystem ausführen musst, würde ich empfehlen die Packete nur in ein sogenannten 'virtual environment' installieren.
1. Terminal öffnen und ins 'home' Verzeichnis gehen:
  ```
  cd ~
  ```
2. Git Repository clonen:
  ```
  git clone https://github.com/jsavargas/zspotify.git
  ```

3. Virtual environment erstellen:
  ```
  cd zspotify
  python3 -m zspotify-env
  ```
4. Virtual environment aktivieren:
  ```
  source ~/zspotify/zspotify-env/bin/activate
  ```
5. Dependencies mit pip installieren:
  ```
  pip install ffmpeg*
  pip install -r requirements.txt
  ```
6. You'r good to go :smile::
  ```
  python3 zspotify.py
  ```
