FROM node:alpine
WORKDIR /app
COPY ./dist ./dist
RUN npm install -g http-server
EXPOSE 5173
CMD ["http-server", "dist", "-p", "5173"]