# JazzHR API Docs
*Powered by [Slate](https://github.com/lord/slate)*

JazzHR API Docs are internally generated publicly published documentation for our customer & partner facing APIs.

The latest documentation can be viewed at [https://jazzhr.github.io/api-doc](https://jazzhr.github.io/api-doc).

## Contents

- [Candidate Export Webhook API](https://jazzhr.github.io/api-doc/#candidate-export-event)

Internal Development Notes: Getting Started with Slate
------------------------------

### Prerequisites

You're going to need:

 - **Ruby, version 2.3.1 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Clone this repository to your local machine
2. Initialize and start Slate. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567.

Learn more about [editing Slate markdown](https://github.com/lord/slate/wiki/Markdown-Syntax).
