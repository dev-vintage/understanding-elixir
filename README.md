# ![GitHub](./assets/github.png) Understanding Elixir ![Elixir](./assets/elixir.png)

<hr>

## What is Elixir?

Elixir is a functional , concurrent , general-purpose programming language that runs on the Erlang virtual machine (BEAM). Elixir compiles on top of Erlang to provide distributed, smooth, fault-tolerant, non-stop real-time applications, but also extends it to support metaprogramming with macros and polymorphism via protocols.

<hr>

## Who created the Elixir?

![José Valim](./assets/valim.png)

José Valim is the Brazilian creator of the programming language Elixir, an R&D project by Plataformatec, a subsidiary of nubank . [ 4 ] Its goals were to allow greater extensibility and productivity in the Erlang VM, while maintaining compatibility with Erlang's tools and ecosystem. [ 5 ]

On July 12, 2018, Honeypot released a mini-documentary on the Elixir language.

<hr>

## Examples

Classic example of Hello world :

```ex
iex> IO.puts "Hello World!"
```

Modules

```ex
defmodule  Fun  do 
  def  fib ( 0 ),  do :  0 
  def  fib ( 1 ),  do :  1 
  def  fib ( n )  do 
    fib ( n - 2 )  +  fib ( n - 1 ) 
  end 
end
```



