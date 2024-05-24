
<h1 align="center">אגף שומא וגביה - עיריית ירושלים</h1>


<p align="middle">
<img src="https://github.com/Tehila-David/database6419_6037/blob/main/Photos/Emblem_of_Jerusalem.svg.png" width="20%">
</p>

**מגישות: תהילה דוד & סיון לוי**

**מערכת: עיריית ירושלים**

**אגף: שומא וגביה**


# מבוא
אגף שומא וגביה הוא הגוף האחראי בעיריית ירושלים על גביית הארנונה ותשלומים עירוניים אחרים מהתושבים והעסקים בעיר. תפקידו המרכזי הוא לקבוע את שיעור הארנונה השנתי על בסיס שטח הנכס, ייעודו וערכו, ולגבות את התשלומים מבעלי הנכסים השונים.

האגף מחולק למספר מחלקות עיקריות:
1. מחלקת שומה - אחראית על חישוב שומות הארנונה לנכסים השונים בעיר על-פי נתוני שטח, ייעוד וערכים עדכניים.
2. מחלקת גבייה - אחראית על הוצאת דרישות תשלום וטיפול בגבייה בפועל של חיובי הארנונה והיטלים מהתושבים והעסקים.
3. מחלקת אכיפה וגבייה - אחראית על טיפול בחובות ארנונה מפיגורים באמצעים שונים כגון הליכי גבייה, עיקולים וכדומה.

הארגון עוסק בניהול נכסים, חיובי ארנונה ותשלומים של תושבים. הישויות העיקריות הן:
1. נכס - Asset: מייצגת נכס פיזי כגון בניין או קרקע. נכס מאופיין על ידי פרטים כמו כתובת, סוג, שטח וכן מידע על רכישת הנכס כגון תאריך ומחיר.
2. חוב - Debt: מייצגת חוב ארנונה שהתושב חייב לשלם. החוב קשור לנכס ספציפי ומכיל מידע כגון סכום החוב, תאריך יצירת החוב ומחיר/תעריף הארנונה.
3. הנחה - Discount: מייצגת הנחה שניתנת לתושבים על תשלום הארנונה. ההנחה מאופיינת על ידי אחוז ההנחה, סוג ההנחה ותוקף ההנחה. 
4. תושב - Resident: מייצגת תושב המחזיק בנכס ומחויב בתשלום ארנונה. הישות כוללת פרטים אישיים של התושב כגון שם, תאריך לידה, כתובת וכו'.
5. תשלום - Payment: מייצגת תשלום ספציפי שבוצע על ידי התושב. התשלום קשור לחשבון הארנונה של התושב וכולל מידע כמו סכום, תאריך, סוג התשלום וקבלה.
6. חשבון ארנונה - Tax_Account: מייצגת את חשבון הארנונה הכולל של התושב, המשלב את כל החיובים, ההנחות והתשלומים שבוצעו.




<h1 align="right">
ERD Diagram
</h1>  
<img src="https://github.com/Tehila-David/database6419_6037/blob/main/Photos/ERD%20diagram.png" width="98%">

<h1 align="right">
DSD Diagram
</h1>  
<img src="https://github.com/Tehila-David/database6419_6037/blob/main/Photos/DSD%20diagram.png" width="98%">

<h1 align="right">
Oracle DSD Diagram
</h1>  
<img src="https://github.com/Tehila-David/DBProject_324926419_324866037/blob/main/Photos/DSD%20Oracle.png" width="98%">

<h1 align="right">
CreateTable Commands
</h1>  
<img src="" width="98%">

{% raw %}
https://github.com/Tehila-David/DBProject_324926419_324866037/blob/main/stage%20A/createTables.sql
{% endraw %}

<h1 align="right">
Desc Command
</h1>  
<img src="" width="98%">

#  שיטות להכנסת נתונים
##  ייבוא נתונים מקובץ טבלאי 


##  ייבוא נתונים מקובץ טקסט

##  הכנסת נתונים ע"י Data Generator
# גיבוי ושחזור נתונים
## גיבוי נתונים
## שחזור נתונים



