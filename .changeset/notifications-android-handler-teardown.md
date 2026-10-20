---
'expo-notifications': patch
---

[Android] Fix a `ConcurrentModificationException` crash when the React host reloads or tears down while two or more foreground notifications wait for the JavaScript notification handler.
