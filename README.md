# Demo of Build and Deploy of an Astro Project

This is a very simple Astro project that is designed to show how to deploy the static files via rsync.

Note that the Astro project is contained within a directory of the git repo (`astro-project-dir`).  The astro project is **not** at the root level of the git repo.

Therefore, with our GitHub Actions, we'll need to specify the directory in which the commands that relate to the Astro project will run.