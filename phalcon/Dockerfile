FROM ssuhss/phalcon:buscape-v1
MAINTAINER Michel Silva <michel_silva_04@hotmail.com>

ENTRYPOINT nginx && service php5-fpm start && /bin/bash
RUN rm -Rf /etc/nginx/sites-enabled/default
RUN rm -Rf /etc/nginx/sites-available/default
CMD ["true"]

EXPOSE 80
