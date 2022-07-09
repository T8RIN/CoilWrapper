# CoilWrapper
Jetpack compose coil wrapper with additional functional like zooming and shimmering image while loading

Copy Picture.kt file to your repository and you are ready to engage!

```kotlin
//Usage example
Picture(
  model = "https://avatars.githubusercontent.com/u/52178347?v=4",
  modifier = Modifier.size(100.dp),
  /*your other params*/
)
```

## Note
Also remember to add this dependencies to local build.gradle folder

```kotlin
//Accompanist
implementation("com.google.accompanist:accompanist-placeholder-material:0.24.13-rc")

//Coil
implementation("io.coil-kt:coil:2.1.0")
implementation("io.coil-kt:coil-compose:2.1.0")
implementation("io.coil-kt:coil-gif:2.1.0")
implementation("io.coil-kt:coil-svg:2.1.0")
```
