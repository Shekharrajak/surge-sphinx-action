FROM alpine:3.7

LABEL "com.github.actions.name"="Surge deploy - sphinx application"
LABEL "com.github.actions.description"="Build your sphinx site and deploy in customized surge URL"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="http://github.com/shekharrajak/surge-sphinx-action"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Shekhar Prasad Rajak <shekharrajak@live.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
