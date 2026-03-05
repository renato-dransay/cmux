# Staging Launch

Build and launch cmux as "cmux STAGING" — an isolated Release build that runs side-by-side with the production cmux app (separate bundle ID, socket, and identity).

## Steps

1. Run the staging build and launch script:
   ```bash
   cd /Users/renatobeltrao/Projects/cmux && ./scripts/reloads.sh
   ```

2. Wait for the build to complete. Report any build errors to the user.

3. On success, confirm the staging app is running:
   ```bash
   pgrep -fl "cmux STAGING" || echo "Staging app not detected"
   ```

4. Report the result — whether the build succeeded and the staging app launched.
