FROM    mhart/alpine-node 
# Get The Code 
COPY . /src
# Install app dependencies
RUN cd /src; npm install
EXPOSE  8080
CMD ["node", "/src/index.js"]

