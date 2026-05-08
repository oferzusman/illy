Illy Zussman Real - v2

מה יש בחבילה:
- index.html  -> עמוד הקישורים הראשי
- gallery.html -> עמוד גלריית תמונות
- assets/ -> כל התמונות והנכסים

העלאה ל-Cloudflare Pages:
1. Cloudflare Dashboard
2. Workers & Pages
3. Create / Pages
4. Direct Upload
5. להעלות את ה-ZIP הזה


עדכון v3 לדומיין:
- כתובת ציבורית מומלצת: https://zeuschef.co.il/illy/
- נוספה canonical לכתובת הזו.
- נוספה base דינמית כדי שהקבצים יעבדו גם תחת /illy/ וגם בכתובת המקורית של Cloudflare Pages.
- מומלץ להגדיר Redirect מ־/illy אל /illy/ כדי למנוע בעיות נתיבים.
- מומלץ לוודא שה־route ב־Cloudflare תופס גם:
  /illy
  /illy/*
