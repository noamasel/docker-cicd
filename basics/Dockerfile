FROM node:4.6
WORKDIR /app
ADD . /app
RUN ls -ltrh
RUN echo " this is a test "
RUN cd basic
RUN npm install
EXPOSE 3000
CMD npm start
