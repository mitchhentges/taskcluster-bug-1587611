# This Source Code Form is subject to the terms of the Mozilla Public
# License, v. 2.0. If a copy of the MPL was not distributed with this
# file, You can obtain one at http://mozilla.org/MPL/2.0/.

# We use this specific version because our decision task also runs on this one.
# We also use that same version in decisionlib.py
FROM ubuntu:bionic-20180821

MAINTAINER Mitchell Hentges "mhentges@mozilla.com"

RUN dd if=/dev/zero of=target-file bs=1M count=9048

VOLUME /builds/worker/checkouts
VOLUME /builds/worker/.cache
