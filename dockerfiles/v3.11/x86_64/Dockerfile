FROM amd64/alpine:3.11

COPY overlay/ /

RUN ["setup.sh", "v3.11" ]

USER buildozer

ENTRYPOINT [ "/bin/sh" ]

