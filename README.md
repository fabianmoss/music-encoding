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

### Friday, January 9

#### Session 1

- What is music encoding? What is it good for? 
- Why do we need standards?

**Tasks:**

1. Take a short music example (e.g. from [Bartók's _Mikrokosmos_, Vol. 1](https://imslp.eu/files/imglnks/euimg/2/21/IMSLP465640-PMLP3661-Bela_Bartok_-_Mikrokosmos.pdf); max. 2 staves) and try to communicate it to your peers only using an Excel sheet.
2. Give your sheet to a peer who then tries to write the music back into a notation software like MuseScore Studio. 
3. Reveal the original notation to your peer.
4. Discuss!

#### Session 2

- What is (the) MEI?
- MEI Guidelines Principles
- Preview of rendering MEI-encoded music example with Verovio (see How-To's above).

**Tasks:**

1. Read and work through Chapters 1.2 and 1.3 of the MEI Guidelines.
2. Understand the 4 music domains (logical, gestural, visual, analytical)
3. Understand the difference between _Events_ and _ControlEvents_
4. Understand how timestamps work. 

### Saturday, January 10

#### Session 3

- What is XML? 
- Basic XML structure ([W3Schools tutorial](https://www.w3schools.com/xml/default.asp))
- Elements and attributes

**Tasks:**

1. Develop you own XML-based music encoding scheme for a simple melody (e.g., "Ode to Joy").
2. Work through Beginners MEI tutorials: https://music-encoding.org/resources/tutorials.html
    - Quickstart
    - XML Basics and minimal MEI structure 
    - Rests
    - Chords

#### Session 4 

- The overall structure of an MEI document 
- editing XML/MEI in VS Code 

**Tasks:**

1. Read Guidelines chapter 2.1 and 2.2
2. Encode a full example using only VS Code.

#### Session 5

- General music elements 

**Tasks:**

1. Read Guidelines chapter 2.2 
2. Encode final barline, fingerings, slurs and unusual accidentals.

#### Session 6

- Common Attributes 
  
**Tasks:**

1. Read Guidelines chapter 2.3

### Friday, January, 16

#### Session 7 

- Rendering a MEI encoding using Verovio and displaying it on a website.

**Tasks:**

1. Understand the minimal structure of a HTML document.
2. Follow the instructions on https://verovio.org on how to call the library and display a music example. 

#### Session 8 

- Metadata in MEI.

**Tasks:**

1. Read Chapter 3.1--3.4 in MEI Guidelines.
2. Understand the structure of the MEI Header (besides the minimal requirements).

### Saturday, January 17

#### Session 9

#### Session 10

#### Session 11

#### Session 12

- Wrap-up, summary, discussion, and feedback
