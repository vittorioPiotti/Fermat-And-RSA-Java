# Fermat-And-RSA
Soluzione software in Java che genera e salva su file i numeri primi con algoritmo di Fermat e algoritmo di crittografia RSA


> [!TIP]
> Software responsive con schermata Small e Large

> [!TIP]
> Corretto funzionamento garantito per algoritmo di Fermat e RSA

## Javadoc

Link al javadoc: [(link)](https://vittoriopiotti.altervista.org/FermatAndRsaJava/index.html)


## Albero di Path

```bash
$ tree
.
├──lib
│   └── flatlaf-3.2.5.jar
└──src
    └── org
        └── app
            ├── applications
            │   ├── encryption
            │   │   ├── ReadFile.java
            │   │   └── TestEncryption.java
            │   └── primality
            │       ├── SavePrimality.java
            │       └── TestPrimality.java
            ├── windows
            │   ├── dependencies
            │   │   ├── components
            │   │   │   ├── encryption
            │   │   │   │   ├── dialogs
            │   │   │   │   │   ├── WinErrorInEncryption.java
            │   │   │   │   │   └── WinErrorOutEncryption.java
            │   │   │   │   ├── panels
            │   │   │   │   │   ├── WinInEncryption.java
            │   │   │   │   │   ├── WinOutEncryption.java
            │   │   │   │   │   └── WinSaveEncryption.java
            │   │   │   │   └── WinEncryption.java
            │   │   │   ├── primality
            │   │   │   │   ├── dialogs
            │   │   │   │   │   ├── WinErrorInPrimality.java
            │   │   │   │   │   └── WinErrorOutPrimality.java
            │   │   │   │   ├── panels
            │   │   │   │   │   ├── WinInPrimality.java
            │   │   │   │   │   ├── WinOutPrimality.java
            │   │   │   │   │   └── WinSavePrimality.java
            │   │   │   │   └── WinPrimality.java
            │   │   │   └── WinHome.java
            │   │   └── managers
            │   │       ├── WinManagerEncryption.java
            │   │       └── WinManagerPrimality.java
            │   └── WinManager.java
            ├── App.java
            └── Main.java

```

## Licenze

| Componente          | Versione         | Copyright                                      | Licenza                                                                                            |
|---------------------|------------------|------------------------------------------------|----------------------------------------------------------------------------------------------------|
| Fermat And RSA     | v1.0.0           | 2024 Vittorio Piotti                           | [GPL-3.0 License](https://github.com/vittorioPiotti/Fermat-And-RSA/blob/main/LICENSE.md)       |
| FlatLaf             | v3.2.5           | 2024 JFormDesigner GmbH                        | [Apache License 2.0](https://github.com/JFormDesigner/FlatLaf/blob/main/LICENSE)                   |
