# OblEnergoGrafic
OblEnergoGrafic - bot for tg, which takes a picture from the site and sends it to you in tg using the /file command  
### config.py
create file config.py:  
TOKEN = 'YourToken'  
### url
url = "your url"  
### path
save_path = r"C:\Users\q2pj\OneDrive\Desktop"  
file_path = r'C:\Users\q2pj\OneDrive\Desktop\grafik0.png'  
### TG
send name, ID  
dispatcher.add_handler(CommandHandler("start", start))  
send grafik0.png  
dispatcher.add_handler(CommandHandler("file", send_file))  
path on F12 (in browser)  
img_element = browser.find_element(By.XPATH, "//img[contains(@src, '/upload/current-timetable/')]")  
