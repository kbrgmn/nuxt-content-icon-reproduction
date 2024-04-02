# Nuxt Content freezes up browser with Nuxt Icon - reproduction

When dev mode with `bun dev` is visited on the page, it completely freezes up (both Firefox and Chrome), 
with no text being selectable, developer console not opening if it hasn't already been opened, and this warning
is printed hundreds of times in the console:
```
Avoid app logic that relies on enumerating keys on a component instance.
The keys will be empty in production mode to avoid performance overhead.
```

This issue does not occur when a production build is being done with `bun run build`.
