# next.js development container
FROM node:14.17.0-alpine3.13

# Install git
RUN apk add --no-cache git

COPY . /workspace
WORKDIR /workspace

# Install dependencies
RUN yarn install

# Start the development server
CMD ["yarn", "dev"]