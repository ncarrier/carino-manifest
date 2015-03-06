# Repo manifests for the carino project

## Description

This project contains the manifests for the carino, to be used with the repo
command. For more information on repo, please refer to the
[aosp documentation][aosp-repo].

## Naming conventions

default.xml is the default manifest for all the carino project, making all the
repositories point to the HEAD of the default branches, *master* for most of the
projects.  
The manifest for building a given vehicle in named *VEHICLE_NAME.xml* and to
retrieve a particular version for a vehicule, please checkout the
*VEHICLE_NAME-VERSION-tag* tag.

## License

    This file is part of the Carino project documentation.
    Copyright (C) 2015
      Nicolas CARRIER <carrier dot nicolas0 at gmail dot com>
    See the file doc/README.md for copying conditions

[aosp-repo]: https://source.android.com/source/downloading.html#installing-repo
