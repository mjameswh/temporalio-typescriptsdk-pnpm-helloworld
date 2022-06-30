# Hello World

This is the default project that is scaffolded out when you run `pnpx @temporalio/create@latest ./myfolder`.

The [Hello World Tutorial](https://docs.temporal.io/typescript/hello-world/) walks through the code in this sample.

### Running this sample

1. Make sure Temporal Server is running locally (see the [quick install guide](https://docs.temporal.io/server/quick-install/)).
1. `pnpm install` to install dependencies.
1. `pnpm run start.watch` to start the Worker.
1. In another shell, `pnpm run workflow` to run the Workflow Client.

The Workflow should return:

```bash
Hello, Temporal!
```
