# YouTube-Upload-Data-Processor

This repository is intended for a very specific task. 
The code in this repository can process a specifically formatted google spreadsheet in a way
which can be easily used with another particular third party tool which uploads google drive videos to spreadsheet owner's youtube channel.


### Requirements:

---

1. [Chrome Browser](https://www.google.com/chrome/)
1. Google Sheet, following [this format](https://docs.google.com/spreadsheets/d/1dAhC7QMI6YyvPIwr0DfQoLd8Knc1YCCFybUdkKTq22I/edit?usp=sharing).
2. [*YouTube Uploader for Dropbox,Drive*](https://chrome.google.com/webstore/detail/youtube-uploader-for-drop/bohlpmbngemggkpioibiahganclljlag) extension for chrome.

### Setup:

---

1. You will need a Google Sheet file in your drive. The format of the google sheet should be exactly like [this google sheet file](https://docs.google.com/spreadsheets/d/1dAhC7QMI6YyvPIwr0DfQoLd8Knc1YCCFybUdkKTq22I/edit?usp=sharing).
2. Now you have to copy the code from [copyThis.gs](https://github.com/s-shifat/YouTube-Upload-Data-Processor/blob/main/copyThis.gs) file and paste that into the **Script editor**.
    * To do that, go to **Tools**>**Script editor** from the spread sheet ui. This will open an script editor in a new tab of your browser.
    * Now open [copyThis.gs](https://github.com/s-shifat/YouTube-Upload-Data-Processor/blob/main/copyThis.gs), copy the code and paste it into the editor you just opened.
    * Hit **ctrl** + **s** from your keyboard, give a project name and save it.
3. In the code, there is a SCRIPT ID at line 3. Copy this.
    * Now from this editor go to **Resources** > **Libraries...** or **Libraries +**. Paste the SCRIPT ID you have copied into the **Add a library** section and click on **Add** button.
    * A Library with Title *YouTubeUploadDataProcessor* is added. Select the latest version, which is currently **4**.
    * Beforre clicking on save, the window will look something like [this](https://github.com/s-shifat/YouTube-Upload-Data-Processor/blob/main/images/Team%20Automation%20Tab.png). Now click on Save.
  - *Note: If there is a persmission issue, contact me.*
4. Okey, Now everything is set. Now go to the your spread sheet tab in the browser and refresh it. If the steps were followed correctly then you should see a new menu
named **Team Automation** in the spread sheet ui, similar to
[this](https://github.com/s-shifat/YouTube-Upload-Data-Processor/blob/main/images/Team%20Automation%20Tab.png).

###### **Note: You need to follow *Steps 1 to 4* only the first time you inject `copyThis.gs` into the spreadsheet. After that, for the same spreadsheet, you only have to follow the steps written below:**

### Executing ***Team Automation*** Menu:

---

To execute the program, click **Team Automation**>**Process Data for YouTube Upload**, follow the instructions. This will create a new sheet named **Processed Output** with processed data.


### Uploading to YouTube Channel:

---

1. Goto the sheet named **Processed Output**. Under the Column named **Folder Name** click on the desired folder.
2. Select the videos or all the videos you want to upload.
3. Right click from the mouse, goto **Open with**>**YouTube Uploader for Dropbox,Drive**. This will open a new tab in your browser.
4. Now go to **Video MetaData Options**. In the **Default video description** box paste the video description. You will find this from **Processed Output** sheet of your spreadsheet under a column named **Description**.
5. Now in the YouTube Uploader tab, click on **Add to Upload List**.
6. Finally, click on **Upload to YouTube** button, this will start uploading the videos.

### Tutorial and References:

---

- [Watch This Video Tutorial](https://youtu.be/P00qykDrTj4)
