# Fysus v0.1 Stable

**Filesystem Census & Duplicate Finder**

Fysus is a Python-based tool that scans your filesystem and provides:

- **Lite Scan (-l)** → Count files quickly  
- **Full Scan (-f)** → Hash and record all files  
- **Clone Scan (-c)** → Find duplicate files by SHA256 hash  
- **Output (-o PATH)** → Save results to custom location (default: Desktop/PS_OUT)

---

## Install
```
Clone the repo:
git clone https://github.com/YOURUSERNAME/fysus.git
```
## go to file location
```
cd fysus
```
## Run
```
python fysus.py
```
## Usage Flags
```
python fysus.py -f       # full scan
python fysus.py -l       # lite scan
python fysus.py -c       # clone scan
python fysus.py -o ./out
```
## Output
```
~/Desktop/PS_OUT/fysus_results.json
```
just a short little project to learn a few basics for my python journey.

### possible future additions Roadmap
---
|Progress bar / live status output|
|Multi-threaded hashing           |
|Export results to CSV / HTML     |
|Antivirus-style integrations     |
---
