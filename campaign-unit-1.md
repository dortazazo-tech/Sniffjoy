# קמפיין 1 | SniffJoy | "הכלב המשועמם בדירה"

> חשבון מודעות: Level Up · דף: SniffJoy · יעד: sniffjoy.co
> **הקמפיין נבנה במצב מושהה. מפעילים רק אחרי רכישת בדיקה אמיתית בכרטיס ישראלי.**

---

## 0. לפני שבונים: 10 דקות

| # | בדיקה | איפה |
|---|---|---|
| 1 | **אפליקציית Facebook & Instagram מחוברת ל-Shopify, עם שיתוף נתונים מקסימלי** | Shopify → Sales channels → Facebook & Instagram → Settings → Customer data sharing: **Maximum** |
| 2 | הפיקסל של SniffJoy מחובר לחשבון Level Up | Events Manager → Data sources |
| 3 | רכישת בדיקה עברה, ו-**Purchase** הופיע ב-Events Manager | Events Manager → Test events |
| 4 | הדומיין sniffjoy.co מאומת | Business Settings → Brand safety → Domains |
| 5 | האירוע Purchase מוגדר בראש סדרי העדיפויות | Events Manager → Aggregated event measurement |

**בלי סעיף 3 לא מפעילים.** בלי Purchase שנרשם, מטא לא יודעת למי להראות את המודעות.

---

## 1. מבנה

```
קמפיין:  SJ | Sales | ABO | IL Broad | Unit1 Bored Dog | 10.2026
├── A | Boredom & Damage      ₪50/יום   מודעות 1, 2
├── B | Mechanism & Nose      ₪50/יום   מודעות 3, 4
├── C | Toys & Offer          ₪50/יום   מודעות 8, 17
└── D | Video                 ₪50/יום   וידאו 01 (עם קריינות)
                              ────────
                              ₪200/יום
```

**למה ABO ולא Advantage+ / CBO:** בשלב הפיצוח רוצים לדעת **איזו זווית** עובדת. ב-CBO מטא שופכת את רוב התקציב על אד-סט אחד אחרי יום, ושלושת האחרים לא נבחנים.

---

## 2. הגדרות קמפיין

| שדה | ערך |
|---|---|
| מטרה | **Sales** |
| Advantage+ campaign | **כבוי** (Manual sales campaign) |
| Campaign budget optimization | **כבוי** (התקציב ברמת אד-סט) |
| A/B test | כבוי |
| Special ad category | אין |

## 3. הגדרות אד-סט (זהות בכל הארבעה, חוץ מהשם)

| שדה | ערך |
|---|---|
| Conversion location | Website |
| Pixel / Event | SniffJoy pixel · **Purchase** |
| Performance goal | Maximize number of conversions |
| Bid strategy | Highest volume (בלי Cost cap בשלב הזה) |
| Daily budget | **₪50** |
| Attribution | 7-day click, 1-day view |
| מיקום | **ישראל** |
| גיל | **24–55** |
| מגדר | הכל |
| שפה | עברית |
| Detailed targeting | **ללא** (Broad, הקריאייטיב עושה את הטירגוט) |
| Advantage+ audience | כבוי בשלב הזה, כדי שהגיל יישמר |
| Placements | Advantage+ placements |

---

## 4. מודעות

**לכל המודעות:**
- **כפתור:** Shop Now
- **תיאור:** משטח הרחה ₪139 · 2 ב-₪219
- **Multi-advertiser ads:** כבוי
- **שיפורי קריאייטיב אוטומטיים (Advantage+ creative):** **לכבות הכל.** מטא מוסיפה מוזיקה, משנה טקסט ומחתכת את התמונה, וזה הורס את הבדיקה.

**קישור יעד:** `https://sniffjoy.co/products/משטח-הרחה-אינטראקטיבי-לכלבים?view=bored`

> `?view=bored` מציג את גרסת הקמפיין של הדף: כותרת "זה לא רעב. זה שעמום." שממשיכה את המודעות. אותו מוצר, אותו עיצוב, אותן חבילות. הגרסה נמצאת בערכת הנושא **"SniffJoy — קמפיין 1 (לפרסום)"**, ועובדת רק אחרי שמפרסמים אותה.
**URL parameters** (שדה נפרד במודעה):
`utm_source=meta&utm_medium=paid&utm_campaign=unit1&utm_content={{ad.name}}`

| אד-סט | שם מודעה | קובץ | כותרת | טקסט ראשי |
|---|---|---|---|---|
| A | ad01-not-hunger | `creatives/final/01-not-hunger.png` | זה לא רעב. זה שעמום. | מודעה 1 ב-`creatives/ad-copy-wave-1.md` |
| A | ad02-torn-couch | `creatives/final/02-torn-couch.png` | משעמם לו. לא רע לו. | מודעה 2 |
| B | ad03-stop-bowl | `creatives/final/03-stop-bowl.png` | תפסיקו להאכיל אותו מקערה | מודעה 3 |
| B | ad04-nose | `creatives/final/04-nose-tires-head.png` | הרחה מעייפת לו את הראש | מודעה 4 |
| C | ad08-not-a-toy | `creatives/final/08-not-a-toy.png` | זה לא צעצוע. זה האוכל שלו. | מודעה 8 |
| C | ad17-two-mats | `creatives/final/17c-one-floor-one-wash.png` | 2 משטחים ב-₪219 במקום ₪278 | מודעה 17 (תיאור: חוסכים ₪59 על הזוג) |
| D | vid01-bored-dog | `creatives/video/sniffjoy-video-01-vo.mp4` | משעמם לו. לא רע לו. | מודעה 2 |

---

## 5. כללי החלטה

**לא נוגעים ב-72 השעות הראשונות.** מטא בלמידה. כל שינוי מאפס אותה.

| מצב | פעולה |
|---|---|
| מודעה הוציאה **₪150 בלי רכישה** | מכבים את המודעה |
| אד-סט הוציא **₪300 בלי רכישה** | מכבים את האד-סט |
| CTR (link) מתחת ל-0.8% אחרי ₪100 | ההוק לא עובד. מכבים |
| יש קליקים, אין Add to cart | הבעיה בדף, לא במודעה |
| יש Add to cart, אין Purchase | הבעיה בצ'קאאוט, **עוצרים הכל** ובודקים תשלומים |
| **CPA מתחת ל-₪77, שלושה ימים ברצף** | ווינר. מעלים תקציב ב-20% כל 48 שעות, ומייצרים 5–10 וריאציות מאותו מסר |
| ROAS מעל 1.8 (או 2.5 אם עוסק מורשה) | רווחי. ממשיכים לסקייל |

**ה-CPA המקסימלי:** ₪77 למשטח בודד · ₪140 לזוג (מ-`00-source-data.md`).

---

## 6. מה לבדוק כל יום (5 דקות)

1. הוצאה מול רכישות לכל מודעה
2. Shopify → Analytics: הזמנות לפי `utm_content`
3. תגובות על המודעות: לענות תוך שעות. תגובה שלא נענתה על מודעה נראית כמו עסק שלא קיים
