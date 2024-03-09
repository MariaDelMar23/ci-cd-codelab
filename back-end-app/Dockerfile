FROM nginx:alpine
LABEL org.opencontainers.image.source ci-cd-codelab
COPY dist /usr/share/nginx/html
EXPOSE 81
CMD ["nginx", "-g", "daemon off;"]
