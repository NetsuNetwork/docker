FROM elixir:latest-alpine

WORKDIR /app/lilith

COPY lilith/* .

RUN mix deps.get && mix deps.compile

EXPOSE 5489/tcp

CMD ["mix", "run", "--no-halt"]
