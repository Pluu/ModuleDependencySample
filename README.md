
# 🚧🚧🚧 테스트 중 🚧🚧🚧

### Gradle task

```
10:50:30 PM: Executing 'pluuGraph'...

Executing tasks: [pluuGraph] in project /Users/pluu/AndroidStudioProjects/ModuleDependencySample


> Configure project :
app
feature1
feature2
kotlin_lib
kotlin_lib2

> Configure project :app
[:app] used com.android.application
Q. :app is Android Module?
A: true

> Configure project :kotlin_lib
[:kotlin_lib] used java-library
Q. :kotlin_lib is Android Module?
A: false

> Configure project :kotlin_lib2
[:kotlin_lib2] used java-library
Q. :kotlin_lib2 is Android Module?
A: false

> Configure project :features:feature1
[:features:feature1] used com.android.library
Q. :features:feature1 is Android Module?
A: true

> Configure project :features:feature2
[:features:feature2] used com.android.library
Q. :features:feature2 is Android Module?
A: true

> Task :app:preBuild UP-TO-DATE
> Task :app:preDebugBuild UP-TO-DATE
> Task :app:compileDebugAidl NO-SOURCE
> Task :app:compileDebugRenderscript NO-SOURCE
> Task :app:generateDebugBuildConfig UP-TO-DATE
> Task :app:checkDebugAarMetadata UP-TO-DATE
> Task :app:generateDebugResValues UP-TO-DATE
> Task :app:mapDebugSourceSetPaths UP-TO-DATE
> Task :app:generateDebugResources UP-TO-DATE
> Task :app:mergeDebugResources UP-TO-DATE
> Task :app:packageDebugResources UP-TO-DATE
> Task :app:parseDebugLocalResources UP-TO-DATE
> Task :app:createDebugCompatibleScreenManifests UP-TO-DATE
> Task :app:extractDeepLinksDebug UP-TO-DATE
> Task :app:processDebugMainManifest UP-TO-DATE
> Task :app:processDebugManifest UP-TO-DATE
> Task :app:processDebugManifestForPackage UP-TO-DATE
> Task :app:processDebugResources UP-TO-DATE
> Task :app:compileDebugKotlin UP-TO-DATE
> Task :app:javaPreCompileDebug UP-TO-DATE
> Task :app:compileDebugJavaWithJavac UP-TO-DATE
> Task :app:bundleDebugClassesToRuntimeJar UP-TO-DATE
> Task :app:bundleDebugClassesToCompileJar UP-TO-DATE
> Task :app:compileDebugUnitTestKotlin UP-TO-DATE
> Task :app:preDebugUnitTestBuild UP-TO-DATE
> Task :app:javaPreCompileDebugUnitTest UP-TO-DATE
> Task :app:compileDebugUnitTestJavaWithJavac NO-SOURCE
> Task :app:processDebugJavaRes NO-SOURCE
> Task :app:processDebugUnitTestJavaRes NO-SOURCE
> Task :app:testDebugUnitTest
> Task :kotlin_lib:compileKotlin UP-TO-DATE
> Task :kotlin_lib:compileJava NO-SOURCE
> Task :kotlin_lib:processResources NO-SOURCE
> Task :kotlin_lib:classes UP-TO-DATE
> Task :kotlin_lib:jar UP-TO-DATE
> Task :kotlin_lib:inspectClassesForKotlinIC UP-TO-DATE
> Task :kotlin_lib:compileTestKotlin UP-TO-DATE
> Task :kotlin_lib:compileTestJava NO-SOURCE
> Task :kotlin_lib:processTestResources NO-SOURCE
> Task :kotlin_lib:testClasses UP-TO-DATE
> Task :kotlin_lib:test
> Task :kotlin_lib2:processResources NO-SOURCE
> Task :kotlin_lib2:processTestResources NO-SOURCE
> Task :features:feature1:preBuild UP-TO-DATE
> Task :features:feature1:preDebugBuild UP-TO-DATE
> Task :features:feature1:compileDebugAidl NO-SOURCE
> Task :features:feature1:compileDebugRenderscript NO-SOURCE
> Task :features:feature1:generateDebugBuildConfig UP-TO-DATE
> Task :features:feature1:generateDebugResValues UP-TO-DATE
> Task :features:feature1:generateDebugResources UP-TO-DATE
> Task :features:feature1:packageDebugResources UP-TO-DATE
> Task :features:feature1:parseDebugLocalResources UP-TO-DATE
> Task :features:feature1:processDebugManifest UP-TO-DATE
> Task :features:feature1:generateDebugRFile UP-TO-DATE
> Task :features:feature1:compileDebugKotlin NO-SOURCE
> Task :features:feature1:processDebugJavaRes NO-SOURCE
> Task :features:feature1:bundleLibResDebug NO-SOURCE
> Task :features:feature1:javaPreCompileDebug UP-TO-DATE
> Task :features:feature1:compileDebugJavaWithJavac UP-TO-DATE
> Task :features:feature1:bundleLibRuntimeToJarDebug UP-TO-DATE
> Task :features:feature1:bundleLibCompileToJarDebug UP-TO-DATE
> Task :features:feature1:preDebugUnitTestBuild UP-TO-DATE
> Task :kotlin_lib2:compileKotlin
> Task :features:feature1:generateDebugUnitTestStubRFile UP-TO-DATE
> Task :kotlin_lib2:compileJava NO-SOURCE
> Task :kotlin_lib2:classes UP-TO-DATE
> Task :kotlin_lib2:jar UP-TO-DATE
> Task :kotlin_lib2:inspectClassesForKotlinIC UP-TO-DATE
> Task :kotlin_lib2:compileTestKotlin UP-TO-DATE
> Task :kotlin_lib2:compileTestJava NO-SOURCE
> Task :kotlin_lib2:testClasses UP-TO-DATE
> Task :kotlin_lib2:test
> Task :features:feature1:compileDebugUnitTestKotlin UP-TO-DATE
> Task :features:feature1:javaPreCompileDebugUnitTest UP-TO-DATE
> Task :features:feature1:compileDebugUnitTestJavaWithJavac NO-SOURCE
> Task :features:feature1:processDebugUnitTestJavaRes NO-SOURCE
> Task :features:feature1:testDebugUnitTest
> Task :features:feature2:preBuild UP-TO-DATE
> Task :features:feature2:preDebugBuild UP-TO-DATE
> Task :features:feature2:compileDebugAidl NO-SOURCE
> Task :features:feature2:compileDebugRenderscript NO-SOURCE
> Task :features:feature2:generateDebugBuildConfig UP-TO-DATE
> Task :features:feature2:generateDebugResValues UP-TO-DATE
> Task :features:feature2:generateDebugResources UP-TO-DATE
> Task :features:feature2:packageDebugResources UP-TO-DATE
> Task :features:feature2:parseDebugLocalResources UP-TO-DATE
> Task :features:feature2:processDebugManifest UP-TO-DATE
> Task :features:feature2:generateDebugRFile UP-TO-DATE
> Task :features:feature2:compileDebugKotlin NO-SOURCE
> Task :features:feature2:processDebugJavaRes NO-SOURCE
> Task :features:feature2:bundleLibResDebug NO-SOURCE
> Task :features:feature2:javaPreCompileDebug UP-TO-DATE
> Task :features:feature2:compileDebugJavaWithJavac UP-TO-DATE
> Task :features:feature2:bundleLibRuntimeToJarDebug UP-TO-DATE
> Task :features:feature2:bundleLibCompileToJarDebug UP-TO-DATE
> Task :features:feature2:preDebugUnitTestBuild UP-TO-DATE
> Task :features:feature2:generateDebugUnitTestStubRFile UP-TO-DATE
> Task :features:feature2:javaPreCompileDebugUnitTest UP-TO-DATE
> Task :features:feature2:processDebugUnitTestJavaRes NO-SOURCE
> Task :features:feature2:compileDebugUnitTestKotlin
> Task :features:feature2:compileDebugUnitTestJavaWithJavac NO-SOURCE
> Task :features:feature2:testDebugUnitTest
> Task :pluuGraph

BUILD SUCCESSFUL in 2s
59 actionable tasks: 7 executed, 52 up-to-date

Build Analyzer results available
10:50:32 PM: Execution finished 'pluuGraph'.
```