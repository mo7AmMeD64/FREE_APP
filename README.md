# FREE_APP

Easy TV catalog for the apps in this repository.

Catalog URL:

```
https://raw.githubusercontent.com/mo7AmMeD64/FREE_APP/main/data.json
```

## Adding an app

1. Put the icon in `img/` (PNG or JPG).
2. Add an entry to `data.json`:

```json
{
  "name": "App Name",
  "version": "v 1.0",
  "image": "https://raw.githubusercontent.com/mo7AmMeD64/FREE_APP/main/img/icon.png",
  "category": "سينما",
  "download1": "https://example.com/app.apk",
  "button1": "تحميل"
}
```

`download1` must be an HTTPS link to an APK or a page that ends in `.apk`. Empty
`download2`/`button2`, `username`, `password`, and `activation_code` are hidden by Easy TV.

Easy TV reads this file together with the main catalog, so entries appear alongside the
existing apps after the app syncs (startup or refresh).
