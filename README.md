# Fish Greeting Messages

This script displays a random greeting message every time you open a new terminal.

## Installation

1. **Install the Fish Shell:**

   If you don't have the Fish shell installed, you can install it using one of the following methods:

   * **macOS (using Homebrew):**
     ```bash
     brew install fish
     ```

   * **Ubuntu/Debian:**
     ```bash
     sudo apt-get update
     sudo apt-get install fish
     ```

   * **Other Linux distributions:**
     You can find instructions for your specific distribution in the [official Fish documentation](https://fishshell.com/docs/current/index.html#installation).

2. **Place the Script:**

   Move the `greeting.fish` file to the `~/.config/fish/functions` directory. If the `functions` directory doesn't exist, you can create it:

   ```bash
   mkdir -p ~/.config/fish/functions
   mv greeting.fish ~/.config/fish/functions/
   ```

3. **Source the Script:**

   Add the following line to your `~/.config/fish/config.fish` file to run the script every time you open a new terminal:

   ```fish
   greeting
   ```

## Usage

Once you've installed the script, simply open a new terminal, and you'll see a random greeting message.

### Configuration

You can customize the type of greeting message by setting the `GREETING_TYPE` environment variable in your `~/.config/fish/config.fish` file.

*   To display only book quotes, add the following line:
    ```fish
    set -x GREETING_TYPE "book"
    ```

*   To display only song refrains, add the following line:
    ```fish
    set -x GREETING_TYPE "song"
    ```

If the `GREETING_TYPE` variable is not set, a random message from all available quotes and refrains will be displayed.
