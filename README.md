# Testing actions
Collection of material for testing GitHub Actions.

## Using nektos/act
1. [Install act](https://github.com/stebje-actions-packages/testing-actions.git)
2. Clone this repo
3. Navigate to the repo root
4. To run a workflow, e.g. `basic.yml`, trigger the `push` event by running
    ```sh
    $ act push
    
    [Basic workflow/printStuff] 🚀  Start image=node:12.6-buster-slim
    [Basic workflow/printStuff]   🐳  docker run image=node:12.6-buster-slim entrypoint=["/usr/bin/tail" "-f" "/dev/null"] cmd=[]
    [Basic workflow/printStuff] ⭐  Run Print stuff
    | Success
    [Basic workflow/printStuff]   ✅  Success - Print stuff
    ```
