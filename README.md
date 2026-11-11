# Dino2Sims

Live Sound Engineering Simulations

האתר: https://dino2code.github.io/Dino2Sims/

## מה יש כאן

| תיקייה | תוכן |
|---|---|
| `index.html` | דף הבית, עם קישורים לסימולטורים |
| `vocal-compressor/` | סימולטור קומפרסור לשירה: Attack, Release, Ratio, Soft Knee ו-Makeup Gain, עם הדרכה בשמונה שלבים, צליל בזמן אמת, קובץ משלכם או הקלטה במיקרופון |
| `compressor-3d/` | קומפרסור בתלת־ממד איזומטרי: לולאת תופים מסונתזת דרך קומפרסור feed-forward, עם מסלולי Input/Threshold, Gain Reduction ו-Output, עקומת העברה ריבועית, Knee, צליל והשוואת Bypass |
| `delay-calculator/` | מחשבון דיליי רמקולים: הדיליי לרמקול שמקדים לפי הפרש המרחקים מנקודת ההאזנה, עם תיקון לטמפרטורה, גבהים והדמיה תלת־ממדית שאפשר להזיז בה את הרמקולים ואת נקודת ההאזנה |
| `line-array/` | Line Array/Ground Stack באולם: מצב בהיר/כהה, חתך צד עם מידות אולם מתכווננות (עומק, שיפוע, תחילת שיפוע, מיקום FOH), גובה מדידה לקהל יושב או עומד, גובה במה ל-ground stack, מפת רמות (Pink או פס 1/3 אוקטבה), line array תלוי מול ground stack על 2 סאבים, זוויות ו-AutoSplay, קווי כיוון וזריקה, אורך המערך ומרחק המעבר לשדה רחוק (van Veen), מגבלות תלייה לפי d&b Y-Series והדגמת site / frame angle |
| `sub-arrays/` | Sub Array Lab: מפת רמות מלמעלה של מערכי סאבים: סאב אחד, End fire (עם אזהרה על 2 סאבים), Gradient in-line, Gradient FBF ו-Gradient 3:1 כערימות, ו-Arc (פיזי או בדיליי). שורה של כמה מערכים במרווח מתכוונן, Left / Right, מנעול מיקומים, תדר בודד או פס 31.5–125 Hz, טבלה לכל סאב (מיקום, כיוון, דיליי, polarity, gain, mute), Polar ותגובת תדר. לפי McCarthy פרק 10, d&b TI 330 ו-L-Acoustics KS28 |
| [AudiofileCheck](https://dino2code.github.io/AudiofileCheck/) (repository נפרד) | AudioCheck: בדיקת האיכות האמיתית של קובצי אודיו, כולל bit depth, sample rate, מקור lossy, ויניל, מאסטרינג וציון איכות |

כל סימולטור הוא קובץ HTML אחד שעובד בדפדפן, בלי התקנה ובלי שרת.

## הערה

ההדמיות ממחישות עקרונות ואינן מדידה. המודלים והמספרים אינם לקוחים מספרי הקורס. 
 