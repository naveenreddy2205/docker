# base file

FROM node:14.15.1-alpine3.10

# Create Directory

RUN mkdir /code

# Make directory as working directory

WORKDIR /code

#copy files to directory

COPY . /code

# Install Npm package

RUN npm install

# block port

EXPOSE 8080

# run npm start

CMD ["npm","start"]  
