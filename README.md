# ExIcal [![Package Version](https://img.shields.io/hexpm/v/ex_ical.svg)](https://hex.pm/packages/ex_ical) [![Build Status](https://travis-ci.org/fazibear/ex_ical.svg?branch=master)](https://travis-ci.org/fazibear/ex_ical)

Not ready yet!

ICalendar parser for [Elixir](http://elixir-lang.org).

####### I AM A CAT ! ######

## Installation

Add ex_ical to your list of dependencies in `mix.exs`:

```elixir
  def deps do
    [{:ex_ical, "~> 0.0.1"}]
  end
```

## Usage

```elixir
  HTTPotion.get("url-for-icalendar").body
    |> ExIcal.parse
    |> ExIcal.by_range(Date.now, Date.now |> Date.shift(days: 7))
```
