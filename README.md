# YouTube-Upload-Data-Processor

This repository is intended for a very specific task. 
The code in this repository can process a specifically formatted google spreadsheet in a way
which can be easily used with another particular third party tool which uploads google drive videos to users youtube channel.

### Things You Need:

---

1. A Google Sheet file in your drive. The format of the google sheet should be exactly like [this google sheet file](https://docs.google.com/spreadsheets/d/1dAhC7QMI6YyvPIwr0DfQoLd8Knc1YCCFybUdkKTq22I/edit?usp=sharing).
2. Now you have to copy the code in [copyThis.gs](https://github.com/s-shifat/YouTube-Upload-Data-Processor/blob/main/copyThis.gs) file and paste that into the **Script editor**.
  * Go to **Tools**>**Script editor** from the spread sheet ui. This will open an script editor in a new tab of your browser.
  * Now open [copyThis.gs](https://github.com/s-shifat/YouTube-Upload-Data-Processor/blob/main/copyThis.gs), copy the code and paste it into the editor you just opened.
  * Hit **ctrl** + **s** from your key board, give a project name and save it.
3. In the code, there is a PROJECT ID at the first line. Copy this.
  * Now from this editor go to **Resources** > **Libraries...**. Paste the PROJECT ID you have copied into the **Add a library** section and click on **Add** button.
  * A Library with Title *YouTubeUploadDataProcessor* is added. Select the latest version, which is currently 4.
  * Beforre clicking on save, the window should look similar to [this](https://github.com/s-shifat/YouTube-Upload-Data-Processor/blob/images/LibrariesWindow.JPG). Now click on Save.
  Note: If there is a persmission issue, contact me.
