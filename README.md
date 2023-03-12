[![Add to Sidekick](https://img.shields.io/badge/Franklin-Sidekick-%23F15A3A?style=for-the-badge&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDI0LjIuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCAxNiAxNiIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgMTYgMTY7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4KCS5zdDB7ZmlsbDojRjE1QTNBO30KCS5zdDF7ZmlsbDojQzcxRjNEO30KCS5zdDJ7ZmlsbDojRkZDNDBDO30KPC9zdHlsZT4KPGc+Cgk8Y2lyY2xlIGNsYXNzPSJzdDAiIGN4PSIxLjciIGN5PSI4IiByPSIxLjciLz4KCTxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE0LjMiIGN5PSI4IiByPSIxLjciLz4KCTxjaXJjbGUgY2xhc3M9InN0MSIgY3g9IjQuNyIgY3k9IjIiIHI9IjIiLz4KCTxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjEyIiBjeT0iMiIgcj0iMS4zIi8+Cgk8Y2lyY2xlIGNsYXNzPSJzdDEiIGN4PSIxMiIgY3k9IjE0IiByPSIyIi8+Cgk8Y2lyY2xlIGNsYXNzPSJzdDIiIGN4PSI0LjciIGN5PSIxNCIgcj0iMS4zIi8+CjwvZz4KPC9zdmc+Cg==)](https://www.hlx.live/tools/sidekick/?project=&from=&giturl=https%3A%2F%2Fgithub.com%2Fhlxsites%2Fdsg%2Ftree%2Fmain)

# Dick's Sporting Goods demo
https://www.dickssportinggoods.com/s/baseball-softball-services

## Environments
- Preview: https://main--dsg--hlxsites.hlx.page/
- Live: https://main--dsg--hlxsites.hlx.live/

## Installation

```sh
npm i
```

## Tests

```sh
npm tst
```

## Authoring tips
- To link an icon, put the linked URL right after :icon:
- To link a picture, do a soft return (shift + enter) before putting the linked URL.

## Local development

1. Create a new repository based on the `helix-project-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [helix-bot](https://github.com/apps/helix-bot) to the repository
1. Install the [Helix CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/helix-cli`
1. Start Franklin Proxy: `hlx up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)

### Charity's steps
1. copy + paste into Word doc https://www.dickssportinggoods.com/s/baseball-softball-services
2. add 3 dashes in a row to create an HTML section between obvious sections
3. Add blocks (tables) based on the boilerplate cards, columns, hero, etc and add a section metadata at the end of each section that has a style name
4. add some alt text to images
5. Edit footer.doc, replace boilerplate info with what I pasted in from the live site
6. Edit nav.doc, replace with all seen in the live site. This navigation is exceptionally large, so I am typing out some placeholder notes, and creating lots of sections as I go along.
7. Take inventory of live site fonts, font sizes, breakpoints, etc and create the base CSS
8. create root-level metatdata sheet to have global metadata and to assign templates or themes
9. Create needed blocks to support the content structure
10. Create 'fragments' -- content that will be reused, but needs to be authored -- such as "This month's specials". Note that the fragments block provided does not allow for more than one section.

