FROM meteorhacks/meteord:base
MAINTAINER MeteorHacks Pvt Ltd.

ENV METEOR_ALLOW_SUPERUSER 1
ONBUILD COPY ./ /app
ONBUILD RUN bash $METEORD_DIR/on_build.sh
