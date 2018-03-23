Scrape the Harvard Q Guide.

## Usage

Running `scrape.sh` will prompt for a Q Guide ID to scrape.

Running `scrape.sh $COURSEID` will scrape the given id.

Running `scrape.sh $MIN $MAX` will scrape ids from `$MIN` to `$MAX` (exclusive of `$MAX`).

You can specify the environment variables `COOKIE` and `THREADS` using `export COOKIE=...` and `export THREADS=...` to specify the `courses.cs50.net` cookie and number of threads to use to download, respectively.
