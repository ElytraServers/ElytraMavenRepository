# Elytra Maven Repository

Hey! This is a maven repository for the dependencies of our mods.

## Use

Add this to your `build.gradle.kts`.

```kts
repositories {
	// ...
	maven("https://github.com/ElytraServers/ElytraMavenRepository/raw/master/")
}
```

or `build.gradle`

```gradle
repositories {
	// ...
	maven {
	    url "https://github.com/ElytraServers/ElytraMavenRepository/raw/master/"
	}
}
```