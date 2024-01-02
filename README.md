# Elixir Identicon

_This project is mostly for learning purposes._

[Identicon](https://en.wikipedia.org/wiki/Identicon) generator built with Elixir. Loosely inspired by the code from this [Udemy course](https://www.udemy.com/course/the-complete-elixir-and-phoenix-bootcamp-and-tutorial).

## Install

- Make sure you have [Elixir](https://elixir-lang.org/) installed. On a Mac you can use `brew install elixir`
- Run `mix deps.get`

## Usage

You can run the program within the REPL interactive console:

```
$ iex -S mix run
iex(1)> Identicon.main("test")
:ok
```

## Development

- compile dependencies `mix deps.compile`
- run the tests with `mix test`
- format code using `mix format`
