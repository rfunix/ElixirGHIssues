# Issues

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `issues` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:issues, "~> 0.1.0"}]
    end
    ```

  2. Ensure `issues` is started before your application:

    ```elixir
    def application do
      [applications: [:issues]]
    end
    ```
    
## Usage

```bash
./issues -h
usage: issues <user> <project> [ count | 4 ]
```

## Running

```bash
./issues elixir-lang elixir 10

22:06:29.013 [info]  Fetching user elixir-lang's project elixir

22:06:32.373 [info]  Successful response
numb | created_at           | title
-----+----------------------+------------------------------------------------------------
2469 | 2014-07-01T08:36:51Z | Provide defguard
3011 | 2015-01-11T17:06:06Z | Discuss if we should support monitoring callbacks in agents
3254 | 2015-04-07T22:12:11Z | Do not allow tuple.foo calls anymore
4082 | 2015-12-17T08:20:09Z | Add make compiler
4171 | 2016-01-07T20:44:36Z | Suggesting the correct patterns to match
4617 | 2016-05-13T06:51:53Z | Support Erlang 19 new features
4829 | 2016-06-19T06:50:12Z | `mix deps.get` gets confused with "> 0.0.0"
4862 | 2016-06-23T14:37:01Z | Revisit usage of diff with =~ in assertions
4864 | 2016-06-23T18:03:35Z | Update Elixir's Unicode support to Unicode 9.0
4913 | 2016-06-30T14:30:18Z | Force disable warnings_as_errors for dependencies
```

