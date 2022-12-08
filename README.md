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
    implementation("com.google.accompanist:accompanist-placeholder-material:0.28.0")

    //Coil
    implementation("io.coil-kt:coil:2.2.2")
    implementation("io.coil-kt:coil-compose:2.2.2")
    implementation("io.coil-kt:coil-gif:2.2.2")
    implementation("io.coil-kt:coil-svg:2.2.2")
```

## Find this repository useful? :heart:
Support it by joining __[stargazers](https://github.com/t8rin/coilwrapper/stargazers)__ for this repository. :star: <br>
And __[follow](https://github.com/t8rin)__ me for my next creations! 🤩

# License
```xml
Designed and developed by 2022 T8RIN

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

