# Application Tiles

Customization favicon.


## Main features
- Different favicon for:
  - Apple devices (IPhone, IPad);
  - Windows Phone;
  - Android.


## Settings

 You can check availability tiles on page: admin/appearance/settings

<br>
 Also you can add setiings to theme .info file

## Example

 > settings[msapplication][tile][TileColor] = #444
 >
 > settings[msapplication][notification][cycle] = 1
 >
 > settings[msapplication][notification][frequency] = 30
 >
 > settings[msapplication][notification][polling-uri][src] = /rss.xml

The values that can take these settings can be found[here](https://msdn.microsoft.com/en-us/library/dn455106(v=vs.85).aspx)
