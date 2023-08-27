FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/praveennimsaragiz/PRAVEEN-1.0.0 /root/PRAVEEN-1.0.0
WORKDIR /root/PRAVEEN-1.0.0/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
 
