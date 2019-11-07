ARG REDMINE_VERSION=latest
FROM redmine:${REDMINE_VERSION}

COPY configuration.yml /usr/src/redmine/config/

EXPOSE 3000
CMD ["rails", "server", "-b", "0.0.0.0"]