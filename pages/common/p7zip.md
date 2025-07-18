# p7zip

> Wrapper of 7-Zip file archiver with high compression ratio.
> Internally executes either 7za or 7zr command.
> More information: <https://p7zip.sourceforge.net>.

- Archive a file, replacing it with a 7zipped compressed version:

`p7zip {{path/to/file}}`

- Archive a file keeping the input file:

`p7zip {{[-k|--keep]}} {{path/to/file}}`

- Decompress a file, replacing it with the original uncompressed version:

`p7zip {{[-d|--decompress]}} {{compressed.ext}}.7z`

- Decompress a file keeping the input file:

`p7zip {{[-d|--decompress]}} {{[-k|--keep]}} {{compressed.ext}}.7z`

- Skip some checks and force compression or decompression:

`p7zip {{[-f|--force]}} {{path/to/file}}`
