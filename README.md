# examples-vivliostyle-pagedjs

This is a project to compare and verify [Vivliostyle](https://vivliostyle.org/) and [Paged.js](https://www.pagedjs.org/).

## Setup

This project gets the sample from an external repository. Therefore, please `git clone` with the following command.

```
$ git clone --recursive https://github.com/akabekobeko/examples-vivliostyle-pagedjs examples-vivliostyle-pagedjs
```

If you are doing a normal git clone, run the following command.

```
$ cd examples-vivliostyle-pagedjs
$ git submodule update --init --recursive
```

The commands that this project runs are defined as [npm-scripts](https://docs.npmjs.com/misc/scripts). Therefore, please prepare an environment where Node.js + npm can be used in advance.

Install npm used by this project.

```
$ cd examples-vivliostyle-pagedjs
$ npm install
```

## Build

The command to create PDF file is `v:*` for Vivliostyle and `p:*` for Paged.js. See `package.json` for `*`. Execute `build:vivliostyle` or `build:pagedjs` to create PDF files in bulk.

```
$ npm run v:viv01
$ npm run p:viv01

$ npm run build:vivliostyle
$ npm run build:pagedjs
```

## License

[MIT](LICENSE)
