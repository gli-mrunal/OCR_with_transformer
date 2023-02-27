# OCR_with_transformer

- https://labelstud.io/
- https://paperswithcode.com/dataset/rvl-cdip  dataset
- https://huggingface.co/datasets/naver-clova-ix/cord-v2'


```python

# Install the package
# into python virtual environment
pip3 install -U label-studio
# Launch it!
label-studio

```

output

```sh
(base) C:\Users\Student>label-studio
Current platform is win32, apply sqlite fix
Can't load sqlite3.dll from current directory
=> Database and media directory: C:\Users\Student\AppData\Local\label-studio\label-studio
=> Static URL is set to: /static/
=> Database and media directory: C:\Users\Student\AppData\Local\label-studio\label-studio
=> Static URL is set to: /static/
Starting new HTTPS connection (1): pypi.org:443
https://pypi.org:443 "GET /pypi/label-studio/json HTTP/1.1" 200 55841
NumExpr defaulting to 8 threads.
Initializing database..
Performing system checks...

[2023-02-26 22:11:27,842] [django::register_actions_from_dir::97] [INFO] No module named 'data_manager.actions.__pycache_'
[2023-02-26 22:11:27,842] [django::register_actions_from_dir::97] [INFO] No module named 'data_manager.actions.__pycache_'
System check identified no issues (1 silenced).
February 26, 2023 - 22:11:28
Django version 3.2.16, using settings 'label_studio.core.settings.label_studio'
Starting development server at http://0.0.0.0:8080/
Quit the server with CTRL-BREAK.
[2023-02-26 22:11:38,253] [django.server::log_message::161] [INFO] "GET / HTTP/1.1" 302 0
[2023-02-26 22:11:38,253] [django.server::log_message::161] [INFO] "GET / HTTP/1.1" 302 0
[2023-02-26 22:11:38,716] [django.server::log_message::161] [INFO] "GET /user/login/ HTTP/1.1" 200 2232
[2023-02-26 22:11:38,716] [django.server::log_message::161] [INFO] "GET /user/login/ HTTP/1.1" 200 2232

```
