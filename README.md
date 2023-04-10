# clean_transcripts_cxs
Scripts to convert MSFT Teams' meeting transcripts to dialogue text.

To start using clean_transcripts, you need to follow a few steps to get set up.

1. Open a Powershell window or terminal window on your device.
2. Download python - Copy/Paste/Enter:
    Invoke-WebRequest -Uri https://www.python.org/ftp/python/3.9.7/python-3.9.7-amd64.exe -OutFile python.exe
3. Install python - Copy/Paste/Enter:
    ./python.exe /quiet InstallAllUsers=1 PrependPath=1 Include_test=0
4. Download pip - Copy/Paste/Enter:
    Invoke-WebRequest https://bootstrap.pypa.io/get-pip.py -OutFile get-pip.py
5. Install pip - Copy/Paste/Enter:
    python get-pip.py
6. Pip install the necessary modules for Clean_Transcript.py (COPY/PASTE/ENTER the following pip installs)
    pip install tkinter
    pip install nltk
    pip install 
7. Type python C:\Users\your_username\Downloads\Clean_Transcript.py 
    A GUI should appear prompting you to select the file to be cleaned. 
8. In the GUI window, click Select File, navigate to the file you wish to clean in your file explorer, click Clean up file.
   This will create a new cleaned up text file in the same location as the file you selected. Enjoy!
   
