FROM oven/bun:latest

WORKDIR /app
COPY package.json bun.lockb ./
RUN bun install --production
COPY . .

CMD ["bun", "run", "start"]