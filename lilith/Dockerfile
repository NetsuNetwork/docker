FROM elixir:latest-alpine

COPY lilith/* .

RUN mix deps.get && mix deps.compile

EXPOSE 5489/tcp

CMD ["mix", "run", "--no-halt"]
