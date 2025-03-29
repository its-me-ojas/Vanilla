## 📌 First-Time Setup
```
git clone https://github.com/its-me-ojas/Vanilla
cd Vanilla
```
- Install **Playit.gg** (if playing with others).
- It will give a executable file named playitgg.exe or something else
# ⚠ **Rule:** Always **pull before playing** and **push after stopping!** 🚀

## **🎮 Playing Locally (Solo Server)**
- **Pull latest changes**
```
git pull origin main
```
- **Start the server** ( it will open a console panel )
```
./start.exe # for windows, just click the start.exe file
```

```
./start.sh # for linux or mac, just run the start.sh in terminal
```
- **Stop the server when done**
`stop` # in game command (console)

- **Save progress**
```
git add .
git commit -m "Meaningful Message (could be anything you did in the server)"
git push origin main
```

## **🌍 Playing with Friends (Using Playit.gg)**
- **Pull latest changes**
```
git pull origin main
```
- **Start the server** ( it will open a console panel )
```
./start.exe # for windows, just click the start.exe file
```

```
./start.sh # for linux or mac, just run the start.sh in terminal
```
- **Start Playit.gg Tunnel**
- Log in and start a tunnel. ( run the executable file )
- Share the **server address** with players.
- **Stop the server when done**
```
stop # in console
```
- **Save progress**
```
git add .
git commit -m "Meaningful Message (could be anything you did in the server)"
git push origin main
```
