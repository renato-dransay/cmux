# Build and Install

Build a Release version of cmux and launch it, replacing any currently running cmux instance.

## Steps

1. Run the release build and launch script:
   ```bash
   cd /Users/renatobeltrao/Projects/cmux && ./scripts/reloadp.sh
   ```

2. Wait for the build to complete. Report any build errors to the user.

3. On success, confirm the app is running:
   ```bash
   pgrep -fl "cmux.app/Contents/MacOS/cmux" || echo "App not detected"
   ```

4. Report the result — whether the build succeeded and the app launched.
