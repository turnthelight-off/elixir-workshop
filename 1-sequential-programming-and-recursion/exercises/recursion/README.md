# Recursion

## Implementation
<pre>
mix deps.get
iex -S mix

current error:
mix -S iex
** (Mix) Cannot implicitly pass flags to default Mix task, please invoke instead "mix run"
</pre>
## Example of implementation taken from test file:
<pre>
no example test currently written.
Recursion.b_not(true)
Recursion.b_not(false)
Recursion.b_not(true, "thing")
//not sure: ... Recursion.b_or(_true, true)
Recursion.b_and(true,true)
Recursion.b_and(false, false)

Recursion.print_all
Recursion.print_all

Recursion.count
Recursion.count

Recursion.remove_dups
Recursion.remove_dups
Recursion.remove_dups
Recursion.remove_dups

Recustion.quicksort
Recustion.quicksort

</pre>

## How to run the test suite
<pre>
mix test
</pre>
# How to find module and functions when using iex
<pre>
Learn module name by first capital letter of module and tab...

Then when you type the module
tab will tell function names.
</pre>

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `recursion` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:recursion, "~> 0.1.0"}]
    end
    ```

  2. Ensure `recursion` is started before your application:

    ```elixir
    def application do
      [applications: [:recursion]]
    end
    ```

