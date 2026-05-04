```kotlin
single<AndroidDeveloper> {
    AndroidDeveloper(
        name = "Muhammad Ali",
        role = "Mid-Level Android Developer",
        experience = "2 years",
        ui = listOf(
            "Declarative UI: Jetpack Compose",
            "Custom Shaders & Render Effects",
            "Animations & Motion",
            "Adaptive layouts",
        ),
        architecture = listOf(
            "Clean Architecture",
            "Architectural Patterns: MVVM, MVI (UDF)",
            "UI Compose Performance Optimization + In-Memory Caching Strategies",
        ),
        async = listOf(
            "Concurrency & Multithreading: Coroutines",
            "Reactive Programming & Data Streaming: Flows",
        ),
        testing = listOf(
            "Unit Testing",
            "Mock Build Variant (fake data layer for UI dev)",
            "Feature-Flag Gated Environments",
        ),
        gradle = listOf(
            "Multi-Module Project Structure",
            "Centralised deps, plugins & task automation",
            "Build Variants & Product Flavors",
        ),
        multiplatform = listOf(
            "KMP: Shared Logic & UI (Android/iOS)",
        ),
    )
}
```
