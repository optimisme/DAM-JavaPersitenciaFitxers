# Exemple de guardar dades a arxius #

En aquest projecte hi ha diversos exemples de com guardar dades en Java, cap a arxius de text, binaris, XML, CSV i objectes serialitzats

### Instruccions ###

Primer posar en funcionament el servidor

Després executar el client i comprovar com els càlculs obtenen resultat des del servidor

### Compilació i funcionament ###

A Linux i OSX:

```
./build.sh
```

A Windows Powershell:

```
.\build.ps1
```

Or, from Visual Studio Code:

```
"Terminal > Run task > Compile for UNIX"
"Terminal > Run task > Compile for PowerShell"
```

Recommended study order:

```
    GestioArxius.java

    EscripturaArxiuWriter.java
    LecturaArxiuScanner.java

    EscripturaArxiuList.java
    LecturaArxiuList.java

    EscripturaDadesPrimitives.java
    LecturaDadesPrimitives.java

    EscripturaObjectes.java
    LecturaObjectes.java

    EscripturaLlistes.java
    LecturaLlistes.java

    GestioCSV.java
    GestioXML.java
```