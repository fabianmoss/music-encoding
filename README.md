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


## Outline 

### Session 1

- What is music encoding? What is it good for? 
- Why do we need standards?

**Task:**

1. Take a short music example (e.g. from [Bartók's _Mikrokosmos_, Vol. 1](https://imslp.eu/files/imglnks/euimg/2/21/IMSLP465640-PMLP3661-Bela_Bartok_-_Mikrokosmos.pdf); max. 2 staves) and try to communicate it to your peers only using an Excel sheet.
2. Give your sheet to a peer who then tries to write the music back into a notation software like MuseScore Studio. 
3. Reveal the original notation to your peer.
4. Discuss!

### Session 2

- What is (the) MEI?
- MEI Guidelines Principles
- Preview of rendering MEI-encoded music example with Verovio (see How-To's above).

**Task:**

1. Read and work through Chapters 1.2 and 1.3 of the MEI Guidelines.
2. Understand the 4 music domains (logical, gestural, visual, analytical)
3. Understand the difference between _Events_ and _ControlEvents_
4. Understand how timestamps work. 

