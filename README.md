# Responsive
### Responsive is a easy way to implement responsive layout in to your application using flutter. [pub.dev](https://pub.dev/packages/responsive_layout_thrive)

## How to use it?

#### 1. Add the package to your dependencies
``flutter pub add responsive_layout_thrive``
#### 2. In your main.dart do this in the body of the Scaffold
``Scaffold(body: Responsive(mobileBody: const MobileBody(), tabletBody: const TabletBody(), desktopBody: const DesktopBody()),``

#### 3. Now create three files, MobileBody, TabletBody and DesktopBody. In these you put the code for your app

#### 4. The last step is to import the files in to your main.dart file and your good to go
