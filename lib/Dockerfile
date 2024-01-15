FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/shamika28/MONSTER-MD /root/shamika28
WORKDIR /root/shamika28/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
