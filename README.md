# ASP.NET Document Management
 
 A web document management app built with [Dynamic Web TWAIN](https://www.dynamsoft.com/web-twain/overview/), HTML5 and ASP.NET.

## Usage

1. Deploy the project.

    **Windows**

    Add the project to IIS and change the port number to 9000.

    **Linux**

    Install [mono](https://www.mono-project.com/download/stable/#download-lin-ubuntu) and SANE:

    ```
    sudo apt install mono-xsp4 sane
    ```

    Start the web server:

    ```bash
    xsp4 --port 9000
    ```

2. Visit `http://localhost:9000/UploadWithHTTP.html` in your web browser.

    ![ASP.NET document management](https://www.dynamsoft.com/codepool/img/2019/02/linux-scan-doc.PNG)


## Blog
[How to Use Mono to Run ASP.NET C# Code in Ubuntu Linux](https://www.dynamsoft.com/codepool/use-mono-run-aspnet-ubuntu-linux.html)
