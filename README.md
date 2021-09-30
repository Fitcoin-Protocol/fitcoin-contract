# Fitcoin Protocol - Contract v1

## General

Any pull requests will be reviewed for the release of a hypothetical Fitcoin Protocol v2, although that will be very unlikely to happen.
The contract describes a behavior that defines the support network such as that of Binance Smart Chain, despite this, we are sure to be able to complete the integration with our Network, without necessarily changing the code, and consequently release a new contract.

This repository will no longer receive changes after the contract is released, outside of the documentation.

# Fitcoin Protocol
## _A new whole EcoSystem_

We will once again bring back the long-neglected anonymity due to regulations aimed at repressing our world.
And we will do it by improving everyone's life.

- Earn money while you work out and burn calories
- Interact with the Community for an exchange of content based on our Network 
- Passive income based on each trade made by Community users.

## Features

- Fitcoin Network
- Mobile App
- No more expensive fees
- Instant transfer
- Privacy
- Multiplatform support

Each feature has its own purpose, and it has been designed to solve a problem in a simple way and for everyone. 
This is the quote that made us think of having to introduce a novelty in the crypto world, which essentially introduces features already seen, but now forgotten or deprecated, in a more optimized and functional way.

> I feel I don't feel like using cryptocurrencies as consistently as before.
> Basically we are point to point, just like before the invention of Bitcoin. 
> What is the point of using a payment system based on anonymity,
> exposing all the information of those who interact with this system, 
> and passing it off as anonymous and safe as well? 

Unfortunately all of this is true, and we still do not explain the reason for these choices made to monitor what should not be monitored.

## We Love Open Source ❤️

We're gonna mention some Open Source projects we currently use for our Development:

- [Telegram.Bot](https://github.com/TelegramBots/Telegram.Bot) - .NET Client for Telegram Bot API
- [jQuery] - JavaScript library
- [Node.js](https://nodejs.org/) - JavaScript runtime environment 
- [Ace Editor] - Web-Based text editor
- [AngularJS] - HTML enhanced for web apps
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML to Markdown converter


## Development

Do you want to be a contributer? Awesome!<br>
Unfortunately it is not possible to change the code of a contract, but you can always contribute
to the documentation and future repositories for our SDKs.

## Docker

We're gonna make a test-net soon for our Network, and it is very easy to install and deploy in a Docker container.
Yes, you can use Docker to deploy your projects on Fitcoin Network.
You can even help the Community with verified plugins to enhance the user's experience.

Use the Dockerfile to build the image.

```sh
cd fitcoin-network-tn
docker build -t <youruser>/fitcoin-network-tn:${package.json.version} .
```

This will create the test-net image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Fitcoin Network.

Once done, run the Docker image and map the port to whatever you wish on
your host:

```sh
docker run -d -p 8000:8080 --restart=always --name=fitcoin-network-tn <youruser>/fitcoin-network-tn:${package.json.version}
```

> Note: In this example, we simply map port 8000 of the host to port 8080 of the Docker (or whatever port was exposed in the Dockerfile).

Verify the deployment by navigating to your server address:

```sh
127.0.0.1:8000
```

## License

MIT

Copyright (c) 2021 Fitcoin-Protocol

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

   [Ace Editor]: <http://ace.ajax.org>
   [jQuery]: <http://jquery.com>
   [AngularJS]: <http://angularjs.org>
