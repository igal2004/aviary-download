# דף הורדת האפליקציה — נוכחות חירום

## כיצד לעדכן את לינק ה-APK

לאחר כל בנייה מוצלחת ב-EAS, עדכן את `config.json`:

```json
{
  "apkUrl": "https://...",   ← הדבק כאן את הלינק החדש מ-EAS
  "version": "1.3.2",        ← עדכן גרסה
  "releaseDate": "2026-04-09"
}
```

## פרסום הדף

### אפשרות א' — GitHub Pages (חינם, קבוע)
1. צור repository חדש ב-GitHub בשם `aviary-download`
2. העלה את תיקיית `download-page/` כ-root
3. הפעל GitHub Pages מ-Settings → Pages
4. הלינק יהיה: `https://igal2004.github.io/aviary-download`

### אפשרות ב' — Netlify Drop (הכי מהיר)
1. גרור את תיקיית `download-page/` לאתר https://app.netlify.com/drop
2. תקבל לינק מיידי כמו: `https://amazing-name-123.netlify.app`

## מבנה הקבצים
```
download-page/
  index.html    ← דף ההורדה (לא לשנות)
  config.json   ← עדכן כאן את הלינק והגרסה
  README.md     ← הוראות
```
