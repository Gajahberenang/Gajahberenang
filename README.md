<div align="center">

![header](https://capsule-render.vercel.app/api?type=rect&color=0:0b0b0f,60:3a0000,100:e10600&height=200&section=header&text=KRYZONIX&fontSize=72&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=python3%20kryzonix.py&descSize=20&descAlignY=68&descColor=ffffff)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2500&pause=900&color=E10600&center=true&vCenter=true&random=false&width=720&lines=%3E%3E%3E+import+kryzonix;%3E%3E%3E+kryzonix.ade.motto;'Simply+Lovely';%3E%3E%3E+kryzonix.ade.diagnose%28pc%29;'stable')](https://kryzonix.netlify.app)

[![Portfolio](https://img.shields.io/badge/Portfolio-kryzonix.netlify.app-E10600?style=for-the-badge&logo=netlify&logoColor=white)](https://kryzonix.netlify.app)
[![Instagram](https://img.shields.io/badge/Instagram-%40kristianpro-111111?style=for-the-badge&logo=instagram&logoColor=E10600)](https://instagram.com/kristianpro)

</div>

## kryzonix.py

```python
class Ade:
    name = "Ferdinandus Ade Kristian"
    alias = "kryzonix"
    base = "Jakarta, Indonesia"
    school = "Tarakanita University (undergrad)"
    motto = "Simply Lovely"

    hardware = ["custom PC builds", "crash repairs", "thermal tuning"]
    embedded = ["Arduino", "ESP32", "KiCad PCB prototypes"]
    open_to = ["builds", "repairs", "collabs"]
```

## bench.py

```python
SUSPECTS = ["psu", "ram", "thermals", "bios", "storage", "drivers"]


def build_pc(parts):
    pc = assemble(parts)
    pc.route_cables(clean=True)
    pc.stress_test()
    return pc if pc.is_quiet() and pc.is_stable() else pc.tune()


def diagnose(pc):
    # crashes are rarely random
    while pc.crashes():
        for part in SUSPECTS:
            if pc.test(part).failed:
                pc.fix(part)
                break
        else:
            pc.reseat_everything()
    return "stable"
```

## projects.py

```python
projects = {
    "discord-music-bot": {
        "stack": ["Node.js", "discord.js", "Lavalink"],
        "does": "queues, saved playlists, reconnects on its own",
        "used_by": "2-3 servers",
    },
    "pc-diagnostics": {
        "does": "component-level troubleshooting, BIOS recovery, clean wiring",
    },
    "esp32-controllers": {
        "stack": ["Arduino", "ESP32", "KiCad"],
        "does": "hardware monitors and custom peripherals",
    },
}
```

## sim_racing.py

```python
most_played = ["Assetto Corsa Competizione", "Assetto Corsa", "F1 25"]
favorite_car = "McLaren 720S Evo GT3"
favorite_track = "Nordschleife"

while True:
    drive(favorite_car, favorite_track)
    if lap_time < personal_best:
        break
```

## stack

![skills](https://skillicons.dev/icons?i=js,nodejs,arduino,linux,windows,git,github,discord,netlify&perline=9)

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Lavalink](https://img.shields.io/badge/Lavalink-1a1a1a?style=flat-square)
![AMD](https://img.shields.io/badge/AMD-ED1C24?style=flat-square&logo=amd&logoColor=white)
![Intel](https://img.shields.io/badge/Intel-0071C5?style=flat-square&logo=intel&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white)

## fortune

[![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)](https://github.com/PiyushSuthar/github-readme-quotes)

## contact.py

```python
if __name__ == "__main__":
    print("https://kryzonix.netlify.app")  # portfolio
    print("@kristianpro")                  # instagram
```

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:0b0b0f,60:3a0000,100:e10600&height=100&section=footer)

</div>
