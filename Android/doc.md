# CMD Line Tools

  - die Zip-Datei und die Ordner sind nicht mit im Git gemerged
  - CMD >> sudo wget https://dl.google.com/android/repository/commandlinetools-linux-11076708_latest.zip
  - Download link : https://developer.android.com/studio?hl=de


```bash
   /run/me/y/6/h/y/Dok/W/VS-Code/App-C#/Android/SDK    main ?1  tree                                                                               ✔ 
.
├── cmdline-tools
│   ├── bin
│   │   ├── apkanalyzer
│   │   ├── avdmanager
│   │   ├── lint
│   │   ├── profgen
│   │   ├── resourceshrinker
│   │   ├── retrace
│   │   ├── screenshot2
│   │   └── sdkmanager
│   ├── latest
│   ├── lib
│   │   ├── analytics-library
│   │   │   ├── protos
│   │   │   │   └── src
│   │   │   │       └── main
│   │   │   │           └── proto
│   │   │   │               └── proto.jar
│   │   │   ├── shared
│   │   │   │   └── tools.analytics-shared.jar
│   │   │   └── tracker
│   │   │       └── tools.analytics-tracker.jar
│   │   ├── annotations
│   │   │   └── annotations.jar
│   │   ├── apkanalyzer-classpath.jar
│   │   ├── apkparser
│   │   │   ├── analyzer
│   │   │   │   └── analyzer.jar
│   │   │   ├── cli
│   │   │   │   └── analyzer-cli.jar
│   │   │   └── tools.binary-resources.jar
│   │   ├── avdmanager-classpath.jar
│   │   ├── build-system
│   │   │   ├── aapt2-proto
│   │   │   │   └── aapt2-proto.jar
│   │   │   ├── builder-model
│   │   │   │   └── builder-model.jar
│   │   │   ├── shrinker
│   │   │   │   └── libshrinker.jar
│   │   │   └── tools.manifest-merger.jar
│   │   ├── common
│   │   │   └── tools.common.jar
│   │   ├── ddmlib
│   │   │   └── tools.ddmlib.jar
│   │   ├── device_validator
│   │   │   └── tools.dvlib.jar
│   │   ├── external
│   │   │   ├── archive-patcher
│   │   │   │   ├── explainer.jar
│   │   │   │   ├── generator.jar
│   │   │   │   └── shared.jar
│   │   │   ├── com
│   │   │   │   ├── android
│   │   │   │   │   └── tools
│   │   │   │   │       └── smali
│   │   │   │   │           ├── smali-baksmali
│   │   │   │   │           │   └── 3.0.3
│   │   │   │   │           │       └── smali-baksmali-3.0.3.jar
│   │   │   │   │           ├── smali-dexlib2
│   │   │   │   │           │   └── 3.0.3
│   │   │   │   │           │       └── smali-dexlib2-3.0.3.jar
│   │   │   │   │           └── smali-util
│   │   │   │   │               └── 3.0.3
│   │   │   │   │                   └── smali-util-3.0.3.jar
│   │   │   │   ├── beust
│   │   │   │   │   └── jcommander
│   │   │   │   │       └── 1.78
│   │   │   │   │           └── jcommander-1.78.jar
│   │   │   │   ├── google
│   │   │   │   │   ├── code
│   │   │   │   │   │   ├── findbugs
│   │   │   │   │   │   │   └── jsr305
│   │   │   │   │   │   │       └── 3.0.2
│   │   │   │   │   │   │           └── jsr305-3.0.2.jar
│   │   │   │   │   │   └── gson
│   │   │   │   │   │       └── gson
│   │   │   │   │   │           └── 2.10
│   │   │   │   │   │               └── gson-2.10.jar
│   │   │   │   │   ├── errorprone
│   │   │   │   │   │   └── error_prone_annotations
│   │   │   │   │   │       └── 2.16
│   │   │   │   │   │           └── error_prone_annotations-2.16.jar
│   │   │   │   │   ├── guava
│   │   │   │   │   │   ├── failureaccess
│   │   │   │   │   │   │   └── 1.0.1
│   │   │   │   │   │   │       └── failureaccess-1.0.1.jar
│   │   │   │   │   │   ├── guava
│   │   │   │   │   │   │   └── 31.1-jre
│   │   │   │   │   │   │       └── guava-31.1-jre.jar
│   │   │   │   │   │   └── listenablefuture
│   │   │   │   │   │       └── 9999.0-empty-to-avoid-conflict-with-guava
│   │   │   │   │   │           └── listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar
│   │   │   │   │   ├── j2objc
│   │   │   │   │   │   └── j2objc-annotations
│   │   │   │   │   │       └── 1.3
│   │   │   │   │   │           └── j2objc-annotations-1.3.jar
│   │   │   │   │   ├── jimfs
│   │   │   │   │   │   └── jimfs
│   │   │   │   │   │       └── 1.1
│   │   │   │   │   │           └── jimfs-1.1.jar
│   │   │   │   │   └── protobuf
│   │   │   │   │       └── protobuf-java
│   │   │   │   │           └── 3.19.3
│   │   │   │   │               └── protobuf-java-3.19.3.jar
│   │   │   │   └── sun
│   │   │   │       ├── activation
│   │   │   │       │   └── javax.activation
│   │   │   │       │       └── 1.2.0
│   │   │   │       │           └── javax.activation-1.2.0.jar
│   │   │   │       ├── istack
│   │   │   │       │   └── istack-commons-runtime
│   │   │   │       │       └── 3.0.8
│   │   │   │       │           └── istack-commons-runtime-3.0.8.jar
│   │   │   │       └── xml
│   │   │   │           └── fastinfoset
│   │   │   │               └── FastInfoset
│   │   │   │                   └── 1.2.16
│   │   │   │                       └── FastInfoset-1.2.16.jar
│   │   │   ├── commons-codec
│   │   │   │   └── commons-codec
│   │   │   │       └── 1.15
│   │   │   │           └── commons-codec-1.15.jar
│   │   │   ├── commons-io
│   │   │   │   └── commons-io
│   │   │   │       └── 2.4
│   │   │   │           └── commons-io-2.4.jar
│   │   │   ├── commons-logging
│   │   │   │   └── commons-logging
│   │   │   │       └── 1.2
│   │   │   │           └── commons-logging-1.2.jar
│   │   │   ├── jakarta
│   │   │   │   ├── activation
│   │   │   │   │   └── jakarta.activation-api
│   │   │   │   │       └── 1.2.1
│   │   │   │   │           └── jakarta.activation-api-1.2.1.jar
│   │   │   │   └── xml
│   │   │   │       └── bind
│   │   │   │           └── jakarta.xml.bind-api
│   │   │   │               └── 2.3.2
│   │   │   │                   └── jakarta.xml.bind-api-2.3.2.jar
│   │   │   ├── javax
│   │   │   │   └── inject
│   │   │   │       └── javax.inject
│   │   │   │           └── 1
│   │   │   │               └── javax.inject-1.jar
│   │   │   ├── lint-psi
│   │   │   │   ├── intellij-core
│   │   │   │   │   └── intellij-core-mvn.jar
│   │   │   │   ├── kotlin-compiler
│   │   │   │   │   └── kotlin-compiler-mvn.jar
│   │   │   │   └── uast
│   │   │   │       └── uast.jar
│   │   │   ├── net
│   │   │   │   ├── java
│   │   │   │   │   └── dev
│   │   │   │   │       └── jna
│   │   │   │   │           ├── jna
│   │   │   │   │           │   └── 5.6.0
│   │   │   │   │           │       └── jna-5.6.0.jar
│   │   │   │   │           └── jna-platform
│   │   │   │   │               └── 5.6.0
│   │   │   │   │                   └── jna-platform-5.6.0.jar
│   │   │   │   └── sf
│   │   │   │       ├── jopt-simple
│   │   │   │       │   └── jopt-simple
│   │   │   │       │       └── 4.9
│   │   │   │       │           └── jopt-simple-4.9.jar
│   │   │   │       └── kxml
│   │   │   │           └── kxml2
│   │   │   │               └── 2.3.0
│   │   │   │                   └── kxml2-2.3.0.jar
│   │   │   ├── org
│   │   │   │   ├── apache
│   │   │   │   │   ├── commons
│   │   │   │   │   │   └── commons-compress
│   │   │   │   │   │       └── 1.21
│   │   │   │   │   │           └── commons-compress-1.21.jar
│   │   │   │   │   └── httpcomponents
│   │   │   │   │       ├── httpclient
│   │   │   │   │       │   └── 4.5.14
│   │   │   │   │       │       └── httpclient-4.5.14.jar
│   │   │   │   │       ├── httpcore
│   │   │   │   │       │   └── 4.4.16
│   │   │   │   │       │       └── httpcore-4.4.16.jar
│   │   │   │   │       └── httpmime
│   │   │   │   │           └── 4.5.6
│   │   │   │   │               └── httpmime-4.5.6.jar
│   │   │   │   ├── bouncycastle
│   │   │   │   │   ├── bcpkix-jdk15on
│   │   │   │   │   │   └── 1.67
│   │   │   │   │   │       └── bcpkix-jdk15on-1.67.jar
│   │   │   │   │   └── bcprov-jdk15on
│   │   │   │   │       └── 1.67
│   │   │   │   │           └── bcprov-jdk15on-1.67.jar
│   │   │   │   ├── checkerframework
│   │   │   │   │   └── checker-qual
│   │   │   │   │       └── 3.21.2
│   │   │   │   │           └── checker-qual-3.21.2.jar
│   │   │   │   ├── glassfish
│   │   │   │   │   └── jaxb
│   │   │   │   │       ├── jaxb-runtime
│   │   │   │   │       │   └── 2.3.2
│   │   │   │   │       │       └── jaxb-runtime-2.3.2.jar
│   │   │   │   │       └── txw2
│   │   │   │   │           └── 2.3.2
│   │   │   │   │               └── txw2-2.3.2.jar
│   │   │   │   ├── jetbrains
│   │   │   │   │   ├── annotations
│   │   │   │   │   │   └── 13.0
│   │   │   │   │   │       └── annotations-13.0.jar
│   │   │   │   │   ├── intellij
│   │   │   │   │   │   └── deps
│   │   │   │   │   │       └── trove4j
│   │   │   │   │   │           └── 1.0.20200330
│   │   │   │   │   │               └── trove4j-1.0.20200330.jar
│   │   │   │   │   ├── kotlin
│   │   │   │   │   │   ├── kotlin-reflect
│   │   │   │   │   │   │   └── 1.9.0
│   │   │   │   │   │   │       └── kotlin-reflect-1.9.0.jar
│   │   │   │   │   │   ├── kotlin-stdlib
│   │   │   │   │   │   │   └── 1.9.0
│   │   │   │   │   │   │       └── kotlin-stdlib-1.9.0.jar
│   │   │   │   │   │   ├── kotlin-stdlib-common
│   │   │   │   │   │   │   └── 1.9.0
│   │   │   │   │   │   │       └── kotlin-stdlib-common-1.9.0.jar
│   │   │   │   │   │   ├── kotlin-stdlib-jdk7
│   │   │   │   │   │   │   └── 1.9.0
│   │   │   │   │   │   │       └── kotlin-stdlib-jdk7-1.9.0.jar
│   │   │   │   │   │   └── kotlin-stdlib-jdk8
│   │   │   │   │   │       └── 1.9.0
│   │   │   │   │   │           └── kotlin-stdlib-jdk8-1.9.0.jar
│   │   │   │   │   └── kotlinx
│   │   │   │   │       └── kotlinx-cli-jvm
│   │   │   │   │           └── 0.3.1
│   │   │   │   │               └── kotlinx-cli-jvm-0.3.1.jar
│   │   │   │   ├── jvnet
│   │   │   │   │   └── staxex
│   │   │   │   │       └── stax-ex
│   │   │   │   │           └── 1.8.1
│   │   │   │   │               └── stax-ex-1.8.1.jar
│   │   │   │   └── ow2
│   │   │   │       └── asm
│   │   │   │           ├── asm
│   │   │   │           │   └── 9.2
│   │   │   │           │       └── asm-9.2.jar
│   │   │   │           ├── asm-analysis
│   │   │   │           │   └── 9.2
│   │   │   │           │       └── asm-analysis-9.2.jar
│   │   │   │           └── asm-tree
│   │   │   │               └── 9.2
│   │   │   │                   └── asm-tree-9.2.jar
│   │   │   ├── xerces
│   │   │   │   └── xercesImpl
│   │   │   │       └── 2.12.0
│   │   │   │           └── xercesImpl-2.12.0.jar
│   │   │   └── xml-apis
│   │   │       └── xml-apis
│   │   │           └── 1.4.01
│   │   │               └── xml-apis-1.4.01.jar
│   │   ├── layoutlib-api
│   │   │   └── tools.layoutlib-api.jar
│   │   ├── lint
│   │   │   ├── cli
│   │   │   │   └── cli.jar
│   │   │   ├── lint-checks-proto.jar
│   │   │   ├── tools.lint-api.jar
│   │   │   ├── tools.lint-checks.jar
│   │   │   └── tools.lint-model.jar
│   │   ├── lint-classpath.jar
│   │   ├── misc
│   │   │   └── screenshot2
│   │   │       └── libscreenshot2lib.jar
│   │   ├── profgen
│   │   │   ├── profgen
│   │   │   │   └── libprofgen.jar
│   │   │   └── profgen-cli
│   │   │       └── libprofgen-cli-lib.jar
│   │   ├── profgen-classpath.jar
│   │   ├── r8.jar
│   │   ├── README
│   │   ├── repository
│   │   │   └── tools.repository.jar
│   │   ├── resourceshrinker-classpath.jar
│   │   ├── retrace-classpath.jar
│   │   ├── screenshot2-classpath.jar
│   │   ├── sdk-common
│   │   │   └── tools.sdk-common.jar
│   │   ├── sdklib
│   │   │   ├── libavdmanager_lib.jar
│   │   │   ├── libsdkmanager_lib.jar
│   │   │   ├── sdklib.core.jar
│   │   │   └── tools.sdklib.jar
│   │   └── sdkmanager-classpath.jar
│   ├── NOTICE.txt
│   └── source.properties
└── commandlinetools-linux-11076708_latest.zip
```