HOW TO OPEN AND USE THE CODES
  1.	Click On The “<> Code”
  2.	From The Down Menu Click on Download ZIP
  3.	After Download Unzip the file content
  4.	Open up your favorite browser
  5.	open up a new tab and search for “Colab” on Google
  6.	you will find “Google Colab” and then you can open it by clicking on it
  7.	if you have not made an account with “Google Colab” before then you have to create one by clicking on sign-in
  8.	you must be directed to the “Welcome page of Colab” now
  9.	on the top menu click on “File”
  10.	from the submenu select “Upload Notebook”
  11.	you must be prompted with the new window named “Open Notebook”
  12.	in that same window click on “Browse”
  13.	you must be opened with a new window where you have to select the location of the “.ipynb” that you have just downloaded
  14.	for the same you have to select and open the folder that you have just downloaded and unzipped before
  15.	select the latest version of “.ipynb” from the file and press open
  16.	it will take a few and then it should open up
  17.	now press “CTRL+F” to open up the text finder
  18.	inside the finder paste the following “ngrok.set_auth_token”
  19.	now we have to replace the “YOUR_AUTHTOKEN” inside double Quotation(ngrok.set_auth_token("YOUR_AUTHTOKEN")
  20.	On your browser open a new tab and search for “ngrok” or  (ngrok | API Gateway, IoT Device Gateway, Secure Tunnels for Containers, Apps & APIs)  you can use the link to go to the website directly
  21.	Go to signup and create an account on “ngrok”
  22.	After signing in you will be welcomed
  23.	on the left-hand side click on “Your Authtoken”
  24.	you will see the text saying “Your Authtoken” and you will see the hidden key
  25.	you can click on “Copy” to copy your auth-token or view it by clicking on it which is in the ngrok tab
  26.	Replace your ngrok auth token with the YOUR_AUTHTOKEN on Google Colab
  27.	After applying the auth token you are ready with your first runtime test
  28.	You can press “CTRL+F9” on your keyboard or
    a.	Press “runtime” on Google Colab
    b.	From the submenu select “Run all”
  29.	Wait for your collab to connect with the runtime engine which will be shown at the bottom of the browser
  30.	Wait for every code to work
  31.	And final code to give you a output like(Streamlit app is live at: NgrokTunnel: "https://0d18-35-184-133-173.ngrok-free.app" -> "http://localhost:8501")
  32.	From there you will click on the (.ngrok-free.app) (or the first link)
  33.	You will be redirected to a new tab with a msg and a button that has typing “Visit Site”
  34.	Press “Visit Side”
  35.	Voila your Simple Web Chat Bot Will be Working NOW

HOW TO MAKE CHATBOT YOUR OWN
  1.	Press “CTRL+F9” to open the text search window
  2.	Search for “patterns”
  3.	You must be directed to a 2-D list which you can edit
  4.	On the left side after “r” inside the single quotes you can write the custom input that you might get from the user
  5.	On the right side inside the blue square brackets “[]” you can write the customized msg that you want your chatbot to answer the question with
  6.	Remember that the amount of inputs should be the same as the outputs separated with comas and single quotes (i.e., & ‘)
  7.	Also you can change the appearance of your web under the “# Streamlit app layout”
  8.	Where “st. title” will change your title and “st. write” will change the subtext on the web page

CAUTIONS
  1.	For Windows user you can use the “CTRL”
  2.	Fpr Mac users you can use “COMAND’ key instead of “CTRL”

UPDATES
  1.	Simple_Chat_Bot_V1
    a.	Basic of chatbot
    b.	You can use it on google colab easily
    c.	Basic streamlit integartion

UPCOMING UPDATES
  1.	More Streamlit features integration
  2.	Tracking of the unknown user input
  3.	Storing the unknown user input to implement it on the code
  4.	Integrating google sheets for ease of acess and unknown user input
