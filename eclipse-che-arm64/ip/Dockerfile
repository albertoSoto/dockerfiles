# Copyright (c) 2016 Codenvy, S.A.
# All rights reserved. This program and the accompanying materials
# are made available under the terms of the Eclipse Public License v1.0
# which accompanies this distribution, and is available at
# http://www.eclipse.org/legal/epl-v10.html
#
# build:
#   docker build -t eclipse/che-ip .
#
# use:
#    docker run --rm --net=host eclipse/che-ip

FROM arm64v8/alpine:3.5

COPY /src/ /ip/
ENTRYPOINT ["/ip/entrypoint.sh"]
