
Setup instruction:

1) Fetch from repository:
```
 git clone https://github.com/galicea/bryk.git
```

2) Select directory:
```
cd bryk
```

3) Setup Python 2.7 environment 

Optional (for Debian/Ubuntu):
```
sudo apt-get install python2.7-virtualenv
```
Make env.:
```
   cd ..
   virtualenv bryk --system-site-packages --python=/usr/bin/python2.7
```

4) Closure:

```
   wget https://github.com/google/closure-library/zipball/master -O closure.zip
   unzip closure.zip
   mv google-closure-library-666f6ec bryk/closure-library
```

5) Switch to Python 2.7:
```
   cd bryk
   source bin/activate
   pip install -r requirements.txt
```

6) Test:
```
#  source bin/activate
  cd bryk
  python2.7 bryk.py
```