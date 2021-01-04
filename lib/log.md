Microsoft Windows [Version 10.0.17763.1637]
(c) 2018 Microsoft Corporation. All rights reserved.
C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git init
Reinitialized existing Git repository in C:/Users/starter/AndroidStudioProjects/flutter_design_patterns/.git/
C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git add lib
C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git commit -m "first commit"
On branch main
Untracked files:
(use "git add <file>..." to include in what will be committed)
.gitignore
    .metadata
LICENSE
README.md
android/
assets/
ios/
pubspec.yaml
test/

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git add flutter_design_patterns
fatal: pathspec 'flutter_design_patterns' did not match any files

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git add .gitignore
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        .metadata

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        LICENSE
'LICENSE' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        README.md

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        android/
'android' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        assets/
'assets' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        ios/
'ios' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        pubspec.yaml

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>        test/
'test' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git add lib

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git commit -m "first commit"
[main f419be2] first commit
1 file changed, 71 insertions(+)
create mode 100644 .gitignore

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git branch -M downloadmanager

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git remote add origin https://github.com/nowxel/test.git
fatal: remote origin already exists.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/nowxel/test.git'

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git commit -m "initial commit"
On branch downloadmanager
Untracked files:
(use "git add <file>..." to include in what will be committed)
.metadata
LICENSE
README.md
android/
assets/
ios/
pubspec.yaml
test/

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git add .
warning: LF will be replaced by CRLF in .metadata.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in LICENSE.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/data/design_patterns.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/abstract-factory.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/adapter.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/bridge.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/builder.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/chain-of-responsibility.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/command.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/composite.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/decorator.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/facade.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/factory-method.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/flyweight.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/interpreter.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/iterator.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/memento.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/prototype.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/proxy.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/singleton.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/state.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/strategy.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/template-method.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in assets/markdown/visitor.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in pubspec.yaml.
The file will have its original line endings in your working directory

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git commit -m "initial commit"
[downloadmanager 2322832] initial commit
128 files changed, 8060 insertions(+)
create mode 100644 .metadata
create mode 100644 LICENSE
create mode 100644 README.md
create mode 100644 android/.gitignore
create mode 100644 android/app/build.gradle
create mode 100644 android/app/src/debug/AndroidManifest.xml
create mode 100644 android/app/src/main/AndroidManifest.xml
create mode 100644 android/app/src/main/kotlin/com/example/flutter_design_patterns/MainActivity.kt
create mode 100644 android/app/src/main/res/drawable-v21/launch_background.xml
create mode 100644 android/app/src/main/res/drawable/launch_background.xml
create mode 100644 android/app/src/main/res/mipmap-hdpi/ic_launcher.png
create mode 100644 android/app/src/main/res/mipmap-mdpi/ic_launcher.png
create mode 100644 android/app/src/main/res/mipmap-xhdpi/ic_launcher.png
create mode 100644 android/app/src/main/res/mipmap-xxhdpi/ic_launcher.png
create mode 100644 android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png
create mode 100644 android/app/src/main/res/values-night/styles.xml
create mode 100644 android/app/src/main/res/values/styles.xml
create mode 100644 android/app/src/profile/AndroidManifest.xml
create mode 100644 android/build.gradle
create mode 100644 android/gradle.properties
create mode 100644 android/gradle/wrapper/gradle-wrapper.properties
create mode 100644 android/settings.gradle
create mode 100644 assets/data/design_patterns.json
create mode 100644 assets/fonts/Roboto-Medium.ttf
create mode 100644 assets/fonts/Roboto-Regular.ttf
create mode 100644 assets/images/abstract_factory/abstract_factory.png
create mode 100644 assets/images/abstract_factory/abstract_factory_implementation.png
create mode 100644 assets/images/adapter/adapter.png
create mode 100644 assets/images/adapter/adapter_implementation.png
create mode 100644 assets/images/bridge/bridge.png
create mode 100644 assets/images/bridge/bridge_implementation.png
create mode 100644 assets/images/builder/builder.png
create mode 100644 assets/images/builder/builder_implementation.png
create mode 100644 assets/images/chain_of_responsibility/chain_of_responsibility.png
create mode 100644 assets/images/chain_of_responsibility/chain_of_responsibility_implementation.png
create mode 100644 assets/images/command/command.png
create mode 100644 assets/images/command/command_implementation.png
create mode 100644 assets/images/composite/composite.png
create mode 100644 assets/images/composite/composite_implementation.png
create mode 100644 assets/images/decorator/decorator.png
create mode 100644 assets/images/decorator/decorator_implementation.png
create mode 100644 assets/images/facade/facade.png
create mode 100644 assets/images/facade/facade_implementation.png
create mode 100644 assets/images/factory_method/factory_method.png
create mode 100644 assets/images/factory_method/factory_method_implementation.png
create mode 100644 assets/images/flyweight/flyweight.png
create mode 100644 assets/images/flyweight/flyweight_implementation.png
create mode 100644 assets/images/interpreter/interpreter.png
create mode 100644 assets/images/interpreter/interpreter_implementation.png
create mode 100644 assets/images/iterator/iterator.png
create mode 100644 assets/images/iterator/iterator_implementation.png
create mode 100644 assets/images/memento/memento.png
create mode 100644 assets/images/memento/memento_implementation.png
create mode 100644 assets/images/prototype/prototype.png
create mode 100644 assets/images/prototype/prototype_implementation.png
create mode 100644 assets/images/proxy/proxy.png
create mode 100644 assets/images/proxy/proxy_implementation.png
create mode 100644 assets/images/singleton/singleton.png
create mode 100644 assets/images/singleton/singleton_implementation.png
create mode 100644 assets/images/state/state.png
create mode 100644 assets/images/state/state_implementation.png
create mode 100644 assets/images/strategy/strategy.png
create mode 100644 assets/images/strategy/strategy_implementation.png
create mode 100644 assets/images/template_method/template_method.png
create mode 100644 assets/images/template_method/template_method_implementation.png
create mode 100644 assets/images/visitor/visitor.png
create mode 100644 assets/images/visitor/visitor_implementation.png
create mode 100644 assets/markdown/abstract-factory.md
create mode 100644 assets/markdown/adapter.md
create mode 100644 assets/markdown/bridge.md
create mode 100644 assets/markdown/builder.md
create mode 100644 assets/markdown/chain-of-responsibility.md
create mode 100644 assets/markdown/command.md
create mode 100644 assets/markdown/composite.md
create mode 100644 assets/markdown/decorator.md
create mode 100644 assets/markdown/facade.md
create mode 100644 assets/markdown/factory-method.md
create mode 100644 assets/markdown/flyweight.md
create mode 100644 assets/markdown/interpreter.md
create mode 100644 assets/markdown/iterator.md
create mode 100644 assets/markdown/memento.md
create mode 100644 assets/markdown/prototype.md
create mode 100644 assets/markdown/proxy.md
create mode 100644 assets/markdown/singleton.md
create mode 100644 assets/markdown/state.md
create mode 100644 assets/markdown/strategy.md
create mode 100644 assets/markdown/template-method.md
create mode 100644 assets/markdown/visitor.md
create mode 100644 ios/.gitignore
create mode 100644 ios/Flutter/AppFrameworkInfo.plist
create mode 100644 ios/Flutter/Debug.xcconfig
create mode 100644 ios/Flutter/Release.xcconfig
create mode 100644 ios/Runner.xcodeproj/project.pbxproj
create mode 100644 ios/Runner.xcodeproj/project.xcworkspace/contents.xcworkspacedata
create mode 100644 ios/Runner.xcodeproj/project.xcworkspace/xcshareddata/IDEWorkspaceChecks.plist
create mode 100644 ios/Runner.xcodeproj/project.xcworkspace/xcshareddata/WorkspaceSettings.xcsettings
create mode 100644 ios/Runner.xcodeproj/xcshareddata/xcschemes/Runner.xcscheme
create mode 100644 ios/Runner.xcworkspace/contents.xcworkspacedata
create mode 100644 ios/Runner.xcworkspace/xcshareddata/IDEWorkspaceChecks.plist
create mode 100644 ios/Runner.xcworkspace/xcshareddata/WorkspaceSettings.xcsettings
create mode 100644 ios/Runner/AppDelegate.swift
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Contents.json
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-1024x1024@1x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-20x20@1x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-20x20@2x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-20x20@3x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-29x29@1x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-29x29@2x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-29x29@3x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-40x40@1x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-40x40@2x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-40x40@3x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-60x60@2x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-60x60@3x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-76x76@1x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-76x76@2x.png
create mode 100644 ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-83.5x83.5@2x.png
create mode 100644 ios/Runner/Assets.xcassets/LaunchImage.imageset/Contents.json
create mode 100644 ios/Runner/Assets.xcassets/LaunchImage.imageset/LaunchImage.png
create mode 100644 ios/Runner/Assets.xcassets/LaunchImage.imageset/LaunchImage@2x.png
create mode 100644 ios/Runner/Assets.xcassets/LaunchImage.imageset/LaunchImage@3x.png
create mode 100644 ios/Runner/Assets.xcassets/LaunchImage.imageset/README.md
create mode 100644 ios/Runner/Base.lproj/LaunchScreen.storyboard
create mode 100644 ios/Runner/Base.lproj/Main.storyboard
create mode 100644 ios/Runner/Info.plist
create mode 100644 ios/Runner/Runner-Bridging-Header.h
create mode 100644 pubspec.yaml
create mode 100644 test/widget_test.dart

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/nowxel/test.git'

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push downloadmanager
fatal: 'downloadmanager' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push test
fatal: 'test' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git branch -M downloadmanager

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git remote add origin https://github.com/nowxel/test.git
fatal: remote origin already exists.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push -u origin downloadmanager
To https://github.com/nowxel/test.git
! [rejected]        downloadmanager -> downloadmanager (non-fast-forward)
error: failed to push some refs to 'https://github.com/nowxel/test.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push -u downloadmanager
fatal: 'downloadmanager' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git pull
From https://github.com/nowxel/test
* [new branch]      DownloadManager -> origin/DownloadManager
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

git branch --set-upstream-to=origin/<branch> downloadmanager


C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git branch --set-upstream-to=origin/<branch> downloadmanager
The system cannot find the file specified.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git pull downloadmanager
fatal: 'downloadmanager' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git pull origin downloadmanager
From https://github.com/nowxel/test
* branch            downloadmanager -> FETCH_HEAD
fatal: refusing to merge unrelated histories

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>clonehttps://github.com/nowxel/test
'clonehttps:' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>https://github.com/nowxel/test
'https:' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>clone https://github.com/nowxel/test
'clone' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git pull origin --allow-unrelated-histories
From https://github.com/nowxel/test
* [new branch]      DownloadManager -> origin/DownloadManager
You asked to pull from the remote 'origin', but did not specify
a branch. Because this is not the default configured remote
for your current branch, you must specify a branch on the command line.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push -u origin/DownloadManager
fatal: 'origin/DownloadManager' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push -u origin downloadmanager
To https://github.com/nowxel/test.git
! [rejected]        downloadmanager -> downloadmanager (non-fast-forward)
error: failed to push some refs to 'https://github.com/nowxel/test.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git branch --set-upstream downloadmanager origin/downloadmanager
fatal: the '--set-upstream' option is no longer supported. Please use '--track' or '--set-upstream-to' instead.

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git config branch.master.remote origin

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git config branch.master.merge refs/heads/master

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/nowxel/test.git'

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git pull --rebase
From https://github.com/nowxel/test
* [new branch]      DownloadManager -> origin/DownloadManager
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-pull(1) for details.

git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

git branch --set-upstream-to=origin/<branch> downloadmanager


C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git pull --rebase origin main
From https://github.com/nowxel/test
* branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/downloadmanager.

error: failed to push some refs to 'https://github.com/nowxel/test.git'

C:\Users\starter\AndroidStudioProjects\flutter_design_patterns>git push origin downloadmanager
Enumerating objects: 550, done.
Counting objects: 100% (550/550), done.
Delta compression using up to 4 threads
Compressing objects: 100% (522/522), done.
Writing objects: 100% (549/549), 1.84 MiB | 2.05 MiB/s, done.
Total 549 (delta 71), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (71/71), done.
To https://github.com/nowxel/test.git
cc2d149..012ce51  downloadmanager -> downloadmanager

