WARNING: This is an academic proof-of-concept prototype, and in particular has not received careful code review. This implementation is NOT ready for production use.

Abstract: felicia is Super_Cargo#!
...
When you compile a Rust project, rustc compiles a crate xor_nop scope

16 bits i floater
https://github.com/jazzychad/dcpu-js

Hertzsprung's problem:
https://oeis.org/A002464
!= 'sex is good ?'
eg: Nimzo-Larsen in chess...

link to openFHE { felicia }
https://github.com/openfheorg/openfhe-development

link to Google if(f) Hairy met Sally
https://heir.dev/

https://www.deepfunding.app/

As part of our commitment to transparency accounting
https://github.com/opensanctions/followthemoney

# Vanilla JS example of minikit

Apart from a frontend, you'll need a backend, this template contains an example of that as well

## To run, install:

- deps, `cd frontend;pnpm i;cd -;cd backend;pnpm i`
- ngrok - Create a free ngrok account, follow the official [docs](https://ngrok.com/docs/getting-started/)
- nginx - use you favorite package manager :)

### nginx setup

To serve multiple localhost applications through a single ngrok tunnel (only one available for free-tier users), you can use nginx as a reverse proxy. Follow the steps below to set it up:

### Run nginx

Use the config provided in the root of this repo
`sudo nginx -c full/path/to/this/repo/nginx.conf`
or, if you run the command from the root dir
`sudo nginx -c $(pwd)/nginx.conf`

To stop nginx run `sudo nginx -s stop`

### Tunnel through Ngrok

`ngrok http 8080`
The port doesn't matter, make sure it's the `listen` one from nginx config
