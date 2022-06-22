# <img height=30 src="https://latex.codecogs.com/svg.latex?{\textsf{\bfseries\color[RGB]{255,216,102}Fore}}" alt="Fore">

Fore is a LaTeX class that extends `beamer` for procedural and rapid build of material newsletters.

Fore provides a simple, modular and accessible component library to use as building blocks for beautiful newsletter and poster renders at speed, including functional and higher-order components, and utility classes.

---

## Installation

Clone the repo

```bash
$ git clone https://github.com/ellsphillips/fore.git

$ cd fore
```

## Features

Fore's feature list is rich and open to extension, using a component-base plug in architecture. The current list includes:

| Component | Order  | Use                                                                                                                    |
| :-------- | :----- | :--------------------------------------------------------------------------------------------------------------------- |
| Columns   | Higher | Segment the current parent into n children containers with option to auto-align column heights across the environment. |
| Page      | Higher | Beamer frame wrapper, facilitates creation, pagination and content flow.                                               |
| Rounded   | Higher | Wrap children in flexible box with standard border radius and hidden overflow.                                         |
| Tile      | Higher | Containerise data inside flexible box model with configurable colour, width and padding.                               |
| Author    | Base   | Credit content items by providing title, subtitle and image credentials.                                               |
| Article   | Base   | State handler for columnar text data with auto flow and gutter management.                                             |
| Button    | Base   | Hyperlinked button component with multiple predefined variants.                                                        |
| Calendar  | Base   | Dynamic scheduling visualiser able to highlight breakable date ranges and itemise interactive event details.           |
| Footer    | Base   | Baked `beamer` template method for sticky positioning per page. Content configurable from newsletter metadata.         |
| Foreword  | Base   | Text-wrapped container for addressing the reader.                                                                      |
| Header    | Base   | Generate banner populated using newsletter metadata and company logo.                                                  |
| Profile   | Base   | A get-to-know-me section with break-out-the-box user photo.                                                            |
| Slides    | Base   | Showcase the recent conference materials across your organisation.                                                     |
| TOC       | Base   | Jigsaw build your Table of Contents.                                                                                   |
| Updates   | Base   | Itemise your updates with clarity.                                                                                     |
| Link      | Macro  | Wrap children in anchor for internal or external linkage.                                                              |
| Spacer    | Macro  | Standardised content gutter.                                                                                           |
| Title     | Macro  | Define new sections with bold headings.                                                                                |

## Citing Fore

Please use the following BibTeX entry when citing Fore:

```BibTeX
@Misc{EP2022Fore,
  author =       {Elliott Phillips},
  title =        {Fore - Procedural material newsletters},
  howpublished = {GitHub},
  year =         {2022},
  url =          {https://github.com/ellsphillips/fore}
}
```
