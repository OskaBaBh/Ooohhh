FROM quay.io/naveeddogar/kingmd
RUN git clone https://github.com/vajirabot1/KING-VAJIRA-MD /root/vajirabot1
WORKDIR /root/vajirabot1/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
