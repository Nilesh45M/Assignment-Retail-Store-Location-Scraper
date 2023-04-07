Approach:

For this assigment, I used Python programming language and some external libraries like requests, json and csv. We sent a POST request to the store locator API of each brand's website and received the data in JSON format. We then parsed the JSON data and extracted the required information to write to a CSV file.

The approach involved analyzing the website's network traffic using the browser developer tools to identify the API endpoint and parameters used for retrieving the store location data. I then used Python to mimic the network request and retrieve the data in a JSON format. I then extracted the relevant data and saved it in a CSV file for further analysis.

Challenges:

One of the main challenges I faced was finding the right API endpoint and parameters required to retrieve the store location data. In some cases, the endpoint was obfuscated or required additional headers to be sent with the request. In such cases, I had to resort to analyzing the website's JavaScript code to identify the API endpoint and parameters.

Another challenge was parsing the response text, which was often in JSON format. Sometimes, the JSON data contained nested structures, which required additional parsing to extract the relevant data.

To overcome these challenges, I used a combination of web analysis tools and Python libraries to identify the required API endpoint and parameters and parse the response text. I also used the trial-and-error method to test different requests and parameters until I was able to retrieve the required data.

Overall, the project involved a lot of experimentation and improvisation, but with the help of Python and web analysis tools, I was able to overcome the challenges and successfully retrieve and analyze the store location data.
