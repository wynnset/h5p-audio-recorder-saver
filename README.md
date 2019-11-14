# H5P Audio Recorder

## Getting started

Grab all the modules:

```bash
npm install
```

Build project for production:

```bash
npm run build
```

# How to import to Wordpress
1. After building the distribution code (step above), double-check to ensure the `dist/h5p-audio-recorder.js` is generated.
2. Remove all the unnecessary files with extension: `.Vue .yml, .babelrc, .h5pignore, .gitignore, .git, .DS_store, .md, node_modules`. Only .json and .js file extensions are allowed by WordPress.
2. Change the name of the folder to `H5P.AudioRecorderSaver` so it matches the machineName described in `library.json`.
3. Zip the entire folder and upload to Wordpress as a new library.

_Notes: Version number, title and machineName information could be found and updated in `library.json`._

## Translating

Help translate h5p-audio-recorder on [crowdin.com](https://crowdin.com/project/h5p-audio-recorder).

If your language isn't on the list, feel free to make a post in the community [forum](https://h5p.org/forum/6).

## License

*H5P Audio Recorder* is [MIT licenced](LICENCE.md)
