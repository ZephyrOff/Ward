<h3 align = "center">
    <img src = "images/logo.png" alt = "Logo" />
</h3>

---

### About

Ward is a simple and minimalistic server monitoring tool. Ward supports adaptive design system. Also, it supports dark theme.
It shows only principal information and can be used, if you want to see nice looking dashboard instead looking on bunch of numbers and graphs.
Ward works nice on all popular operating systems, because it uses [OSHI](https://github.com/oshi/oshi).

**All features tested on:** `Windows` `Linux`

<p align = "center">
    <img src = "images/preview.png" alt = "Preview Image" />
</p>

<h6 align = "center">Preview Image</h6>

---

### Installation

    Create your own .jar

    • Clone the project
    • Import project in your IDE as Maven project
    • mvn clean package

<br>

    Run .jar file

    • Download latest .jar from releases section
    • Execute jar on Windows or Linux with administrative rights
    • Enter localhost:4000 and set up application

---

### Configuration

You can create a setup.ini file where the .jar file is located to configure the application.

```ini
[setup]
serverName = VPS
theme = light
port = 2222
host = 127.0.0.1
```

- serverName for the name of the server that will be displayed on the page
- theme: dark or light
- port: Port used
- host: binding host IP