<center>
<b>JavaDoc Only Repo</b>
</center>

# [Visit JavaDoc here !](https://catalyst105.github.io/FactionsUUID-javadoc/)

This is a forked repository of the original [FactionsUUID](https://github.com/FactionsU/UID) only for the purpose of creating and uploading FactionsUUID's javaDoc

> ## 🚨 4.3.1 javaDoc errors 🚨
> The gradle repository of Graves (from Ranull) don't authorize download. So I removed all the Graves reference for this upload.

## How to create javaDoc yourself

*(For windows people, use ./gradlew.bat instead of ./gradlew)*

1. Clone the original repo : `git clone https://github.com/FactionsU/UID`
2. Remove the `./exemple-plugin` causing errors in the javadoc generations.
3. Check errors with gradle : `./gradlew(.bat) check`
4. `./gradlew(.bat) javaDoc`
5. Get the docs in `./bukkit/build/docs/javadoc/index.html`
