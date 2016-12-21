# ngrok

## 【 Overview 】  

開發網頁或服務的時候，如果沒有 Public IP，但又想讓別人看到此網頁或服務時，就可以使用 ngrok 的服務讓別人連進來。

## 【 Setup ngrok 】

* Download ngrok
   * [Mac OS](https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-darwin-amd64.zip)
   * [Windows](https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-windows-amd64.zip)

* Unzip
   * Mac OS
   
     ```
     unzip /path/to/ngrok.zip
     ```

## 【 Run it 】

* Python Flask

     ```
     pip install flask
     python crud.py
     ```

* ngrok

     ```
     ./ngrok http 5000
     ```
     
     ![Imgur](http://i.imgur.com/Lvt9LVi.png)
