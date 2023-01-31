# Bapti Imagine

A minimal client for Bapti Imagine hosted inference API on Replicate. This package allows you to easily access Midjourney/Openjourney from NodeJS.

> Bapti Imagine is an open source Stable Diffusion fine tuned model on Bapti Imagine images, by [PromptHero](https://prompthero.com/). Predictions run on Nvidia A100 GPU hardware.

<img src='https://replicate.delivery/pbxt/AKYKbvhgl06rPdPdFq6nJYMJpzTsQOEQiiJWh8x5ncqNTHAE/out-0.png'>


## Installation

```js
const package = require('bapti-funkopop')
npm i bapti-imagine
```


## API

The API is super simple; just enter your prompt and `await` for one or more image URLs. One image is returned by default.

```js
await funkodiffusion('a painting of a ginger cat.')
```

Pass in additional parameters as a second argument.

```js
await funkodiffusion('a painting of a ginger cat.', { width: 1024 })
```

A complete list of supported parameters can be found [here](https://replicate.com/prompthero/funko-diffusion/api#inputs).


## Examples

> portrait of female elf, intricate, elegant, highly detailed, digital painting, artstation, concept art, smooth, sharp focus, illustration, art by artgerm and greg rutkowski and alphonse mucha, 8k.

<img src='https://replicate.delivery/pbxt/8x94TXrayZ4jK1nE39E1mJrLUtiV3b4k84wHzGa0MWLVSHAE/out-0.png'>

> whimsical fantasy elegant rose floral botany maximalism with a wave of flowers garden flowing flowers floating in misty soft pink, aqua, soft apricot, smoke fractal, moody and big scale realistic flowers, octane render, by josephine wall art, isabelle menin, Jean, amy brown.

<img src='https://replicate.delivery/pbxt/eNlIp5fWsGt7oki3JUQK4HyufDFvJqMIlbOD1DLos9Dfw0BAB/out-0.png'>


## Future

- Improve API interfaces (i.e. return richer objects than just arrays of URLs).
- Merge/become part of Replicated/ReplicateJS. 
