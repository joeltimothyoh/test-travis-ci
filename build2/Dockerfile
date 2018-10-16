ARG IMAGE
From $IMAGE


RUN steamcmd.sh +login anonymous +force_install_dir /app +app_update 222860 validate +quit

ENV LD_LIBRARY_PATH .:bin:$LD_LIBRARY_PATH