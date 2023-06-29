# asherwebsite.github.io

## Dev FAQ:
### Why is half the site missing?
Jquery is throwing a CORS error. Instead of opening index.html directly, run it on localhost--the easiest ways to do this are Node.js http-server or python http.server.

### How do I add new images?
1. Add the file to the images folder
2. Go to https://docs.google.com/spreadsheets/d/1Tl4CCd5JnAgVxmHjdPEg77ID9W_lb9OmsAHKg8e-xNQ/edit?skip_itp2_check=true&pli=1#gid=0
3. Fill out the appropriate information
4. Download the spreadsheet as a csv file
5. Rename and replace the existing assets/data/imagedata.csv file with the new csv

### How do I add filters?
0. Add the desired filter to assets/data/filters.txt if it does not already exist
1. Go to https://docs.google.com/spreadsheets/d/1Tl4CCd5JnAgVxmHjdPEg77ID9W_lb9OmsAHKg8e-xNQ/edit?skip_itp2_check=true&pli=1#gid=0
2. Add the filter to the the filters column for the image, separating multiple filters with ", "
3. Redownload and rename/replace the imagedata csv file


TODO:
Add photos and text. 
Change color scheme of the website. 
