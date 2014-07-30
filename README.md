Repot
=====

Repot is a simple `git-repo` tool to record the revisions of each projects
of a repo manifest.


Usage
-----

To dump the SHA1 of each projects checked out by the `git-repo` tool, run
the following command to create a new manifest:

    $ repot

To reset the fetch URL:

    $ repot --remote-set-url [name]:[url]
    $ repot --remote-set-url aosp:https://android.googlesource.com/

To specify the source tree and output:

    $ repot -o [output_name] [source tree]
