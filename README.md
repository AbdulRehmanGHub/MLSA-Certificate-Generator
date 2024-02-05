# MLSA-Certificate-Generator

This repo simply uses a template certificate docx file and generates certificates in
both docx and pdf.

First of all, give a star to this repository.

## Run these commands in your terminal

```
git clone https://github.com/abdulrehmanghub/MLSA-Certificate-Generator/
cd MLSA-Certificate-Generator
```

## Customization and Generation

### Step 1: Adding a list of participants
![ss_1](https://github.com/AbdulRehmanGHub/MLSA-Certificate-Generator/assets/105493274/9d997754-5fda-491a-affc-30e0ad73deb2)
<br>

- Now Copy the name of the Participants of your event and paste their names in the file  `Event Participants.csv` present in the folder `Templates`.
- Save the changes
- No additional field is required only the names of participants can work.
  

### Step 2: Modifying your event details
![ss_2](https://github.com/AbdulRehmanGHub/MLSA-Certificate-Generator/assets/105493274/b6e9cdec-0a5e-4791-bf18-30c8dc02326b)
<br>

- Open the file `main_certificate.py`
- Move to line 53 and Write the name of the "Host" instead of "Your Name"
- Move to line 56 and Write "Event name" instead of "Your Event Name"
- Save the changes.

### Step 3: Open Terminal

### ``` For Windows Users```

```
pip install -r requirements.txt
python main_certificate.py
```

<br>

### ``` For Mac Users```

```
pip3 install -r requirements.txt
python3 main_certificate.py
```

### Step 4: Certificates

- Look for the Output Folder in the "MLSA-Certificate-Generator" folder on your pc
- There you find 2 separate folders namely "Doc" and "PDF" with your certificates ready
- Extract the certificates and share them with your participants

### Certificate Template
![cert template](https://github.com/AbdulRehmanGHub/MLSA-Certificate-Generator/assets/105493274/eb497bc1-880b-4c33-aee4-bd5e660805b8)



## Well Done!!! You Did It.
