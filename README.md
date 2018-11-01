Readme:

1. What information is being communicated?
2. How is this information structured?
3. Do you notice any patterns?

Title and description:

Ledbetter

Ledbetter is a simple script for gathering Nagios problem statistics and submitting them to Graphite. It focuses on summary (overall, service group and hostgroup) statistics. It writes them to the nagios.problems metrics namespace within Graphite.


Installation

clone the Github repository and use Bundler to install the gem dependencies,

$ git clone https://github.com/github/ledbetter.git
$ cd ledbetter
$ bundle install

Usage

Ledbetter requires a number of environment variables for runtime configuration. The following example demonstrates how to run it manually from the command line, but you would typically run it as a cron job.

$ export NAGIOS_URL=http://nagios.foo.com/cgi-bin/nagios3
$ export NAGIOS_USER=foo
$ export NAGIOS_PASS=bar
$ export CARBON_URL=carbon://localhost:2003
$ bundle exec ruby ledbetter.rb


1. What steps need to be taken?
2. What should the user already have installed or configured?
3. What might they have a hard time understanding right away?

Write Readme in mark down


Example:

# My Fabulous Recipe

This recipe for **cereal and milk** has been passed down my family for months.

### Ingredients

* Cereal (you can find some cool cereals [here](www.example.com/Coolcereals))

### Directions

If I were writing these out as _code_, it might look something like this:

```
if bowl is empty:
    add cereal
if bowl has only cereal in it:
    add milk
```
