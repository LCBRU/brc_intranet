# BRC Intranet

Intranet for BRC written using the lektor tool for static site creation.

## How to Develop

This intranet uses the lektor tool for developing a static HTML site.
In order to install the pre-requisites, run the command: `pip install -r requirements.txt`

To run the development server cd into the `brc_intranet` directory and run
the command `lektor server -h 0.0.0.0`

## How to Build and Deploy

Once development is completed, build the static sites by running the
command `lektor build --output-path build`.

Then check the changes into github and run the deployment Ansible script.