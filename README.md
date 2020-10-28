# pro-rata-job-search
Search Axios Pro Rata email newsletters to find VC-backed companies matching specific criteria. 

You can subscribe to the newsletter here: https://www.axios.com/newsletters/axios-pro-rata

This newsletter contains a daily summary of much of the venture capital funding activity across the globe. These companies typically use the funds to expand, or in other words, hire more employees, so are a good source of opportunities for those looking for a new role!

This script requires emails be accessible as files outside of the email client. In Outlook, this is easily done using File > Save As. In Gmail, it is less straightforward. I was able to do so by selecting the emails, right clicking and selecting "Forward as attachment" and then sending to myself. From there you can download in a zip file. The emails I worked with in this script had a .eml file format.

The target keyword can be an industry specific term, a location, or individual company. The default value of "9A=91" used in the script partially matches the UTF-8 hex encoding for ambulance, which the newsletter uses to indicate jobs related to the lifesciences industry. While not as common, the newsletter also uses a fuel pump to indicate energy industry related "x9B\xBD."

Good luck and happy job hunting!
