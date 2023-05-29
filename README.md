# 📁 extcount.py 📁
![overview](https://i.imgur.com/Q0tJw6S.png)

`extcount.py` recursively counts the total number and combined size of all files per extension within a directory and prints the results to console in separate frames.

## 🛠️ Requirements 🛠️
- Python ≥3.7
- rich ≥10.1.0
- argparse ≥1.4.0

## 📥 Installation 📥
1. Download the script [manually](https://raw.githubusercontent.com/kpg-anon/extcount/main/extcount.py) or clone the repository:
    ```bash
    git clone https://github.com/kpg-anon/extcount
    ```

2. Navigate into the directory:
    ```bash
    cd extcount
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 💻 Usage 💻
By default, the current working directory will be used if none if none is provided. The optional `-e` flag is used to specify one or multiple comma-separated extensions.

Example:

```bash
./extcount.py -e jpg,mp4 <folder path>
```

This will print out the total number of .jpg and .mp4 files in the specified folder path, as well as their combined size.

![screenshot](https://i.imgur.com/HUdLfD5.png)

## TODO

- [ ] fix total_files formatting
- [ ] add optional flag to specify depth
- [ ] add functionality to print extension counts by subfolder
