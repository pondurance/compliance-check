# compliance-check
The compliance checker is a program used to gather details about a systems compliance posture. 

Dependencies
============

This script requires the command `jq` to run, ensure its installed before running the script. The script will check for dependencies automatically and will prompt
you to accept or deny the install during run time. 

Installation
============

* Download and distribute locally
Navigate to the [releases](https://github.com/pondurance/compliance-check/releases) page and locate the most recent release. 

Unpack the archive you downloaded on the host(s) you want to run the check on. 

Execute the script
chmod +x compliance-check

Run the script
./compliance-check > /tmp/compliance-check.json

* Running with a 1-liner
curl -sL https://raw.githubusercontent.com/pondurance/compliance-check/master/compliance-check > /tmp/compliance-check.json

