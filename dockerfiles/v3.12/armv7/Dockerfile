FROM arm32v7/alpine:3.12

COPY overlay/ /

RUN ["setup.sh", "v3.12" ]

USER buildozer

ENTRYPOINT [ "/bin/sh" ]

