## Ma Structure

```
body
├── header
│   └── nav
│       ├── div.portfolio
│       │   └── h2
│       └── div.menu
│           ├── input#menu-toggle
│           ├── label
│           │   └── i.fa-solid.fa-bars
│           └── ul
│               ├── li > a[href="#home"]
│               ├── li > a[href="#about"]
│               ├── li > a[href="#services"]
│               ├── li > a[href="#portfolio"]
│               └── li > a[href="#contact"]
│
├── main
│   ├── section#home
│   │   ├── div.profil
│   │   │   ├── h3 ("Hi, Myself")
│   │   │   ├── h1 ("Dev Junior")
│   │   │   ├── h3 ("And I'm a")
│   │   │   ├── p (description)
│   │   │   ├── ul (icônes réseaux)
│   │   │   │   ├── li > i.ri-facebook-fill
│   │   │   │   ├── li > i.ri-twitter-fill
│   │   │   │   ├── li > i.ri-instagram-line
│   │   │   │   └── li > i.ri-linkedin-fill
│   │   │   └── button ("Download CV")
│   │   └── div.image
│   │       └── img[src="jenna2.png"]
│
│   ├── section#about
│   │   ├── div.maphoto
│   │   │   └── img[src="jenna1.png"]
│   │   └── div.apropos
│   │       ├── h1 ("About Me")
│   │       ├── h3 ("Frontend Developer")
│   │       ├── p (texte descriptif)
│   │       └── button ("Read More")
│
│   ├── section#services
│   │   ├── h1 ("My Services")
│   │   └── div.list
│   │       ├── div.categorie (Web Development)
│   │       ├── div.categorie (UI/UX Designing)
│   │       └── div.categorie (App Development)
│
│   ├── section#portfolio
│   │   ├── h1 ("Latest Project")
│   │   └── div.projets
│   │       ├── div.images (×6)
│   │       │   ├── img
│   │       │   └── div.images-overlay
│   │       │       ├── h3
│   │       │       ├── p
│   │       │       └── span > i.fa-solid.fa-arrow-up-right-from-square
│
│   └── section#contact
│       ├── h1 ("Contact Me!")
│       └── div.niveau
│           ├── div.maps
│           │   └── iframe (Google Maps)
│           └── div.contact
│               ├── input[type=text]
│               ├── input[type=email]
│               ├── input[type=number]
│               ├── input[type=email]
│               ├── textarea#message
│               └── button ("Send Message")
│
└── footer
    ├── p ("Copyright...")
    └── button
        └── a[href="#home"]
            └── i.ri-arrow-up-s-line
```