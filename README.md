# compliance-check
The compliance checker is a program used to gather details about a systems compliance posture. 

Dependencies
============

This script requires the command `jq` to run, ensure its installed before running the script. The script will check for dependencies automatically and will prompt
you to accept or deny the install during run time. 

Installation from release (self-distribute)
===========================================

**Download and distribute locally**

1. Navigate to the [releases](https://github.com/pondurance/compliance-check/releases) page and locate the most recent release. 

2. Unpack the archive you downloaded on the host(s) you want to run the check on. 

3. Execute the script
`chmod +x compliance-check`

4. Run the script
`./compliance-check > /tmp/compliance-check.json`

Running with a `insecure 1-liner`
================================

:warning:
:exclamation: This is the easiest method of running the script but please be aware of the caveats of running 1-liner scripts from the internet.

1. Running with a 1-liner
`curl -sL https://raw.githubusercontent.com/pondurance/compliance-check/master/compliance-check | bash > /tmp/compliance-check.json`
