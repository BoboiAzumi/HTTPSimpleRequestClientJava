# HTTPSimpleRequestClientJava
Library java sederhana yang saya buat untuk melakukan request HTTP v1. Library ini sangat sangat sederhana, cocok untuk project sederhana yang melakukan request HTTP dengan response HTML.

# Struktur
Class HTTPConnect()
|
+---- public String get(String url)
|
+---- public String post(String url, String data)
|
+---- public InputStream getInputStream(String url)
|
+---- public InputStream postInputStream(String url, String data)

# method get(String url)
Berfungsi untuk melakukan request GET dengan return String berupa HTML

# method post(String url, String data)
Berfungsi untuk melakukan request POST dengan return String berupa HTML

# method getInputStream(String url)
Berfungsi untuk melakukan request GET dengan return berupa InputStream

# method postInputStream(String url, String data)
Berfungsi untuk melakukan request POST dengan return berupa InputStream
