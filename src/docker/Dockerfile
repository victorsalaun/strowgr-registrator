FROM busybox

LABEL application.name "StrowgrRegistrator"
LABEL application.desc "Strowgr docker registrator"

COPY ${project.build.finalNameWithExt} /app
ENTRYPOINT [ "/app" ]