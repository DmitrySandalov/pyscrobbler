pyscrobbler
===========

Simple last.fm scrobbler (API 2.0)

###Requirements###
* You need an API account, which includes an API key, to use the Last.fm Web Services.<br/>
For using this app you'll need 2 keys: API key & secret key.<br/>
http://www.last.fm/api/account/create

* pyscrobbler is based on requests:
<pre>
sudo apt-get install python-pip
sudo pip install -Ur requirements.pip
</pre>

###Examples###
<pre>
if __name__ == "__main__":
    api_root = 'https://ws.audioscrobbler.com/2.0/'

    api_key = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
    secret = 'yyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy'

    session_key = login('myuser', 'mypassword')
    submit('Haddaway', 'I Miss You')
</pre>

###Support###
Noticed a bug? https://github.com/DmitrySandalov/pyscrobbler/issues
