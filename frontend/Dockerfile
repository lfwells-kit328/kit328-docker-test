FROM node:20-slim

RUN npm install -g serve
WORKDIR /app

# Copy the public folder from the current directory (frontend/)
COPY public ./public

EXPOSE 3000
CMD ["serve", "-s", "public", "-l", "3000"]