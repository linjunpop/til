The `--jobs` option (`-j` for short) installs gems in parallel.
For example, `bundle install -j4` will use 4 workers.
We've seen speedups of 40-60% on fresh bundle installs.
To always install in parallel, run `bundle config --global jobs 4` or `set BUNDLE_JOBS`.
