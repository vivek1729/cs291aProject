# cs291aProject (defunkt)
Project repo for Deep Learning NLP (now defunkt)
The latest repo with updated code and README can be found at https://github.com/vivek1729/style_trasnfer_lyric

#Crawling data for a specific genre by artist
`pylrics3` can be used to fetch lyrics by artist.
Configuration variables before use:
In the `__init__` method set `self.artists` to the list of artists you want to get the lyrics for and set `self.artist_idx` to 0 or a specific index of the `self.artists` list. The script would start downloading lyrics from that artist
Add database connection params in the `self._conn = psycopg2.connect` block in `__init__` method.
