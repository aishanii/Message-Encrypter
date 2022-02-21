# Message-Encrypter

A simple message encryption GUI software made in Python based on symmetric-key encryption.<br>
It utilizes a key table which has byte values for every alpabhet of the English language. <br>

[Source of the key table](https://www.fileformat.info/info/charset/UTF-8/list.htm)


![onee](https://user-images.githubusercontent.com/84021861/154902032-ee95dbe5-bde7-485c-a8a6-20b898369f09.jpg)
![twoo](https://user-images.githubusercontent.com/84021861/154902133-805d00ff-ddbb-4d4a-a5bd-fbeed8805b64.jpg)

<br>


## How to run the application?
Run the *main.pyw* file and enter the message to be encrypted or decrypted.

<br>

## How to use the application as .exe?
#### Step 1: 
<p>Install Pyinsntaller and Pandas using Command Prompt, if not already installed.</p> <br>
<pre><code>pip install pyinstaller
</code></pre><br>
<pre><code>pip install pandas
</code></pre>

#### Step 2: 
On the Command Prompt, navigate to the folder where the Python file is located.
<pre><code>cd C:\Users\UserName\Downloads
</code></pre>

#### Step 3: 
Type the following to build the .exe file:
<pre><code>pyinstaller --onefile main.py
</code></pre>

#### Step 4: 
After the success message, look for the 'dist' folder in the same directory.
There you'll find your .exe file ready to be used. 

