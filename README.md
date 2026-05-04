[README.md](https://github.com/user-attachments/files/27372067/README.md)
# Carolina Prado — Academic Portfolio

Personal academic website hosted via GitHub Pages.

## Structure

```
.
├── index.html          # Main site file
├── assets/
│   ├── photo.png       # Profile photo (transparent background)
│   ├── capa.jpeg       # Book cover
│   ├── contracapa.jpeg # Book back cover
│   ├── hist1.jpeg      # Book interior page
│   ├── hist2.jpeg      # Book interior page
│   └── hist3.jpeg      # Book interior page
└── cv.pdf              # Curriculum Vitae (add your own)
```

## How to update

### Update content
Edit `index.html` directly. The main sections are clearly marked with HTML comments:
- `<!-- About -->`
- `<!-- Research -->`
- `<!-- Teaching -->`
- `<!-- Books -->`
- `<!-- Contact -->`

### Add a new paper
Find the `<!-- Research -->` section in `index.html` and copy the `.paper` block, updating the title, abstract, and link.

### Update the CV
Replace `cv.pdf` in the root of the repository with your updated file.

### Update the profile photo
Replace `assets/photo.png` with a new PNG file (transparent background recommended).

