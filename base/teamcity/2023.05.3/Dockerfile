FROM jetbrains/teamcity-server:2023.11.5

LABEL maintainer="phithon <root@leavesongs.com>"

COPY --chmod=0755 entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
CMD ["/run-services.sh"]
