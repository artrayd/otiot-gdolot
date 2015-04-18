# אותיות גדולות לשפה עברית (Capital Letters for Hebrew)
<h2> תיור כללי </h2>
<p>ברוב שפות העולם יש אותיות גדולות, כמעצב אני יכול להגיד שטקסטים הרשומים באותיות גדולות טובים יותר לקריאה בגלל ההבדלה בין סוף משפט ושמות עצם. <br><br>

בשפה העברית אין אותיות גדולות וחשבתי שצריך להיות פונט שיתן את האפשרות הזאת, זה בהחלט יכול לתת גיוון לשפה וגם הרבה יותר נוח  להשתמש. <br> <br>
</p>

<a href="" target="_blank">http://otiot.artrayd.com/</a>

<h2>שימוש ב-WEB</h2>
<p>
חיבור פונט ב-CSS

@font-face {
    font-family: "OtiotGdolot";
    src: url("font/OtiotGdolot.ttf") format("truetype");
}

body,html{
	font-family: "OtiotGdolot", arial, helvetica
}

!חשוב
שימו לב, אותיות גדולות עובדור רק בתוך תגיות של p ו-h1,2,3,4

גם צריך להוסיף rtl עם css

p, h1,h2,h3,h4,h5{
	direction: rtl;
}
</p>
