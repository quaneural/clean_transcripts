# clean_transcripts_cxs
Scripts to convert MSFT Teams' meeting transcripts to dialogue text.

To start using clean_transcripts, you need to follow a few steps to get set up.

1. Open a Powershell window or terminal window on your device.
2. Download python - Copy/Paste line 8 below and hit enter in your Powershell window.
    Invoke-WebRequest -Uri https://www.python.org/ftp/python/3.9.7/python-3.9.7-amd64.exe -OutFile python.exe
   Install python - Copy/Paste line 10 below and hit enter in your Powershell window.
    ./python.exe /quiet InstallAllUsers=1 PrependPath=1 Include_test=0
3. Download pip - Copy/Paste line 12 below and hit enter in your Powershell window.
    Invoke-WebRequest https://bootstrap.pypa.io/get-pip.py -OutFile get-pip.py
   Install pip - Copy/Paste line 14 below and hit enter in your Powershell window.
    python get-pip.py
4. Pip install the necessary modules for Clean_Transcript.py (COPY/PASTE the following lines)
    pip install tkinter
    pip install nltk
    pip install 
5. Type python <FILEPATH>\Clean_Transcript.py (If downloaded on Windows this will be something like C:\Users\your_username\Downloads)
    A GUI should appear prompting you to select the file to be cleaned. 
6. In the GUI window, click Select File, navigate to the file you wish to clean in your file explorer, click Clean up file.
   This will create a new cleaned up text file in the same location as the file you selected. Enjoy!
   
