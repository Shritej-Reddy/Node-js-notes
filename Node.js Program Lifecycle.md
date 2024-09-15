
- node app.js -> start script -> parse code, register variables & function -> Event Loop(keeps on running as long as there are event listeners registered)

- Entire node process uses one thread.
- By leveraging the OS there is some degree of multi-threading that's being done.
- process.exit() -> exits out of the process