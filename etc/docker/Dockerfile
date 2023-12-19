FROM node:19.9.0

WORKDIR /directus
# Copy project
COPY . .

# Install dependencies
RUN npm i

EXPOSE 8055

CMD [ "npx", "directus", "start"]