# Usage
> You need {N} CLI 3.4.0+.

Run without webpack:
```
tns run android|ios
```

Run with webpack:
```
tns run android|ios --bundle
```

Run with optimization flags:
```
tns run android|ios --bundle --env.aot --env.uglify --env.snapshot
```
