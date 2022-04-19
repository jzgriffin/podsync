# Podsync

Podsync is a podcast manager and download client.  You can subscribe to
podcasts using its CLI.  Podsync will monitor the feeds of subscribed
podcasts and download new episodes.  You can optionally download old
episodes when subscribing to a new podcast.

# Dependencies

Podsync is written in Haskell and can be built using either
[Stack](https://haskellstack.org) or [Cabal](https://haskell.org/cabal).
These instructions show how to install using Stack.  You can install
Stack with [GHCup](https://haskell.org/ghcup).

# Downloading

Clone the source from GitHub:
```sh
git clone https://github.com/nokurn/podsync
cd podsync
```

# Installing

Build and install using Stack:
```sh
stack setup
stack build
stack install
```

# Using

Podsync can be used via the `podsync` command after installation.

# Licensing

This project is made available under the terms of the permissive
MIT free software license:

> Copyright 2022 Jeremiah Griffin
>
> Permission is hereby granted, free of charge, to any person obtaining
> a copy of this software and associated documentation files (the
> "Software"), to deal in the Software without restriction, including
> without limitation the rights to use, copy, modify, merge, publish,
> distribute, sublicense, and/or sell copies of the Software, and to
> permit persons to whom the Software is furnished to do so, subject to
> the following conditions:
>
> The above copyright notice and this permission notice shall be
> included in all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
> EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
> MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
> IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
> CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
> TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
> SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
