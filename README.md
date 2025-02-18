# Expo CLI Development Server Crash

This repository demonstrates a bug where the Expo CLI development server crashes without providing any error messages. The app functions correctly initially but then the server terminates abruptly.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Observe the development server. After some time it will unexpectedly crash.

## Potential Causes

* Memory leak in Expo's internal processes.
* Unexpected interaction between Expo and other system components.
* Race condition in Expo's event handling.
* Bugs in dependencies.

## Workaround

The provided solution demonstrates one possible workaround. It is still crucial to report this issue to the Expo team for proper investigation.