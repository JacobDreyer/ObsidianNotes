## Flutter
UI Framework for building apps on IOS and Android

DartPad allows you to edit and run flutter code in the browser

#### Create a Project
Open Terminal and run: flutter create "<mark style="background: #CACFD9A6;">name</mark> "

##### Building an App from Scratch
``` dart
//gives you access to pre-built widgets
import 'package:flutter/material.dart';

//main function
void main() {
	//inflates a widget to screen
	//MyApp represents application
	runApp(MyApp());
}

//type: st  : into editor and it should give you a snippet for a stateless widget

class MyApp extends StatelessWidget {
	const ({ Key? key }) : super(key: key);

	@override
	Widget build(BuildContext context) {
		return Container(
		
		);
	}
}

```
