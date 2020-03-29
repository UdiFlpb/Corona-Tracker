# Corona-Tracker
Checks your locations based on googles data and compares it to known corona locations in ISRAEL.


הוראות שימוש:
1) יש להיכנס לקישור הבא: https://takeout.google.com/settings/takeout/custom/location_history

2) יש להכניס את שם המשתמש והסיסמא ולהוריד את נתוני המיקום שלך.

3)יש להמתין לקבלת קישור להורדת הקובץ במייל ולהוריד אותו.

4) בתוך קובץ הZIP יש להיכנס לתיקייה Takeout ולאחר מכן לתיקייה היסטוריית מיקומים.

5) יש לחלץ את הקובץ היסטוריית מיקומים.json ולשמור אותו בשם myLocations.json.

6) נדרש לחלץ את הקבצים coronaLocations.csv וtracker.exe לאותה תיקייה.

7) כעט כול שנותר הוא להפעיל את הקובץ tracker.exe ולהסתכל בקובץ התוצאות Results.txt. (צריך לגלול למטה הרבה)


--------------------------------------------------------------------------------
רשימת מקומות של חולי הקורונה המצורפת עדכנית לתאריך 26.03.2020.

ניתן להוריד רשימת מקומות שבהם שהו חולי קורונה מעודכנת מאתר משרד הבריאות בקישור הבא: https://imoh.maps.arcgis.com/apps/webappviewer/index.html?id=20ded58639ff4d47a2e2e36af464c36e&locale=he&/

יש ללחוץ על החץ הקטן למטה, ללחוץ על אפשרויות וייצא הכול לCSV.

יש לשמור את הקובץ בשם coronaLocations.csv באותה תיקייה עם tracker.exe וmyLocations.json.
