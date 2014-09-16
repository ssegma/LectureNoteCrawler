LectureNoteCrawler
==================

Get all LectureNotes by Url!


How to compile it without eclipse
--------------------------------------

```sh
$ javac ./src/com/goznauk/Main.java ./src/com/goznauk/HttpDownloader.java
```



* How to run in console
---------------------------------------
```sh
$ java com.goznauk.Main
```


Troubleshooting..
-----------------------

1. java.io.FileNotFoundException
```sh
$ java com.goznauk.Main
105java.io.FileNotFoundException: http://www.broadcom.com/collateral/pb1.pdf
106        at sun.net.www.protocol.http.HttpURLConnection.getInputStream0(HttpURLConnection.java:1834)
107        at sun.net.www.protocol.http.HttpURLConnection.getInputStream(HttpURLConnection.java:1439)
108        at com.goznauk.HttpDownloader.download(HttpDownloader.java:21)
109        at com.goznauk.Main$1.run(Main.java:19)
110        at java.lang.Thread.run(Thread.java:745)
111        at com.goznauk.Main.main(Main.java:22)
```


