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

## Preview

The command to run the preview is `vp:*` for Vivliostyle and `pp:*` for Paged.js. See `package.json` for `*`.

```
$ npm run vp:gon
$ npm run pp:gon
```

## Build

The command to create PDF file is `vb:*` for Vivliostyle and `pb:*` for Paged.js. See `package.json` for `*`. Execute `vivliostyle:build` or `pagedjs:build` to create PDF files in bulk.

```
$ npm run vb:gon
$ npm run pb:gon

$ npm run vivliostyle:build
$ npm run pagedjs:build
```

## License

[MIT](LICENSE)
