# job-hunter

GitHub Actions workflows only. There is no application code, no data and no configuration in this repository.

The workflows run on GitHub's free public-repository runners. At run time each one checks out a separate private repository using a token stored in this repository's secrets, runs its job there, and saves the results and the logs back into that private repository. Nothing a run prints is left in this repository's logs.

These files are generated. Do not edit them here; they are overwritten from the private repository.
