# music-encoding

Some material for teaching music encoding with MEI.

## Links

- [MEI Guidelines (v5.1)](https://music-encoding.org/guidelines/v5/MEI_Guidelines_v5.1.pdf)
- [Verovio](https://book.verovio.org/first-steps/getting-started.html)
- [MEI friend](https://mei-friend.github.io//docs/)

## How-To's 

Music is encoded in `music.mei`. It can be rendered to `.svg` using Verovio:

```bash
verovio music.mei
```

For rendering on a website, we can use the skeleton HTML document `index.html` 
that includes the Verovio JavaScript library. 


Serve with 

```python
python3 -m http.server
```
