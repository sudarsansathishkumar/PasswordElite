# Password Elite - Your secured password vault

<h3>Basic Solution of the Project:</h3>
			We have developed a windows application in which we can store the information of a certain domain with their passwords. It contains three pages: login, signup, user details pages. It works in a way in which the domain name, username and passwords are stored in a database in an encrypted format. Since it needs the decryption code to view the original text, no one can able to view the user’s details from outside. The passwords are generated randomly and also it can be edited by the user. All the domains with their passwords which are added by the user can be viewed by them in a tabular format.	
<h3>Modules with Explanation and Use Cases:</h3>
<ul>
  <li>
    random: random module is used to select or generate random things. Here we used it to generate the password randomly.
  </li>
  <li>
    PyQt5: pyqt5 is a GUI based python module. Using this module, we can create user interfaces which can be converted into python scripts.  
  </li>
  <li>
    sqlite3: sqlite3 is also a python module, which is used to work with databases. Here we used this module to store all the information of the users in tabular format. This module is easy to use i.e., data can be easily inserted and retrieved.
  </li>
  <li>
    time: time module in python is used to work with time calculations. Here we used it to track the activity of the user i.e., we track the time of the user signing and the time of adding new password to their database.
  </li>
</ul>
<h3>How to use it?</h3>
<p>First you need to check for the required libraries: pyqt5 (<code>pip install PyQt5</code>).<br>The libraries except pyqt5 are inbuild libraries.</p>
<p>You can directly download the PasswordElite folder from this repository and run the login.py (or) signup.py file.</p>
<h3>Details</h3>
<p>Language: Python (with few lines of CSS to style the components)<br>Libraries: PyQt5, sqlite3, time, random</p>
<h3>Future Development</h3>
<p>The Future scope of this project is to be developed as a web based application using MERN stack, so that any user can able to access their credentials from anywhere through a cloud platform.</p>
