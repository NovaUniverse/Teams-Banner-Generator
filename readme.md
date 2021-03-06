# ✦ MCF Teams Banner Generator
<p align="center">
  <img src="https://user-images.githubusercontent.com/66202304/160249081-1802ff23-3d7b-4ac3-af2c-6c5728c18f6d.png" width="960" />

  ## ★ A small python script we use to generate banners displaying the players participating in MCF.
</p>

## 🍭Install & Run Instructions
#### • Step 1) Download Git Repo.
```
git clone https://github.com/NovaUniverse/Teams-Banner-Generator
```

#### • Step 2) Install all required dependencies.
```cmd
cd Teams-Banner-Generator
pip install -r requirements.txt
```

#### • Step 3) Run script and drag the teams.json file in the console.
```cmd
cd src
python mcf_banner.py
```
![image](https://user-images.githubusercontent.com/66202304/160249424-11bc975c-6e42-43e0-8181-249f3b960f38.png)

#### • Step 4) DONE! The PNG should open up but it can also be found in the 'dest' folder with the following date.
![image](https://user-images.githubusercontent.com/66202304/160249393-a05f7ea4-dec1-4d2b-8e83-316df583e500.png)

## 💽Command Line Args
*(Assuming your in the src directory.)*

### MCF Banner
```
python mcf_banner.py {path to teams.json} {date: 10/04/2022} {max teams: 12} {don't open file: True} {save location: "./dest"}
```
#### To settle with default options you can just pass "None", "none" or "null". Also we drop the final rendered images in a "dest" folder in the root directory but this can be changed in the cli args.

**© Copyright (C) 2022 Nova Universe (Under the [GPL-3.0 License](LICENSE.md))**
