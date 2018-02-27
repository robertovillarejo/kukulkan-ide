# Theia & Xtext Example

A Theia Application with an Xtext-based Language Server extension for the Kukulkan DSL.

## Build and Run

Build the language server
```
  cd mx.infotec.dads.kukulkan.parent &&
  ./gradlew shadowJar &&
  cd ..
```

Build and start Theia
```
   yarn install &&
   cd app &&
   yarn start
```

References:  
[Theia & Xtext Example](https://github.com/theia-ide/theia-xtext)
