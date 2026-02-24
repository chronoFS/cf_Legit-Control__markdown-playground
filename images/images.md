# Image tag <img/>

## Image Tag with external URL 
<img src="https://www.legitcontrol.com/timetravel.svg"> 

## Image Tag alignment

<img src="https://www.legitcontrol.com/timetravel.svg" alt="Playbook" align="right">

## Image Tag size
<img src="https://www.legitcontrol.com/timetravel.svg" alt="Playbook" width="200" >

## Image Tag internal URL

<img src="Image1.png"> 

# Markdown image syntax


## Basic syntax

![Legit Playbook](https://www.legitcontrol.com/timetravel.svg)

## With optional title (tooltip)

`![alt text](url "title")` — title appears on hover.

![Legit Playbook](https://www.legitcontrol.com/timetravel.svg "Legit Time Travel")

## Relative path (image in repo)

`![description](path/to/image.png)` — path relative to the markdown file.

![Local image](Image1.png)

## Reference-style image

Define the URL once, reuse by reference:

![Legit logo][logo]

[logo]: https://www.legitcontrol.com/timetravel.svg


### Notes

- **Alt text** is required in the brackets; use `""` for decorative images: `![](url)`.
- **Relative paths** are relative to the `.md` file; use `./Image1.png` or `Image1.png` in the same folder.
- **Sizing/alignment** in plain Markdown is not supported; use HTML `<img>` (see above) when you need width/align.
