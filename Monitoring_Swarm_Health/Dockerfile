FROM nginx:alpine
RUN apk add --no-cache curl
RUN echo "Healtcheck Demo" > /usr/share/nginx/html/index.html
HEALTHCHECK --interval=5s --timeout=5s CMD curl --fail -A "healthcheck-routine" http://localhost:80/ || exit 1


