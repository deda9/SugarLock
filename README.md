# SugarLock
In short it replaces this 
```Swift 
let locker = NSLock()
locker.lock()
//do your work
locker.unlock()
```

with 
```Swift 
let locker = NSLock()
locker.with {
  //Do your work
}
```
