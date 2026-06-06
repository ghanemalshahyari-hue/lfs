# SAT

This workspace contains a very large MBTiles dataset.

The file [maptiler-satellite-2017-11-02-v1.2-z0-z13.mbtiles](maptiler-satellite-2017-11-02-v1.2-z0-z13.mbtiles) is tracked with Git LFS, not normal git.

Use this repo pattern:

1. Create or choose a remote repo that supports Git LFS.
2. Run `git lfs install`.
3. Run `git add .gitattributes README.md`.
4. Run `git commit -m "Add LFS tracking for MBTiles"`.
5. Add your remote with `git remote add origin <remote-url>`.
6. Push with `git push -u origin main`.
7. On another machine, clone the repo and run `git lfs pull`.

If the host cannot store a 200 GB LFS object, keep the MBTiles file in external storage and use this repo only for the metadata, instructions, and any scripts that download the file.
