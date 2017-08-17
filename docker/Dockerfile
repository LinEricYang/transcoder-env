FROM mss:r2.ubuntu-xenial

COPY transcoder_daemon.sh /usr/local/bin/
COPY sample_multi_transcode /usr/local/bin/

VOLUME /mnt/shared

ENTRYPOINT ["transcoder_daemon.sh"]
